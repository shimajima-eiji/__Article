[公開先](https://qiita.com/nomurasan/items/5b97f9664370d5d6d2bc)

# タイトルについて
私用のアプリをサクッと作っていた時にコンソールがエラーで埋め尽くされたので原因を調べていたら、参照できないオブジェクト（null）に対し操作をしているらしい事が分かった。
ページごとに必ず発生しているがエラー件数も違うので原因がつかめずハマったのでviewを見ながらビルドしたところjsファイルに問題がある事が発覚した。

昨今のフレームワークはこういう作りになっている事は珍しいが、古いCMSだとありそうだな、と思ったので提案。

**良かれと思って書いているがバッドノウハウである**（後述）事は留意しておいてほしい。

# 前提
- 生成側ではhtmlソースを管理していない
  - たとえばindex.phpとかcontents.phpのようなファイルは存在しないか、編集不可である
  - 生成されたhtmlファイルをview側で変更できない
- 複数のページで同じjsファイルを呼び出している
- 呼び出されるjsファイルはscript.jsしかない
- jsとcssは編集できる

という場合を想定。
なお、実際はユーザーが参照するファイルはhtmlではないのですが、説明をしやすいようにここでは生成物をhtmlとしている。

## 生成されるソースコード例
``` index.html
（中略）
<script src="script.js">
（中略）
<section id="top_block">
（中略）
<!-- こちらにid:contents_blockは存在しない -->
```

``` contents.html
（中略）
<script src='script.js'>
（中略）
<section id="contents_block">
（中略）
<!-- こちらにid:top_blockは存在しない -->
```

この時、`id:top_block`と`id:contents_block`に対して何かしらのアプローチをしたい場合、他のページで存在しない要素に対して制御を行うとブラウザのコンソールに期待しないエラーが発生するためデバッグが面倒になる。
これが少ない数なら無視できるが、それぞれのページや要素に対して何か行っている場合、呼び出している回数だけエラーが発生することになってしまう。

# 解決（提案）
``` script.js
function run_judge_function ( obj, func )
{
  obj == null ? null : func();
}
```

関数を実施させる際に直接呼び出すのではなく、`run_judge_function`に**対象となるオブジェクト**と**実施したい関数**を渡してnull(undefined)を検出してあげて、見つかれば実施したい関数を実行するというアプローチを検討する。

### 名前が良くないので何か良いものを考えたい。
- run_judge_function: 関数を実行するか判定する。こういった関数を作る場合、returnはtrue/falseが望ましい事が多いが、呼び出し元でif(result) みたいに書くのが手間なので省略。

## 使用例
``` script.js
let topObj = document.getElementById('top_block');
let contentsObj = document.getElementById('contents_block');

function run_judge_function ( obj, func )
{
  if(!obj)func();
}

function run_top_object() {
  // topObjへの処理
}
function run_contents_object() {
  // contentsObjへの処理
}

run_judge_function (topObj, run_top_object);
run_judge_function (contentsObj, run_contents_object);
```

## 他案
わざわざ名前空間を汚す必要はないので、こちらの方がスマート。

``` script.js
let topObj = document.getElementById('top_block');
let contentsObj = document.getElementById('contents_block');

function run_top_object() {
  if(!topObj) return;
  // topObjへの処理
}

function run_contents_object() {
  if(!contentsObj) return;
  // contentsObjへの処理
}

run_top_object();
run_contents_object();
```

この程度の内容なら`run_judge_function`を作る必要はないので、それぞれの`run_obj`内で制御してしまうのがベターか。
ただし、**実行しない条件について変更が生じた際はすべての`run_obj`に変更が必要**なので、将来性を見据えるなら作っておくのも良い。

## 注意
この関数が想定される・本来は検出したいエラーを揉み消す可能性があり、本番環境に乗せてしまうと異常が発生した場合に適切なエラーログが取得できない事が考えられる。

``` script.js
let stage_flg = true;  // ※１
function run_judge_function ( obj, func )
{
  if (stage_flg) obj == null ? null : func();
}
```

（※１[^1]）
としておくと、消し忘れを防止できるが検証環境と本番環境で差異が発生する事に留意。
検証環境の時はtrue、そうでなければfalseにする環境変数を用意しておく事も検討すべきか。

## 備考
本来は呼び出し側で適切なスクリプトを参照するようにしてあげるのがスマートだが、これらのhtmlソースを生成する側のファイルでヘッダ情報などを共通化しているために起こってしまう。
生成側のファイルを変更できるなら調整や対応をissueに上げるべきだが、今回はあくまでview側で解決する場合を考えた。

## 注意とお節介
この問題は現場でも起こる可能性があるのではないかと考えており、たとえばプロジェクト初期に想定されなかった要素を継ぎ接ぎで追加した時に起こりがちな問題ではないだろうか？
後で継ぎ接ぎした時に**良かれと思って**こういう関数をかますと（既存部分への影響が大きすぎてテストが大変になり）メチャクチャ怒られるのが普通なので導入時は注意するか、なんならstage環境にも上げるべきではない。

githubなどコードレビュー文化が根付いているならチェックが入るはずだが、**コードを書けるプロの人はレビューもプロか？というとそうではない**ので運用上の注意が必要。

# お願い
ページを参照した（view）がイコール最後まで読んでもらった（complete）と思っていないので、お手数を掛けて恐縮だがLGTMをいただけると、読みやすい書き方や記事がどういうものか分析しやすくなり大変助かります。

# 注釈
[^1]: 【※１】実際の使用例としてstage_flgは環境変数か何かで設定する事が望ましい。
