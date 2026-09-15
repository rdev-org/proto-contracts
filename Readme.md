Generate User Proto

```bash
protoc -I=./proto --go_out=./pb/user --go_opt=paths=source_relative --go-grpc_out=./pb/user --go-grpc_opt=paths=source_relative proto/user.proto
```

Generate User Address Proto

```bash
protoc -I=./proto --go_out=./pb/user_address --go_opt=paths=source_relative --go-grpc_out=./pb/user_address --go-grpc_opt=paths=source_relative proto/user_address.proto
```
