[公開先](https://qiita.com/nomurasan/items/5671326dc3e16f8b7890)

<a href="https://qiita.com/nomurasan/items/a4291f5a18f3b6cc1525">WindowsでもGitlabを使いたい！</a>という記事を書いたんですが、結局使えなかったのでより欲望に忠実なタイトルに変えて書き直します。
事実上、やり直しです。

# Windows(10 pro)でGitlabを運用したいのでHyper-Vで環境を作って運用している話
**今まさに運用している話**です。
出来そうな話は卒業しました。

# Hyper-Vで環境を作る
<a href="https://qiita.com/nomurasan/items/3c58b964943a24751802">Hyper-Vで構築した環境でインターネット接続が出来るようにする</a>方法を記事に書いていますので、この辺りのをサクッとやっちゃってください。

# gitlabをインストールする
私はUbuntuでやってますので、Ubuntuで説明しますが、CentOSでもできると思います。
https://about.gitlab.com/installation/#ubuntu

この手順でやると、他でイメージをもらった時の最新版(7.9など）ではなく、きちんと最新版[^1]でした。
ただ、以下は気を付けてください。

``` Install.sh
curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | sudo bash
sudo EXTERNAL_URL="http://（ブラウザでアクセスするためのURL。IPでも可）" apt-get install gitlab-ce
```
変更点は、gitlab-**ee**ではなくgitlab-**ce**です。
気付かずにうっかりやらかしました。

# gitlabを起動する
インストールしただけでは起動できてないかもしれません。

```
sudo gitlab-ctl reconfigure
sudo gitlab-ctl restart
```

を実施しておくといいかもしれません。

# gitlabにログインする
7.9とは画面が異なります。
パスワードを設定するところから始めるみたいです。
ここで設定するユーザーは「root」です。
パッと見分からないので気を付けて。

# gitlab10を日本語化する
ログイン後、画面右上のアバターからSetting、
画面を開いたらPreferred languageのプルダウンを「日本語」とします。
ほとんど英語のままですが、メインで使うプロジェクトの画面では日本語になっています。

## ちょっとぐっちーな
こんな形で日本語になる前はもっと大変でした。
詳しくはgitlab 日本語あたりで眺めてほしいんですが、こういう裏側があって今のような形に落ち着いているんだなぁ、というのが見えると現状の翻訳だけでもだいぶ使いやすくなっている方です。

# gitlabからgit cloneしてみる
gitlabの使い方は省略します。githubと似たようなものなので、日本語にもなってるし何となくフィーリングで。

私はTortoiseGitで実施していますが、Git for Windowsとかでもできます。
git clone時にユーザーアカウントとパスワードを求められますが、gitlabの設定をしたものを使うとcloneできます。
URLは各プロジェクトに依存します。その辺りはgithubと同じです。
TortoiseGitユーザーはhttpを使います。

# git pushしてみる
cloneしたらpushしましょう。
そこまで確認できれば大丈夫です。

# Windowsを再起動して使えるか確認してみる
同じことをやってみます。
ここまで確認できたら運用できるレベルではないでしょうか。

# 注釈
[^1]: 執筆時点では10.5.3です。タイトルの通り。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
