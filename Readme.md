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

Generate User Credentials Proto

```bash
protoc -I=./proto --go_out=./pb/user_credential --go_opt=paths=source_relative --go-grpc_out=./pb/user_credential --go-grpc_opt=paths=source_relative proto/user_credential.proto
```

Generate User Profile Proto

```bash
protoc -I=./proto --go_out=./pb/user_profile --go_opt=paths=source_relative --go-grpc_out=./pb/user_profile --go-grpc_opt=paths=source_relative proto/user_profile.proto
```

Generate User Address Proto

```bash
protoc -I=./proto --go_out=./pb/user_address --go_opt=paths=source_relative --go-grpc_out=./pb/user_address --go-grpc_opt=paths=source_relative proto/user_address.proto
```
