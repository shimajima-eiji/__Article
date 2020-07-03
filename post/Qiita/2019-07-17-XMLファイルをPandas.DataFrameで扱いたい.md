[公開先](https://qiita.com/nomurasan/items/78d0174977bb61a52808)

# XMLファイルをPandas.DataFrameで扱いたい
pandasはcsvやjsonを扱う時は便利ですが、xmlは対応してくれていないのか、良い方法が思いつきませんでした。
xmlをdictやjsonに変えたりすることも考えたんですが、ネストされたxmlを扱うと途端に敷居が高まります。
これは変換する時に文字列にされてしまうために、シングルクォーテーションをダブルクォーテーションに置き換えたり、意味のあるオブジェクトであることを維持し続けなければならない等の制約があるため、だと理解しました。
→【要出典】

# 結論
[やりたいことは全部ここにあった](https://gist.github.com/mattmc3/712f280ec81044ec7bd12a6dda560787)んですが、ここの通りxmlをアレコレやって直接dataframeに置き換えるのが一番いいのかなぁ、と思ってます。
私が活用した時のコードは以下のとおりです。
執筆時点の最新版と同じものです。

``` xml2df.py
import xml.etree.ElementTree as ET
import pandas as pd

def xml2df(xml_data):
    root = ET.XML(xml_data) # element tree
    all_records = []
    for i, child in enumerate(root):
        record = {}
        for subchild in child:
            record[subchild.tag] = subchild.text
        all_records.append(record)
    df = pd.DataFrame(all_records)
    return df

# load XML to dataframe (gotta be small)
xml_data = open('sample.xml').read()
df = xml2df(xml_data)
print(df)
```

色々なところで扱ってるサンプルコード程度なら意図した結果が得られると思います。

# 参考
私が使ったxmlと結果も載せておきます。
テストケースとしては優秀ではないですが、やりたいことは実現できました。

``` sample.xml
<?xml version="1.0" encoding="UTF-8" ?>
<sports>
  <sport>
    <name>サッカー</name>
    <orgin>イングランド</orgin>
  </sport>
  <sport>
    <name>野球</name>
    <orgin>アメリカ</orgin>
  </sport>
</sports>
```

``` 
# result
   name   orgin
0  サッカー  イングランド
1    野球    アメリカ
```

# 注意・懸念
root(sports)や親情報(sport)がなくなっているので、親ノードが複数存在する場合は予期せぬ結果になる可能性があります。
親情報も保持したい場合はdataframeではなくpanelで持つか、df_dictなどで持つ方が良いと思います。

が、どちらにしても親情報が破棄されてしまっているため、このコードはそのまま使えない気がします。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。
