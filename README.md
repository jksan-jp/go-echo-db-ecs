# go-echo-db-ecs

### install
```
go get github.com/labstack/echo/v4
```


### build
```
docker build -t go-echo-db-ecs . 

```

### hadolint
> [リファクタリングしながら学ぶGoのDockerfileベストプラクティス](https://zenn.dev/mitsu5/articles/b1acc3a8e47bd6#%EF%BC%91.%E9%9D%99%E7%9A%84%E8%A7%A3%E6%9E%90%E3%83%84%E3%83%BC%E3%83%AB%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E3%81%BF%E3%82%8B)

```
$ hadolint ./Dockerfile
```