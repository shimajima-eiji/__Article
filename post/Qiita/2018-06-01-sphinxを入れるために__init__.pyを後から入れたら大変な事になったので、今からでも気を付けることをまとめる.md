[公開先](https://qiita.com/nomurasan/items/11042943f918fdd5a37c)

基礎的な話ばかりだけど、「こういう場合ってどうなんだっけ？」って頻繁に悩んでgoogle先生に教えを乞うので、この機会にきちんと整理！
コーディング規約から保守から、雑ながら包括的に。

ちょっとだけsphinxの導入とか、パッケージを意識したモジュールづくりの話とかもします。

# sphinxを入れるために\_\_init\_\_.pyを後から入れたら大変な事になったので、今からでも気を付けることをまとめる
# ファイル構成
今回の環境はこういう形で作ってます。

``` tree.
(root)
├── README.md
├── run.py
├── app
│   ├── __init__.py
│   ├── main.py
│   ├── libs
│   │   ├── __init__.py
│   │   ├── modules.py
│   │   ... py
│   └── src
│       ├── __init__.py
│       ├── modules.py
│       ... py
└── sphinx
    ├── Makefile
    ├── conf.py
    ├── make.bat
    ... rst
```

元々は\_\_init\_\_.pyなんてなかったし、appとかsphinxとかのディレクトリも後付けです。
出力先の階層が一段深まってしまったので、パスもそれぞれ書き直すことになってしまいました。
**実装に着手する前に変更に強い仕組みを考えておくのは非常に重要な事だと改めて思いました。**

## \_\_init\_\_.pyについて補足
なにかモジュールが呼ばれた場合（たとえばapp/main.py）、同階層の\_\_init\_\_.py（app/\_\_init\_\_.py）が実行するより先に呼ばれるため、
後述のapp/src/modules.pyの from ..libs import modulesも１：app/\_\_init\_\_.pyを通って２：app/libs/\_\_init\_\_.pyを通ってlibs/modules.pyが実行されます。

これを検証する場合、各ファイルの先頭にprint \_\_file\_\_とすると流れをつかみやすいが、上の通り何度も呼ばれるので、呼ばれた回数を正しく追う方が大事。
つまり、sphinxのビルド時にエラーになると呼ばれた回数だけエラー件数が増えるので、\_\_init\_\_.pyには基本的には何も書かないようにします。

## (current)
ここには\_\_init\_\_.pyを置く必要はありません。
パッケージの外から実行した時のイメージです。

``` run.py
"""
パッケージの外なのでfrom .app import mainとしない
"""

import app.main
```

### (current)/app
sphinx-apidocのソーススクリプトで指定するパッケージ（ディレクトリ）
サブディレクトリ含む以下がドキュメントとして生成される

``` app/main.py
"""
srcのモジュールを参照して何らかの処理をする
"""

from .src import modules
```

#### (current)/app/src
``` app/src/modules.py
"""
ここは普通に書く
main.pyから呼び出されて、libs/modules.pyを呼ぶ
"""

from ..libs import modules
# ～なにかの処理
```

#### (current)/app/libs
``` app/libs/modules.py
"""
ここは普通に書く
src/modules.pyから呼び出される
"""

# ～なにかの処理
```

# ハマりどころ
当たり前だがモジュールはimportされたその瞬間、その場所から当該ファイルが１行ずつ処理されます。
この時、相対的なパスで通ってきた\_\_init\_\_.pyは通るたびに呼ばれるので、夥しい量のエラーメッセージを吐き出す可能性が高く、デバッグ時に血反吐を吐くことになります。
当然、\_\_init\_\_.pyに同階層のモジュールをimportして、同階層のモジュールが巡り巡って…なんて無限ループが発生しうる可能性も考えられます。

うっかり忘れがちですが、python3では暗黙的な相対パスでのimportは禁止。
\_\_init\_\_.pyがなくてもimportができるので、本当に忘れがち。
sphinxを入れると必須になるので、この問題も未然に防げます。

sys.path.appendを使う方法も考えられるものの、相対パスが使えるならそちらを選択したいですね。

このあと、WLSで生成したsphinxドキュメントがwindows10の権限回りでハマったのですが、別記事にて。


# 参考
- <a href="https://qiita.com/sukobuto/items/15c1173b3f37f0306dd5">Python におけるモジュールとパッケージは「名前空間」</a>
- <a href="https://www.yoheim.net/blog.php?q=20160612">[Python] コーディング規約(PEP8)を学んで、Pythonらしいコードを書く</a>
- <a href="http://d.hatena.ne.jp/chlere/20110618/1308369842">Pythonでディレクトリの上層にあるモジュールをimportするときの注意点</a>
- <a href="https://qiita.com/ysk24ok/items/2711295d83218c699276">[Python] importの躓きどころ（筆者註：importの話）</a>

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
