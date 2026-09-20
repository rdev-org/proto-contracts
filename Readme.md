Generate Meta Proto

```bash
protoc -I=./proto --go_out=./pb --go_opt=paths=source_relative --go-grpc_out=./pb --go-grpc_opt=paths=source_relative proto/common/meta.proto
```

Generate Filter Proto

```bash
protoc -I=./proto --go_out=./pb --go_opt=paths=source_relative --go-grpc_out=./pb --go-grpc_opt=paths=source_relative proto/common/filter.proto
```

Generate Filter Proto

```bash
protoc -I=./proto --go_out=./pb --go_opt=paths=source_relative --go-grpc_out=./pb --go-grpc_opt=paths=source_relative proto/common/pagination.proto
```

Generate User proto

```bash
protoc -I=./proto --go_out=./pb --go_opt=paths=source_relative --go-grpc_out=./pb --go-grpc_opt=paths=source_relative proto/user/*.proto
```

Generate Auth Proto

```bash
protoc -I=./proto --go_out=./pb --go_opt=paths=source_relative --go-grpc_out=./pb --go-grpc_opt=paths=source_relative proto/auth/*.proto
```

Generate Notification Email Proto

```bash
protoc -I=./proto --go_out=./pb --go_opt=paths=source_relative --go-grpc_out=./pb --go-grpc_opt=paths=source_relative proto/notification/*.proto
```
