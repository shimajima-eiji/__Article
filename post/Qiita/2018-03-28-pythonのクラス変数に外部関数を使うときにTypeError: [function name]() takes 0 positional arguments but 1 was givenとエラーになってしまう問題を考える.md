[公開先](https://qiita.com/nomurasan/items/f8b749930ed0af16d76c)

# pythonのクラス変数に外部関数を使うときにTypeError: [function name]() takes 0 positional arguments but 1 was givenとエラーになってしまう問題を考える
タイトルが長いですが、言いたい事はそのままです。

## 問題

``` question.py
def outer():
    return 'outer'

class inner():
    function = outer
    def call_outer_function(self):
        print(self.function())

inner().function()
```

これを実施すると、タイトルの通りエラーになります。

## 解決

``` answer.py
def outer():
    return 'outer'

class inner():
    function = lambda self:outer()
    def call_outer_function(self):
        print(self.function())

inner().function()
```

クラス内でメソッドを使う場合、暗示的にselfが渡されます。
selfを捨てることで解決させようという発想です。

### 展開
lambda式で書いているので分かりにくいんですが、要するにこういう事をやってます。


``` answer.py
def outer():
    return 'outer'

class inner():
    def function(self):
        outer()

    def call_outer_function(self):
        print(self.function())

inner().function()
```

こちらはよく見る形だと思います。

## 実例
`def outer(input)`
を作っていて、クラス内から呼び出した時に`if isinstance(input,
 '期待するobject')`をやらなかったせいで、この関数ではエラーにならず通ってしまい、別の場所で問題になった時に追いかけるのにやたらと時間が掛かりました。
可能であれば引数をバリデーションする癖をつけておきましょう。
たったこれだけの事なんですが、えらい目に遭いました。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
