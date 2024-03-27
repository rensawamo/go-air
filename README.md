## insatall
```sh
$ go install github.com/cosmtrek/air@latest
```

## PATH を通す
```sh
$ export PATH=$PATH:$(go env GOPATH)/bin
```

## Golang Air 
https://github.com/cosmtrek/air

## サーバの起動
```sh
$ docker compose up
```

## request 
```sh
$ curl localhost:8080/remon
```

## 結論
docker を使っていても　ホットリロードで再ビルドとAPIの再起動が行われる
