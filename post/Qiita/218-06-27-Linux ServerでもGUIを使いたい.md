[公開先](https://qiita.com/nomurasan/items/68df96053e03215b542b)

**当たり前ですが、Serverで使っている以上GUIは使えません。**
が、GUIがなくてもGUIを使いたいのが本記事の趣旨です。

# やり方
GUIがある端末でttyを立ち上げて以下のコマンドを実行するだけです。
動かすだけならオプションは-Yだけでいいです。

``` client.tty
ssh -XYC (user)@(ip/host)
# GUIでやりたいこと firefoxとか
```

# 構成
以下、注意事項です。
- クライアントがGUIに対応していないと表示されない
    - つまり、Desktop版からsshで接続する必要があります。
- Windows Subsystem for Linux(Bash on Windows on Ubuntu)だとダメでした。
- Windowsから実行する場合は更に設定が必要かも？

実施時はUbuntu16ですが、CentOSほかでも同じだと思います。

# 細かい話
ここにたどり着くまでにxサーバーに対して色々やるのでxhostが必要だとか、.Xauthorityにaddするとか、
あるいは/etc/ssh/ssh_configのX11を有効にしてポートフォワーディングをするとか、TCPポートをLISTENにして$DISPLAYにlocalhost:0.0を入れる…などなど、
かなり遠回りをしましたが、実は上記でいけました。
場合によってはssh_configのX11を有効にする作業[^1]は必要かもしれません。

# 注釈
[^1]: 【X11を有効にする】ForwardX11 = yesにしてsshを再起動する

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
