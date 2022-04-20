## grpc_protobuff_test

https://www.youtube.com/watch?v=YudT0nHvkkE

# grpc
> protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative usermgmt/usermgmt.proto
> go run usermgmt_server/usermgmt_server.go
> go run usermgmt_client/usermgmt_client.go

# Docker
> docker run --name go-grpc -e POSTGRES_PASSWORD=mysecretpassword -p 5431:5431 -d postgres
> docker exec -it go-grpc /bin/bash
> su - postgres
> psql
