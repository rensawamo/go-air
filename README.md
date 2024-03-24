## フォルダ構成
.
├── Dockerfile
├── .air.toml
├── docker-compose.yaml
├── go.mod
├── go.sum
├── main.go

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
