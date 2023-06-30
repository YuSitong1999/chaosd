# Swagger 文档生成方式

Windows 下执行以下命令。

```shell
go get github.com/swaggo/swag/gen@v1.8.3

go get github.com/swaggo/swag/cmd/swag@v1.8.3

go install github.com/swaggo/swag/cmd/swag

swag init -g cmd/main.go
```

生成的文档在 `docs` 目录下。
