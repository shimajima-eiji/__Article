[公開先](https://qiita.com/nomurasan/items/a2cdaa55aa00fd44e29e)

<a href="https://qiita.com/nomurasan/items/5197100a1ae3e5a30f4c">レベル０のDockerプレイヤーが可能な限りシンプルな状態から勉強したい時の話</a>という記事を書いたんですが、その続きみたいなものです。

# WindowsでもGitlabを運用出来た話

# 補足
今回から注釈記法に対応しました。
注釈数字のリンクをマウスオーバーで参照することを目的に書いているので、他の方とちょっと使い方が異なる事があります。[^1][^2]
[^1]: Qiitaの注釈記法について：凡例（何に対して？：対象の解説、注釈）という書き方をしています。この場合は（注釈記法について：私はこうやってつかってます）みたいな感じです。
[^2]: 【リンク有】Qiitaの注釈記法について・補足：http://blog.qiita.com/post/105484781374/qiita-markdown-supporting-footnotes

# Windows(10 pro)でGitlabを運用したいのでDocker for Windowsで環境を作ってみた。

ということで、google先生に色々聞いてみたんですが、よく分からんかったです。

**ここではVMだとかVagrantだとかVirtual Boxなどは使っていません。**
私がよく分からん事になるので、使用は避けました。
ただ、管理まで考える場合はあった方がいいらしい、という事は何となく認識しているんですが…。
ちょっと理解が追い付いてない状態です。

# 本題

* Docker for Windows入れて、[^3]
* Docker for WindowsをGUIチックに操作できるようにKitematic入れて[^4]
* Gitlab CEを探して入れる[^5]

と、かなり簡単に入れられました。

[^3]: 【リンク有】<a href="http://docs.docker.jp/windows/step_one.html">Docker for Windows ダウンロードページ</a>が私にとっては分かりにくかったのですが、今後のためにちゃんと英語内容も読んでもらった方がいいと思ったのでここでは解説しません。
[^4]: Kitematic：インストールして再起動が完了したらアイコンを右クリック→Kitematicでダウンロードできる
[^5]: Gitlab CEのインストール：Kitematicの画面上からどうぞ

## 注意

Docker for Windowsを動かすところが一番のヤマだと思うので、Hyper-V使えるかどうかは確認しておいたほうがいいです。
例によって例のごとく、Bash on Ubuntu on Windowsに入れようとしたんですが、こっちはgitlabを入れる前段の環境構築で結構面倒くさい事になってしまった[^6]ため、いったん取りやめました。
→<a href="">やってみました。</a>
[^6]: 環境構築が面倒くさい：元々他でも使っている環境なので、変な競合を起こしてしまったらしく…原因はまだ分かっていません。

誤解を恐れずに言うと、私がやりたい用途という意味では、Docker for Windowsでも結局はBash on Ubuntu on Windowsと似たような事をやっているので、今回はあくまで「gitlabを運用したい！」という点だけに絞って話を進めさせていただきたい。

# やること
上にも書いてますが、本当に３ステップ。
途中でハマったのは、他の端末でもファイルを共有したかったので、ブラウザのダウンロード先をネットワークストラテジにしていたため、CドライブのProgram FilesにKitematicを置こうとしたら怒られたぐらい。
普通に使っていたらハマらないです、きっと。

# 構築完了

gitlabのインストールは結構時間が掛かるっぽいです。寝て起きた頃に終わったのでそこまでではないでしょう。

# 問題
多分環境自体は出来てると思うんですが、実際にgitlabを使おうとするとこれがうまくいかない。
gitlabの構築は完了していると思うんだけど、Container logを見ても何をすればいいのか分からない。
試しにexecからpower shellを開いてみるんだけど、何のログを見ればいいとか、恐らくgitlabの根本的な知識がないので調べようがない。
出来る状態にはなってると思うけど、今出来るか？というとちょっと疑問。
要調査ですね…。

# 参考
http://docs.docker.jp/windows/step_one.html

# 類似記事
<a href="https://qiita.com/nomurasan/items/a4291f5a18f3b6cc1525">Windows(10 pro)でGitlabを運用したいのでVagrant+VirtualBoxで環境を作って運用できた話</a>
【ココ】Windows(10 pro)でGitlabを運用したいのでDocker for Windowsで環境を作ってみたけど運用できなかった話
<a href="https://qiita.com/nomurasan/items/b725c9ee9179bcac2b22">Windows(10 pro)でGitlabを運用したいのでBash on Ubuntu on Windowsで環境を作ってみたけど運用できなかった話</a>

# 注釈
