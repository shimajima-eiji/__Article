[公開先](https://qiita.com/nomurasan/items/95837a309f4bc8a0dbae)

# もくじ
- WindowsのIDEで開発したものをそのまま使える環境を作る
- 開発用で使えるWebサーバーを作る
- テスト・デバッグで使えるAPIサーバーを構築する
- MySQLを入れてMysql Workbenchをもっと快適にする
- Dockerを入れて環境を壊しやすくする

# 事前準備
インストールについては他にいっぱいやり方が書いてあるのでそちらを参照のこと。
ここでは便宜的にwinrootというユーザーとする。
また、インストール後はapt updateを実施している。

#  WindowsのIDEで開発したものをそのまま使える環境を作る
ちょっとしたものを作るぐらいならエディタでいいけど、凝ったものを作り出すと主にデバッグ・トレース面でキツいのでなるべくIDEを使いたいというところから。
IDEのソースフォルダをgitに上げて対象サーバーでpullとかも考えたんですが、IDEで開発してエディタでデバッグ修正して、とやると管理が非常に面倒な事になるので、これはやりたくなかった。

## 直接ファイルを渡してみる
まずはWindowsのエクスプローラーでもcmdでもいいが、winrootを検索してみよう。
すると以下がヒット。
C:\Users\(Your name)\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_(なんかいろいろ)\LocalState\rootfs\

この辺りはバージョンとかが影響するのかな？
細かい事はよくわかってないですが、どうやらここがルートカレントっぽい。
試しにエクスプローラーからファイルを作ってlsしてみる。

が、出てこない…。
では、逆にUbuntu側でtouchしてみる。

出た！

なんでだ？と思ったんですが、Windowsで新規作成したファイルをUbuntuがさわると大変な事になるらしいので、対策としてそうなっているんだろう、というところで納得。
細かい話がよく分からなかったので、今はそう理解しているが人に説明できない…。

## 暫定対応
/mnt/(ドライブ）/...にシンボリックリンク張るのが楽かなと。
SCPで渡したり2窓を開いてgitを叩かなくても良くなったのはある意味ありがたい。
あとは運用の問題だけど、間違ってもエディタを開いて編集とかやらない。やってもIDE側のソースを優先する。
結局本質的な問題は解決出来ていないけど、窓を減らせたのは大きい。

# 開発用で使えるWebサーバーを作る
これは簡単。
apache2をインストールして/etc/init.d/apache2 startとするとhttp://localhost:80で接続できる。

``` shell:commands
sudo apt install -t apache2
sudo /etc/init.d/apache2 start
```

## 検証
sshでつなげるかやってみた。
まずはUbuntuをservice ssh startで接続できるようにする。
で、他の端末から従来通りsshコマンドで……**入れない**。

起動時にキーが見つからないと言われたのでこの辺りが関係ありそうだ。
パス認証ではcmdベースでは入れたっぽい。lsもpwdも使えないけどdirが使えたので変な笑いが出た。
Windows-Windowsなのでリモートデスクトップをすればcmdを使う以上に色々出来るけど、窓を減らすためにもう一工夫が必要と思われる。
出来そうな気はするけど、そこまで頑張らなくてもいいや、と思ったので今回は断念。

# テスト・デバッグで使えるAPIサーバーを構築する
APIサーバーと言えばSinatraのイメージが強い。が、RubyとかchefはまぁいいとしてRuby on Railsに抵抗値がすさまじく高い私としてはなるべく避けたい、という思いがあった。
そこで、Json-server（nodejs）を使ってみたところ、とても簡単に入った。

``` shell:commands
sudo apt install -y npm
sudo npm install -y json-server
```
私がこれをやった時は先にnodejsを入れてしまったので、このままだとnodeが見つからないと怒られるかもしれない。
そんな時は、/usr/binのnodejsへシンボリックリンクを張って対応する。

# MySQLを入れてMysql Workbenchをもっと快適にする
これも簡単

``` shell:commands
sudo apt install -y mysql-server
sudo /etc/init.d/mysql start
```
mysqlのrootユーザー/パスワードをサクッと入れればOK。慣れない人は一瞬ビビる。
あとはSQLを持っていくなりすれば環境が作れる。

# Dockerを入れて環境を壊しやすくする
最初に結論を書くが、Dockerは入るけどデーモンが動かないので本当にやりたい事は出来なかった。
詳細は参考欄を参照のこと。
とりあえずVargrantとかVirtualBoxとかはあるので困りはしないけど残念感もある。

# ちょっとメモ
MySQLとかはインストールにめちゃくちゃ時間が掛かったので、環境構築は余裕がある時か、可能なら夜に回して帰るとかした方がいいです。

## git
入ってた。2.7.4。アップデートしよう。

## python
入ってた。2.7.12。アップデートしよう。

## cron
去年ぐらいに<a href="https://qiita.com/nomurasan/items/dba72d1ec1d194b74a33">Windowsでcronみたいな事をやらせる</a>って記事を書いたんですが、Windows Subsystem for Linuxだとそんな事しなくても普通にcronが使えます。

# 参考
敬称略

テスト用REST-APIサーバーをコマンド一発で！「json-server」（cup!OF）
http://co.bsnws.net/article/239

Sinatra入門(@kimioka0)
https://qiita.com/kimioka0/items/751e460cbb59c70379c6

BashOnUbuntuOnWindowsでMySQLを起動させる。(@akahirout2641)
https://qiita.com/akahirout2641/items/047a0f01a051691637dc

WSL(Bash on Windows)でDockerを使用する（@yoichiwo7）
https://qiita.com/yoichiwo7/items/0b2aaa3a8c26ce8e87fe

すごく勉強になったので紹介。
WebAPIについての説明（@busyoumono99）
https://qiita.com/busyoumono99/items/9b5ffd35dd521bafce47

記事書いてから知った…。
【ubuntu-make】 Ubuntuでいろいろな開発環境をらくらく構築(@ygkn)
https://qiita.com/ygkn/items/0f5d7a7778c7b06220f5

開発環境の構築ではないが、あると便利なもの。
作業がグッと楽になる screen を使おう！（bacchi.me）
https://bacchi.me/linux/how-2-use-screen/
