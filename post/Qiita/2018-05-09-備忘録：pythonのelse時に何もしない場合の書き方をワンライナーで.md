[](https://qiita.com/nomurasan/items/b1a59a78ddb1b21f172a)

気付いたらそれだけなんですが、気付くまでに時間が掛かるやつです。
探しても見つからなかったので備忘録。

# やりたいこと
``` Ternary_operator.py
def practice(message = None):
  if message is None:
    message = 'no message'
  print(message)
```

messageがあればそれを、なければno messageと表示させたい。
この書き方を一行でスマートにできればいいよね＾＾というのが事の発端。

# 調べたら見つかりやすかったケース（三項演算子を使う）
``` Ternary_operator.py
def practice(message = None):
  message = 'no message' if message is None else message
  print(message)
```

確かにこれで良いんですが、elseは何もしないので書きたくない。

# こうすれば良かった
``` Ternary_operator.py
def practice(message = None):
  if message is None: message = 'no message'
  print(message)
```

三項演算子を使う、というところにとらわれすぎてて、基本的な使い方を忘れていました。
if～: の後に改行をしなければ良いだけなのですが、なぜか思い当たるまでに時間が掛かってしまった……。

# （私がよくやる）実運用ケース
``` Ternary_operator.py
class hoge(object):
  message = 'no message'  #実際はこのmessageを__init__なりで色々変更しています。

  def practice(message = None):
    if message is None: message = self.message
    ～なにかしらの処理～
```

これで少しはムダなコードが減りますね。
ちなみに、if～: 【ここ】は代入以外も当然書けますので、実際に活用する場合はその方がいいです。
lambdaと組み合わせるとすごい効果を発揮します。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
