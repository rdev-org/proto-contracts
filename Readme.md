Generate Proto
```bash
protoc -I=./proto --go_out=./pb/domain --go_opt=paths=source_relative --go-grpc_out=./pb/domain --go-grpc_opt=paths=source_relative <proto_file>
```