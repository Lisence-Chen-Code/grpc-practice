###### 生成pb文件

```
protoc --go_out=. helloworld.proto
```

###### 生成rpcpb文件

```
protoc --go-grpc_out=. helloworld.proto
```

###### 运行

```
go run server/main.go
go run client/main.go
```


