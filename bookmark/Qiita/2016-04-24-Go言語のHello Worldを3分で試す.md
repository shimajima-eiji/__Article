# Go言語のHello Worldを3分で試す
[元記事](https://qiita.com/techys/items/44a712a76859fe0a9dea)

やることはこれだけ。
```
echo "
package main

import "fmt"

func main() {
  fmt.Printf("Hello World\n")
}
" >hello.go

go run hello.go
go build hello.go
./hello
```

[paizaCloud(Go)](https://paiza.cloud/containers)なら環境構築すら要らない。
