[公開先](https://qiita.com/nomurasan/items/7c170163c7c9f1d19516)

こんなマニアックな使い方をする人がいるか分からないけど、備忘録

``` expansion.py
from pathlib import Path

path = Path('任意のパス')
dirname = path.parent  #フルパスが欲しい場合はpath.resolve().parentでも取れる
filename = path.stem  #拡張子を除いたファイル名を取得

Path(dirname) / '{}.ext'.format(filename)  #.extはいい感じに
```

説明用にdirnameやfilenameにPathを使っているけど、実際はstrを想定。
こんな面倒な事をしなくてもいいはずなんだけど、方法が見つからなかった。

# 参考
<a href="https://docs.python.jp/3/library/pathlib.html">pathlib — オブジェクト指向のファイルシステムパス(Python.org)</a>

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
