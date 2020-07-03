[公開先](https://qiita.com/nomurasan/items/7ae15e8dc299ea8ad2c8)

Python2.7でやってます。3系はもっと簡単に出来そう。

# ソースコード

```
from urlparse import urlparse
import urllib

def toGSBL(str_url, character_code)
  scheme, netloc, path, params, query, fragments = urlparse(unicode(str_url, character_code, 'ignore'))

  netloc = netloc.encode('idna')
  path = urllib.quote_plus(path.encode('utf-8'), '')　if len(path) > 0 else '/'
  query = urllib.quote_plus(query.encode('utf-8'), '')　if len(query) > 0 else ''

  return scheme + '://' + netloc + path + query
```

- urlparseして必要なところを細工したらくっつけてるだけです。
- charactor_codeにshift-jisとかutf-8とか入れれば思い思いに使えます。
- pathやqueryなど他にもマルチバイト文字が含まれていることを想定していますが、ここで欲しいのはあくまでnetlocをpunycodeにしたものです。
- 文字コードにもよりますが、日本語・韓国語・中国語で期待した結果が得られたので大体できると思いますが確認していません。

## ハマりポイント
UnicodeDecodeError、UnicodeEncodeErrorにはすっごく悩まされました…
というのも、urlparseをするのに環境の都合上どうしてもstr-unicode変換を強いられるため、その辺りの関係をきちんと理解しておかないとだめでした。
普段文字コードを気にしないで開発しているとこういう細かいところでハマります。

楽にするなら文頭に「# -*- coding: utf-8 -*-」とか書ければいいんですが、今回はそれはナシということでこの形で実現しています。

あと、URLLIBを知らない場合は便利だから見ておいたほうがいいと思います。

# 参考
敬称略
大変助かりました！

Pythonで日本語を含む国際化ドメイン（IDNA）をPunycode変換する（ServersMan@VPS（CentOS）でお気楽サーバー運営 (^^♪　　(忘れっぽいので個人メモ用)）
http://d.hatena.ne.jp/addition/20130327/1364353289

日本語文字列コード問題まとめ　ニホンジンは文字コードにうるさい（PythonMatrixJp for Pythonista!）
http://python.matrix.jp/pages/tips/string/encoding.html

20.16. urlparse — Parse URLs into components（Python 2.7.14 Documentation）
https://docs.python.org/2.7/library/urlparse.html#module-urlparse

urllib.parse.quote関数使用時の注意（@FGtatsuro）
https://qiita.com/FGtatsuro/items/75a4593fec954a32c10c

urllib – ネットワークリソースへのシンプルなインタフェース（PyMOTW）
http://ja.pymotw.com/2/urllib/

pythonで三項演算子のネスト（@u1and0）
https://qiita.com/u1and0/items/e47e3de059e27d4ebd74
