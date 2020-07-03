[公開先](https://qiita.com/nomurasan/items/a4291f5a18f3b6cc1525)

ようやく出来た記事です。
いやぁ、長かった……！

# Windows(10 pro)でGitlabを運用したいのでVagrant+VirtualBoxで環境を作って運用できそうな話
→まだやってないので、これからっぽいタイトルにしておきます。
→<a href="https://qiita.com/nomurasan/items/5671326dc3e16f8b7890">結局うまくいかなかったので、Hyper-Vで作り直しました。</a>

なお、よく忘れるので先に書いておきますが、gitlabの初期ログインパスは、

* root
* 5iveL!fe

です。
ログイン後に変更しろと言われるので、その時にパスワードを変更します。

# 実施環境
Windows: 10 Pro
Vagrant: 2.0.2　（インストール時点）
VirtualBox: 5.2.8-121009-Win

書く必要はないんですが、本環境は64bitです。
gitとかはvagrant boxの方で入っているものと思ってたんですが、インストール直後は見つからなかったです。

# 事前準備
Vagrantインストール
https://weblabo.oscasierra.net/install-vagrant-onto-windows/

VirtualBoxインストール
https://eng-entrance.com/virtualbox-install
読み飛ばし項目は未実施

前の記事とかでDocker入れたりHyper-Vが動いてたりしてるので、こいつが障害になったため、後で止めてます。
その前提で以下を読み進めてください。

# 手順
大体は<a href="http://growsic.com/blog/vagrantubuntu1404gitlab/">こちら</a>の手順です。
実行時はpowershellで行います。

``` powershell.sh
mkdir (vagrant_directory)
cd (vagrant_directory)
vagrant box add ubuntu1404s https://oss-binaries.phusionpassenger.com/vagrant/boxes/latest/ubuntu-14.04-amd64-vbox.box
vagrant init ubuntu1404s
vagrant up
vagrant ssh
# ここでコンソールの表記が vagrant@ubuntu-14:~$ に変わる事でログインができたことを確認できる
# 以下、ログイン後を想定。普通のubuntuの設定
sudo apt-get install openssh-server
sudo apt-get install postfix
wget https://downloads-packages.s3.amazonaws.com/ubuntu-14.04/gitlab_7.9.2-omnibus-1_amd64.deb
sudo dpkg -i gitlab_7.9.2-omnibus-1_amd64.deb
sudo gitlab-ctl reconfigure
```

後で知ったんですが、vagrant upの前にvagrantfileを編集しておいた方が良いです。
私がやったのは
``` # config.vm.network "private_network", ip: "192.168.33.10" ```
のコメントを外しました。

``` powershell.shの続き
exit
# ここでコンソールの表記がpowershell従来のものに戻る
vagrant reload
```
この時に、WindowsのVirtualBoxを実行しようとしています。
うまくいかなかったのはこの辺りにも理由がありそうです……

もしかすると、追加の手順が必要かもしれませんが、私の環境ではこれだけでできました。
あとは、<a href="http://192.168.33.10">http://192.168.33.10</a>にブラウザでアクセスすればログインページになっていました。
もちろん、通常通りログインできましたが、場合によっては追加で調査が必要かもしれません。
私の環境ではそのままWelcome to GitLab!まで出来たので、とりあえず環境構築はここまでとします。
また問題があれば別記事で起こします。

# 参考
Docker for Windowsを使うためにHyper-Vを入れてたり、Vagrantfileを編集する必要はあるので、以下も合わせて参考のこと
http://growsic.com/blog/vagrantubuntu1404gitlab/

vagrant upコマンドで失敗する場合
http://eiua-memo.tumblr.com/post/143625719906/vagrantwindows10にアップグレード後vt-x-is-not

ipアドレスにアクセスできない場合
http://to-developer.com/blog/?p=1827

今回うまくいかなかった方法
http://semper-fi.hatenablog.com/entry/2017/04/05/122446
→vagrant box addしている https://atlas.hashicorp.com/webysther/boxes/gitlab-ce-ubuntu-x64-14.04/versions/1.0/providers/virtualbox.box が見つからない。ただし http://www.vagrantbox.es には居る。
　上記リンク先で404エラーになっているので、このURLは使えない。

# 過去記事
<a href="https://qiita.com/nomurasan/items/a2cdaa55aa00fd44e29e">Windows(10 pro)でGitlabを運用したいのでDocker for Windowsで環境を作ってみたけど運用できなかった話</a>
<a href="https://qiita.com/nomurasan/items/b725c9ee9179bcac2b22">Windows(10 pro)でGitlabを運用したいのでBash on Ubuntu on Windowsで環境を作ってみたけど運用できなかった話</a>

## 事の発端
<a href="https://qiita.com/nomurasan/items/5197100a1ae3e5a30f4c">レベル０のDockerプレイヤーが可能な限りシンプルな状態から勉強したい時の話</a>

# 注釈
