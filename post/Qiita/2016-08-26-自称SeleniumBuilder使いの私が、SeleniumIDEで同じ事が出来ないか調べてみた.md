[公開先](https://qiita.com/nomurasan/items/69233da8e8beb45f51af)

SeleniumBuilderがFirefox48系に淘汰されたため、これを機会にIDEに乗り換えることにしました。
とはいえ、既存のシステムを改修する必要があるため、色々と問題になりそうな部分を調査してみます。

今回のテーマはこちら

- フレームの切り替え
- ウィンドウ(タブ含む）の切り替え

たぶん沼だと思います。

# 前提条件
フロントをFrameで作るな！
と言いたい所ですが、これは出来ないものとしてください…


# 調査環境

- Firefox46.0.1
- SeleniumIDE2.1.1.1-signed
- SeleniumBuilder2.3.5

# 本題：フレーム
ログインしてその先のフレームページのリンクをクリックして
フレームのレイアウトイメージとしてはこんな感じ

- (root)
	- main
		- nav
		- contains

思わず画面ごと叩き割りたくなりますが、ここはぐっと堪えます。
こういうレイアウトの画面に対してSeleniumIDEからアプローチします。

（作るのが面倒だったので某サイトさまのページレイアウトをローカルに作成して使用しています）

## Selenium IDE

![ide.png](https://qiita-image-store.s3.amazonaws.com/0/122800/61a93d07-9e62-5e4e-26a4-3b9ac1a39a50.png)
## Selenium Builder

![builder.png](https://qiita-image-store.s3.amazonaws.com/0/122800/babab318-045b-6b25-7263-b0ac205e532f.png)

# 本題：ウィンドウ
では、同じようにウィンドウを使ってみましょう。

## Selenium IDE

色々やってうまくいかなかったので、秘伝のタレをいただきました！
[もぎゃろぐ さま](http://blog.mogya.com/2009/07/selenuimtarget-blank.html)

![windowide.png](https://qiita-image-store.s3.amazonaws.com/0/122800/f2b14512-0e41-454c-184b-9196927d199d.png)

## Selenium Builder
コツはswitchToWindowByIndex。ウィンドウの変更ではうまく出来ません（名前がないため）
![windowbuilder.png](https://qiita-image-store.s3.amazonaws.com/0/122800/5a5c6821-fd2f-8154-634c-8f26f9f1fed1.png)

とりあえずこれで行けるっちゃ行けます。
たぶん秘伝のタレをいい感じに使えばBuilderでも使えるんじゃないでしょうか。
（需要があるかどうかは別として）

とはいえ、フレームやウィンドウの処理はホント魔窟です…
可能ならdivなりsectionなりで組み替えて欲しいです…

# 補足
ビデンスを取得するという意味では、これらの方法では結構怪しいです。
試しに取れるのか検証してみました。
（面倒なのでこれまたコンテンツ丸コピしちゃってます。画面が見えるとアレなのでなんとなく雰囲気を感じ取ってください）

## frame

### Selenium IDE
キャプチャソースです。
![captIDE.png](https://qiita-image-store.s3.amazonaws.com/0/122800/7e71d6e9-33f9-ce47-dde8-35eab4f5ba80.png)

outframe
![outframe.png](https://qiita-image-store.s3.amazonaws.com/0/122800/bacbc677-7e27-d1f4-ba42-69c50373acc5.png)

inframe
![inframe.png](https://qiita-image-store.s3.amazonaws.com/0/122800/1f0358c7-5374-0f88-36b1-33708071912c.png)

何となく分かりますかね？
outframeの外側がinframeに見つからないのを雰囲気で感じてもらえれば。

### Selenium Builder
こちらはどのパターンでもIDEのoutframeと同じ結果を返します。

![captBuilder.png](https://qiita-image-store.s3.amazonaws.com/0/122800/0dc04182-d65a-d41c-8a4b-a178826db9d1.png)

## window
### Selenium IDE
秘伝のタレの味が強すぎたようです。ちょっとエビデンスとして使用するのは辛いレベル。
黒塗りは私がやったのではありません。

![bokashi.png](https://qiita-image-store.s3.amazonaws.com/0/122800/8fd313c2-2908-9823-beca-c2ac99585479.png)

### Selenium Builder
想定していた結果はこちら。
背景黒にならず、きちんと取れている事を確認します（ボカシてるので確認も何もないですが）

![outframe.png](https://qiita-image-store.s3.amazonaws.com/0/122800/bacbc677-7e27-d1f4-ba42-69c50373acc5.png)

# まとめ

エビデンス取得を考慮する場合（というか大半？）は吟味したほうがいいです。
場合によっては外から画面キャプチャ撮るぐらいの方がいいかもしれませんね。

[→書きました。
SeleniumIDE・Builderのイケてないキャプチャ機能を改修する](http://qiita.com/nomurasan/items/21c9dabe898dfebe2a5c)

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
