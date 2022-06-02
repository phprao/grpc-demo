# grpc-demo
a grpc demo for golang

cd grpc-demo
protoc --go_out=plugins=grpc:./ ./pkg/pbs/helloworld.proto

cd server
go run main.go

cd client
go run main.go