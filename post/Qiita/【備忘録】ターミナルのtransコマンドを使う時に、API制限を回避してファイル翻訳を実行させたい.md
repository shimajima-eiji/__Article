[公開先](https://qiita.com/nomurasan/items/aebead4856e02cbd9fd3)

# 【備忘録】ターミナルのtransコマンドを使う時に、API制限を回避してファイル翻訳を実行させたい
[Translate-shellを無限に動かして遊ぶ#API制限の回避](https://qiita.com/eggplants/items/f3de713add0bb4f0548f#api制限の回避)のコマンドを都度都度打ち込んだり、transコマンドをいじるのに抵抗があったので、ファイル化しようとして躓いたところなど。
知ってるかどうかの違いだけど、まとまった情報はなかった。

<details><summary>前提：transコマンドのインストール</summary><div>

transコマンドのインストール自体は[本家](https://www.soimort.org/translate-shell/#installation)の通り。
環境により方法が異なるため、ここでは解説できない。

私の環境（WSL:Ubuntu）だと`#3. From Git`の手順でインストールしている。

``` Terminal.
git clone https://github.com/soimort/translate-shell
cd translate-shell/
make
[sudo] make install
```

参考程度に。

</div></details>

# 実行ファイル（Bash）
``` trans_file.bsh
#!/bin/bash
if [ -z "$BASH_VERSION" ] || [ "${BASH##*/}" != "bash" ]; then
  echo "$0: RETURN: Use bash" >&2
  exit 1
fi

input='出力元のファイル'
output='出力先のファイル'
echo >${output}
while read line; do
  # 英語のファイルを日本語に翻訳したい場合
  echo $line | trans en:ja -b -no-autocorrect | tee -a ${output}
  sleep $[RANDOM%5+5]  # 【※】
done <${input}
```

## ※補足
Bashである必要があるのは`$[RANDOM%5+5]`の部分。
shで書き換えられるならbashである必要はない。

# 参考
- [Translate-shellを無限に動かして遊ぶ](https://qiita.com/eggplants/items/f3de713add0bb4f0548f#api制限の回避)
- [detect bash（bashから実行されているかどうかの判定）](https://qiita.com/ma2saka/items/f975fff5af6d48255e0a)
- [Qiitaでいつも調べちゃうマークダウン（表、折りたたみ）](https://qiita.com/tea4/items/5b430c0ed3da3372166c)
  - 本記事内の折りたたみの書き方

<details><summary>ご協力のお願い</summary><div>
読みやすく、疲れない記事にする努力をしているのですが、Qiitaで表示数(View)は分かっても読了を知る方法がないので、
読了された方はLGTMを押してもらえると「この記事は最後まで読んでもらえたんだな」と判別できて助かります。
お手数をおかけします。
</div></details>
