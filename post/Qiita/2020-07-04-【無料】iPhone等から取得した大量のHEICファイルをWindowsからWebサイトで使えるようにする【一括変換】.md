[公開先](https://qiita.com/nomurasan/items/c929f69c9bda9541f3c0)

# 【無料】iPhone等から取得した大量のHEICファイルをWindowsのローカル環境からWebサイトで使えるようにする【一括変換】
タイトルで一番言いたいのは「無料」と「大量」と「一括変換」、たかだかこれだけのために課金しろと言われたのでカッとなって作った。

# 謝辞
WSL+Shellを使っているので純粋にWindowsか？と言われるとツラい…。
PowerShellでもできるとは思うが、ここでは紹介しない（私が分からない）。

## 前提：少数で個人ならWebサービスがおすすめ
探せば結構便利なのがいっぱいあります。
いくつか見たところ、日本語サイトより海外サイトの方が利便性が高い気がします。

## 公開中のサービスのいろいろと惜しいポイント
- 一括変換できるがダウンロードは一つずつ
- 変換後のファイルのど真ん中に独自のロゴ（無料プラン）を入れてくる
- 無料プランだと変換できるファイル数が100件以下

部分的には問題ないのに、致命的な欠点が一つあるせいで使えない、となってしまう。
（尤も、それがウリなんだろう）

## 解決案
[imagemagick](https://imagemagick.org/)を使えばheicファイルを変換できる。
実行するだけなら`magick *.heic -set filename:x "%t" "%[filename:x].jpg"`が手っ取り早い。
実はこれだけでも複数ファイルを変換することは可能だが、20GB/3000ファイルで検証したところ、うんともすんとも言わなくなったので、この方法は採用しなかった。

なので、特定のディレクトリ以下にfindを掛けてxargsなりで一つずつ処理をさせる方法が良さそうだ。

### 実行例
``` heic2jpg.bsh
#!/bin/bash
# 変更をユーザー側の設定に合わせて適宜変更する
processor=1
dir_path="./"
export expansion_input='HEIC'
export expansion_output='jpg'
export magick_path='magick'  # magickのパスを再設定できる。WSLならmagick.exeか

# 以下は高度な変更不可
function execute {
  input=$1
  output="${input%.$expansion_input}.${expansion_output}"
  echo "Run [${input}]"

  if [ -e "${output}" ] ;then
    echo "Skip"

  else
    ${magick_path} ${input} ${output} && echo "Complete!" # && rm ${input}  # 変換後削除する場合は、&&の前の#のコメントアウトを外す
  fi
}
export -f execute

find $dir_path -type f -name "*.${expansion_input}" | xargs -P ${processor} -I@ bash -c 'execute "@"'
```
[Github](https://github.com/shimajima-eiji/Chocolatey/blob/master/tool/heic2jpg.bsh)

# 参考
- [Windows10で画像を一括処理したいときに便利なコマンドラインツール（ImageMagick）](https://4thsight.xyz/8342)
- 備考：[「さようなら ImageMagick」の考察](https://qiita.com/yoya/items/2076c1f5137d4041e3aa)

重要なのは備考部分で、色々と不安定な状態のものをメンテすると大変だからサービスとして公開する以上は無料ではなく有償としているのだろう、という事が窺えるのでお金取るな！という話をするつもりはない。
ただし、一般利用者（特に非プログラマー）としてはそこまで神経質にならず、とりあえず使えるものがあればそれで良いので、そういったニーズに応えても良いのでは？と思う。

# ボツ案
最初は使い慣れているpythonでやろうとしたところ、日本語文字や特殊文字にメチャクチャ弱かったので諦めた…。

```
import sys, subprocess
from pathlib import Path

print(len(sys.argv))
if len(sys.argv) < 2:
  print('[Require] 引数にファイルパスが必要です')
  exit()

input_file=Path(sys.argv[1])

if not input_file.exists():
  exit()

output_file=Path(input_file.stem + ".jpg")
if output_file.exists():
  print('Skip ' + input_file.name)
  exit()

subprocess.run(["magick.exe", '\"' + input_file.name + '\"', '\"' + output_file.name + '\"'])
print("Complete %s -> %s" % (input_file, output_file))
```
