[公開先](https://qiita.com/nomurasan/items/1e54601a980832a2eb0a)

今はpythonを使っているのでいいんだけど、いずれ古巣に戻るつもりなので、そこからまたpythonに戻ってきたら確実に忘れてるだろうな、と思うことを備忘録にしています。

# printが式でなくて文になると何がうれしいか？
<a href="http://d.hatena.ne.jp/hekyou/20111224/p1">探せばこのように、小難しい話とかはいっぱいある</a>んですが、**実感として自分に降りてきてない**ので自分どうなんよ？という話にフォーカスします。
**正確性のある、かつ体系的な情報を求めている方にとっては有益な情報は提供できていない**[^1]かもしれません…
[^1]: 【有益な情報が提供できない理由】アーキテクチャーの話も理解しようとしたのですが、私の中でうまく理解しきれていません…

## 大前提
以下のように書くとpython2系でも式っぽくなります。

``` user_print.py
lambda message:print message

# 上記は以下と同義
import six
def message(message):
  if six.PY2:
    print message
  elif six.PY3:
    print message
```

なので、python2でもprintを式っぽく書くこと自体は可能です。
厳密に言うと上記サイトの通り、上記のようなオレオレ関数は小回りは利かないのでpython3のprint式とは違うのですが…
私が使ってきた範囲ではあんまり関係ないので、本記事では同じものとして扱います。

## 実践
高階関数を使うのが分かりやすいと思います。

``` practice.py
from user_print import user_print

str_list = [
  'test1',
  'test2',
  ]

list(map(print, str_list))  # python3
list(map(lambda string:print(string), str_list))  # python3

list(map(message, str_list))  # python2
list(map(lambda string:message(string), str_list))  # python2

# forで書く
for string in str_list:
  message(string)  # if six.PY3: print(string)

```

別にfor文に何か思うところがあるわけではないんですが、たとえば上記のようにする場合。
mapとかで引数が一つのケースでlambda式を書くメリットはほとんどないと思ってますが、帰ってきた時に忘れてそうなので書いておきます。

### 脱線メモ
以下のようなケースではlambda式を使う必要があります。

``` class.py
class user_print(object):
  def __init__(self, string):
    self.string = string
  def main(self):
    print(self.string)

list(map(lambda string:user_print(string).main(), str_list))
```
list(map(user_print, str_list))
とか
list(map(user_print.main(), str_list))
は期待する結果を得られませんが、エラーにもなりません（？）

## 要望、というか希望
上記でも書いてますが、printとmessageは同じものなので深く考えなくていい[^2]んですが、message関数のようにバージョンに対応出来た方が比較的親切かな、と思うシーンが多かったです。
本来はpy2とpy3のパーサがあればいいんでしょうが[^3]、探すより作ったほうが楽だったのでそうしてます。
個人の環境でgitサーバーなりを立ててライブラリをまとめたプロジェクトを置いておくだけでも相当捗ります。

[^2]: 【printとユーザー関数messageが同じ】大事な事なので何度も言いますが、本記事のような使い方に限定しています。
[^3]: 【py2-py3のパーサ】例えば今回でいうところのprint文・式をいい感じにするものとかはありそうな気はしますよね。configparserとConfigparserみたいなのとか、socketのsettimeoutとか、探せば色々見つかります。

# 念のために
- python2.7.12
- python3.6.4

で検証しています。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
