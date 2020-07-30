[公開先](https://note.com/nomuragoro/n/nc4374b8b4fc1)

![コード比較](https://user-images.githubusercontent.com/15845907/88918795-0693ae80-d2a5-11ea-9c8e-8ef608e9ccea.png)

予めお伝えしておきますが、プログラマー向けです。
プログラマーじゃなくても使えますし、読めるように書いていますが、プログラマー以外には価値が薄いと思います。

# サンプルコード

https://codepen.io/nomuraya/embed/BayaMzJ?default-tab=&theme-id=

カーソルキーを押したら押したキーが表示されるだけの簡単なものです。
ここで使うのはjsファイルについてですが、jsファイルの内容を知る必要はないです。

# コードとgistで見る
世の中のサンプルコードがCodePenで見れるワケではないので、code記法とGistで比較してみましょう。

## code
document.onkeydown = keydown;

function keydown() {
 if (event.key == "ArrowUp") {
   document.getElementById("displayArea").textContent = "↑";
 } else if (event.key == "ArrowDown") {
   document.getElementById("displayArea").textContent = "↓";
 } else if (event.key == "ArrowLeft") {
   document.getElementById("displayArea").textContent = "←";
 } else if (event.key == "ArrowRight") {
   document.getElementById("displayArea").textContent = "→";
 } else {
   document.getElementById("displayArea").textContent = event.key;
 }
}
## Gist

https://gist.github.com/shimajima-eiji/a3077686179f1c298e6cc1d4845554bf#file-script-js

背景の黒と白の差が目を引きますが、行番号が振られているかとかシンタックスハイライトは見過ごせません。
Gistの埋め込みにダークモードがあれば使いやすいのですが、うまく見つけられませんでした。
が、noteのダークモードがあるのでそちらを使うことで、背景の問題は解決できます。

https://note.com/bluepixel/n/nbb6ff4c58976

chrome拡張機能が欲しくてダウンロードリンクに飛んだのですが、こちらだとうまくダウンロードできませんでしたので、ダウンロードリンクを掲載しておきます。

https://chrome.google.com/webstore/detail/note-dark/ndjhheglhimmpjbgedbacgmloigpicng

# CodePenの開発について

https://www.webprofessional.jp/web-maker-an-offline-browser-based-codepen-alternative/

いちいちCodePenを開くのが面倒くさいな、と思っていたらありました。

# Gistを使いやすくしたい！
Gistを使い始めるとすぐに感じるのが、非常に管理しにくいのです。
スニペットを撒き散らす分には良いんですが、管理したくなると大変です。

そこで、Cacherというサービスを使います。Githubアカウントがあれば使えるので、Gistを持っている人は何もしなくても使い始めることができます。

https://www.cacher.io/

ローカルで使えるスタンドアローン版もダウンロードできますが、chrome拡張機能でやりたい事が完結できます。
ブラウジングのメモリを軽くしたい時ぐらいでしょうか。

https://chrome.google.com/webstore/detail/cacher/aiiaandmkmekfhembfoghdnfiiiedhhk
