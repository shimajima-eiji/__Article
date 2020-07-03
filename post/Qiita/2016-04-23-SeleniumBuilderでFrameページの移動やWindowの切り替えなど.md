[公開先](https://qiita.com/nomurasan/items/39ebe76f0542bb2df00f)

【Attention】
思ったより長くなってしまったので、検索で来られた方はCtrl+Fしてそこまで飛んでください。

#使用環境

- Firefox
 - 45.0.2 Japanese
 - Beta(46.0) English(JP-lang)
- Selenium
 - Builder3.0.9
 - Builder2.3.5 [2016/08/22 追記／firefox48.0.0以降は使用できません]

#環境説明
以下のようなフレームを使ったページ構成があったとします。

![frame.png](https://qiita-image-store.s3.amazonaws.com/0/122800/7293378f-fcd1-859b-c511-54daaf4ba780.png)

絵ではtopフレームとmainフレームにだいぶスキマがありますが、実際ないものとしておいてください。
topフレーム内の要素に対してアプローチするときは以下のようにします。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/5beff106-7b51-049c-46f3-8ee8d1978826.png)

とても簡単ですね！

##フレームタッチ：main
では次に、mainにアプローチしてみましょう

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/fe799a3a-3274-81cb-0e60-ef1bce1843d8.png)

こう書くと思いますが、これは失敗するんです。
何故か？

答えは簡単で、フレームtop内にフレームmainがいないからですね。
なのでいったんフレームtopから抜けなければなりません。

こうしましょう。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/db0a1ede-9970-b7da-6eaa-4578d093e947.png)

いったん一番上のフレームに戻るようにしてあげればmainフレームへ行けます。

##フレームタッチ：main-left
では次に、main-leftフレームへ行きましょう。
これはさっきと同じ考え方でできます。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/4bb9ea57-a7ed-14aa-20a7-cf20b337b07f.png)

##フレームタッチ：main-right
用事が済んだのでmain-rightフレームへ行きましょう。
main-rightフレームはmain-leftの中にはないのでいったんフレームを戻します。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/0cda1a1d-16f8-9d31-25af-61701e2cb01d.png)

実はこれ、失敗します。

何故か？
ページの直下にmain-rightフレームはないからです。
Selenium Builderのエレベーターは上に登れても下には降りれないんですね、と私は理解しました。
ソースで言うと

``` java:switchToMoveFrame.java
//最上階直通エレベーターのみ
pageObject.switchTo().defaultContent();
```

ですね。
この場合は諦めて階段を使いましょう。

``` java:switchToMoveFrame.java
//階段
pageObject.switchTo().frame("一つ下の階層");
```

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/a4a28e5a-543a-b1c0-bb20-ac9c3ad77002.png)

#top・mainをウィンドウと見た場合
実はこの想定で絵をかいてました。だからスキマを開けていました。

さて、現在topウィンドウにいて、blankなりでmainウィンドウを生成した状態です。
もういちどさっきの絵を出します。

![frame.png](https://qiita-image-store.s3.amazonaws.com/0/122800/7293378f-fcd1-859b-c511-54daaf4ba780.png)

mainウィンドウ内はmain-leftフレームとmain-rightフレームがあるという状態です。
が、ただのウィンドウ・フレームの混合ケースなのでこれでサクッと出来ちゃいます。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/bd2f36cc-e30f-a0a5-f735-c5fa0c2b6a33.png)

##注意！
###追記 2016/08/22]
Firefox48.0.0以降、xpinstall.signatures.required = falseとしても未署名のアドオンが使えなく（制限から禁止へ）されてしまったので、この方法はFirefox47.0.1以前か、Firefox Developer Editionをご活用ください。

###原文
あ…
この記事書いてて知ったんですが、**セレニウムビルダー3.xには『ここから実行』がないので気を付けてください。*
しくじった…

皆さんはやらなくていいんですが、一応手順書いときます。
この記事を参考にSelenium Builder2.3.5を入れます。
http://qiita.com/mihonak/items/28258ec5c242dfe5fe5e

念のために3.xは無効化しておきましょう。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/589f043f-252b-d63c-08b6-2e7d2edcb1e5.png)

ちょっと絵からは分かりにくいですが、2.3.5を入れて3.xを無効化した状態です。
この後Firefoxを再起動をすると設定が適用されるようになります。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/38e3fe7d-8394-3276-bf4a-eafbcfa303b5.png)

では、今後はスクリプトの9行目から実施していく事にします。

#ちょっと脱線：Selenium Builderでコメントを書く
Selenium Builderのコメントの書き方は8のようにやってます。
これが良い方法かは分かりませんが、暫定対処でこうしました。
設定の仕方はこんな感じ。変数は未設定でもいいんですが分かりやすいようにdevnullとでも言っておきます。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/96d01f76-5ac6-ef38-840f-3d161d1c6c76.png)

##もっといい？方法
2016/08/22 追記
記録->値の保存　があります。
スクリプトの保存よりゴチャゴチャしてないので、個人でやるならこっちがお勧めです。
保守を想定した場合は明示的にコメントにする必要があるので、スクリプトの保存でdevnullにするといいでしょう。
運用の方法も色々あると思いますが、私はそうしてきた（出川感）

#Selenium Builderでウィンドウを切り替える
ここからですね。
再掲

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/38e3fe7d-8394-3276-bf4a-eafbcfa303b5.png)

実はこの画像の通りにやると失敗します。

何故か？
target="_blank"で開いたウィンドウには名前がないからです。
これは知らないとハマります。
解決方法は以下。

![image](https://qiita-image-store.s3.amazonaws.com/0/122800/8f14811f-9710-aa97-e0c2-d037532e54cc.png)

SeleniumBuilderの問題解析は結構大変です。
この問題の場合、Javaからソースレベルで追えなければ諦めていたぐらいのレベルです…
この問題（仕様）自体はMozillaのページのどこかに書いてそうなもんですが、HTMLの仕様かな？分からない…

##注意
この方法を使う（使わざるを得ない状態）になると、ローカル実行とサーバー実行の互換性がなくなります。
具体的にはバージョン2と3に互換性がなくなります。
ソースレベルでいうとswitchTo.window("ここの番号がどう頑張っても変わる");からです。

``` java:switchToWindow.java
switchTo().window(”Selenium2の場合は２以降”);
```
（画像はブログにて。すみません）

##運用案
10行目がSelenium3の場合1以降となります。
以降なんてキレイに言ってますが、身もふたもなく言えばよっぽど大きなテストをしない限り固定値みたいなものです。
回避方法としては、サーバー実行時は意味のないページを一つ置いて、そこからテストしたいページの_blankリンクを置いて切り替えるのが一番手っ取り早いです。
その場合、以下手順を追加する事になります。

- ブランク用のページを開く（ウィンドウインデックス0）
- ブランク用のページのブランクリンクをクリック（その結果、新しいウィンドウが開かれる）
- switchTo().window(1);   /* seleniumbuilderのバージョンに注意してください。 */

（画像はブログにて。すみません）

#まとめ
見た目はちょっと良くないですが、やりたいことは実現できます。
topウィンドウからmainウィンドウを開いた時も同じ要領でウィンドウを切り替えればよいのです。
その場合、ウィンドウのインデックスは2。既存コードを書き換える事なく、ローカルとサーバーの同期？が出来るようになりました。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
