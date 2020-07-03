[公開先](https://qiita.com/nomurasan/items/ab1f3c7062f9ef6d588f)

# [map,filterなど高階関数がよく分からない場合]listの中にlistを持っていた時にmap関数を使いたい

なんてことはないんだけど、解説してるサイトが見つからなかったので、後で困った時のためにメモ。

``` list_in_list.py
list_in_list = [
  ['1A','1B','1C'],
  ['2A','2B'],
  ['3A','3B','3C','4D']
]

list(
  map(
    print, list_in_list
  )
)
#['1A','1B','1C']
#['2A','2B']
#['3A','3B','3C','4D']

list(map(lambda lists:list(map(print, lists)) , list_in_list))
#1A
#1B
#1C
#2A
#2B
#3A
#3B
#3C
#4D
```

リストの外の括弧[]に対してlist(map())でループを回しているイメージ。

## 発展

ただし、

``` list_in_list.py
list_in_list = [['first',['1A','1B','1C']],['second',['2A','2B']],['third',['3A','3B','3C','4D']]]

list(map(lambda lists:list(map(print, lists)) , list_in_list))

#first
#['1A','1B','1C']

#second
#['2A','2B']

#third
#['3A','3B','3C','4D']
```

のようなデータを扱うと、以下の場合おかしくなる。

``` list_in_list.py
list(map(lambda lists:list(map(lambda list2:list(map(print, list2)), lists)) , list_in_list))
#f
#i
#r
#s
#t
#1A
#1B
#1C
#s
#e
#c
#o
#n
#d
#2A
#2B
#t
#h
#i
#r
#d
#3A
#3B
#3C
#4D
```

これは、stringに'first'を入れてstring[0]、string[1]...のように取り出すような振る舞いがされている。
そのためエラーにならないが、期待値と異なる事がある。

## 解決
これを防ぎたい場合、たとえば今回の場合は以下のような書き方で逃げられる。

``` list_in_list.py
list(map(lambda lists:list(map(print, lists[1])) , list_in_list))
#1A
#1B
#1C
#2A
#2B
#3A
#3B
#3C
#4D
```

lists[0]のfirst, second, thirdを取りたい場合は、

``` list_in_list.py
list(map(lambda string: print(x[0]), list_in_list))

#first
#second
#third
```

で取れる。
落ち着いて一つずつ読み解けば難しい事ではないんだけど、勘違いしやすいので注意。
よく分からなくなった場合、list(map(..., list_in_list))をfor文に書き直してみると気付きやすいかも。

## 2018/04/09 解決追記
itertools.chainを使うともう少しスマートになる。

``` answer_comment.py
from itertools import chain

list_in_list = [['first', ['1A', '1B', '1C']], 'second', ['second',['2A', '2B']], ['third', [['3A', '3B', '3C', '4D']]]]
list(
    map(print, list_in_list )
)
```

# python2.x系の場合
printで説明しているのでprintについて言及するが、python2では上記をそのまま使えない。
そのため、以下のような関数を用意する。

``` python2.py
def my_print(message):
    print message
```
これでとりあえず使える。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
