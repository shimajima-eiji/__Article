[公開先](https://qiita.com/nomurasan/items/b725c9ee9179bcac2b22)

<a href="">似たようなタイトルの記事</a>[^1]を書いてますが、今回はアプローチを変えてチャレンジしました。
今度はDocker for WindowsではなくてBash on Ubuntu on Windowsです。要は「既にGitlabがサポートする[^2]ディストリビューションがあるんだからそれを使おう」

[^1]: 【同リンク有】<a href="">似たようなタイトルの記事：Windows(10 pro)でGitlabを運用したいのでDocker for Windowsで環境を作ってみたけど運用できなかった話</a>
[^2]: Gitlabがサポートするディストリビューション：厳密に言うと純正のUbuntuではないので対象外だと思います。

# Windows(10 pro)でGitlabを運用したいのでBash on Ubuntu on Windowsで環境を作ってみた
結論からいうと、なんか上手くいってるっぽいんですがipからのログインが出来ませんでした。

``` commands.sh
sudo apt-get install curl openssh-server ca-certificates postfix
curl -s https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | sudo bash
sudo apt-get install gitlab-ce
sudo gitlab-ctl reconfigure
```

なんか出来そうな気がするんですが……

# 参考
https://about.gitlab.com/installation/#ubuntu

# 類似記事
<a href="https://qiita.com/nomurasan/items/a4291f5a18f3b6cc1525">Windows(10 pro)でGitlabを運用したいのでVagrant+VirtualBoxで環境を作って運用できた話</a>
<a href="https://qiita.com/nomurasan/items/a2cdaa55aa00fd44e29e">Windows(10 pro)でGitlabを運用したいのでDocker for Windowsで環境を作ってみたけど運用できなかった話</a>
【ココ】Windows(10 pro)でGitlabを運用したいのでBash on Ubuntu on Windowsで環境を作ってみたけど運用できなかった話

# 注釈
