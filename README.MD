## Learning Goal Steps
1. Make a client
2. Make a server 
3. Make a Proto file
4. Utilize proto file to generate client, and server code in Go
5. Make the client, and server talk to each other

## Command
protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative grpc-service/grpc-service.proto