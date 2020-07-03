[](https://qiita.com/nomurasan/items/c9a2c076ccf6966961f5)

# はじめに
SeleniumBuilderで作ったJsonファイルを使うのではなく、**JavaなりRubyなりお好みの言語にエクスポートして使ったほうがなんぼかマシ**です。
ということで、実際にSeleniumBuilderでファイルを作ってServerに渡します。

# 前提条件
SeleniumBuilderの操作が出来る、分かる人
[参考先](http://qiita.com/nomurasan/items/39ebe76f0542bb2df00f)が分かれば大丈夫です。


# サーバーで動かす理由
プログラマーならコード書いて動かしたいよね！
というところから始まります。
他にも、ヘッドレスで実行できるのでテスト作業がとてもスムーズになります。

# 環境ありますか？
[さっき作ったのでどうぞ](http://qiita.com/nomurasan/items/0e8c342576c90ce2a4cf)
ここで作る環境はあくまでブラウザから実行する場合の話なので、この後で動かすサーバーとはちょっと分けて考えてほしいです。
[追記]もしかしたらSeleniumBuilder3.x系じゃないとダメかも知れません。

# 更に環境を作ります。
SeleniumServerのStandaloneが必要です。
が、[いつものところ](http://docs.seleniumhq.org/)では最新版しか取得できないので、ちょっと回り道します。

[Use Selenium WebDriver 2.53.1 with Firefox 47.0.1](http://seleniumsimplified.com/2016/06/use_selenium_webdriver_jar_locally/)
ここに環境の内訳が全部書いてます。
あとはJavaを入れてターミナル（プロンプト）からダウンロードしたSeleniumServerを実行するとできます。パスが通っているならjava -jar (selenium...jar)で起動したら、SeleniumBuilderの画面から実行->サーバーで動く（ターミナルがなんか反応する）と思います。
もしここで動きが見られないならブラウザを再起動してみてください。

## Javaの入れ方
探せばいっぱいあります。お使いの環境によっては共存させる必要があるかも知れません。

## パスの通し方
[windowsならこの辺](http://realize.jounin.jp/path.html)とかを参考に。
他にもいいサイトはあります。

# 動かしてみよう
SeleniumBuilderで作った操作ファイルはjsonと各環境に合わせて２つ用意しましょう。
SeleniumBuilderはJavaとかRubyとかPython、JavaScriptとC#は読めませんがエクスポートは出来る。一方通行です。
操作部分で修正とかがあるとjsonを変更する方が将来的に楽です。

エクスポートした後は、webdriverにmarionetteの設定を忘れずに。

# エラーになる場合
webdriver側の問題であることが多いです。
Firefox46.0.1だとmarionetteなくても動くはずですが、それより新しいバージョンだとエラーログから推測していくのが良いと思います。
おすすめのサイトはteratailではなく[stackoverflow(リンクは日本語にしておきました)](http://ja.stackoverflow.com/)です。

# コツ
英語ばかりのサイトを開いて即行閉じないのがコツです。
難しいことは書いていません。

## 疑問
[seleniumhq](http://docs.seleniumhq.org/)でメジャーバージョンアップとはいえベータ版である3.0.0beta2を押しているのか、よく分かりません…

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
