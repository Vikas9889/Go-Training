install-windows:
		choco install protoc --pre
		

install-mac:
		brew install protoc


build:
		protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative proto/hello.proto
run:
		go run main.go

test:
		go run Client/cli.go
		