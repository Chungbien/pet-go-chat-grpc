gen-cal:
	protoc ./pb/chat.proto \
 	--go_out=./pb \
 	--go-grpc_out=./pb \
 	--go_opt=module=github.com/Chungbien/pet-go-chat-grpc/server/pb \
 	--go-grpc_opt=module=module=github.com/Chungbien/pet-go-chat-grpc/server/pb
run-server:
	go run main.go
run-client:
	go run calculator/client/main.go
gen-stream:
	protoc ./stream/proto/stream.proto --go_out=./stream/proto --go-grpc_out=./stream/proto --go_opt=module=github.com/Chungbien/udemy-grpc-course/stream/proto --go-grpc_opt=module=github.com/Chungbien/udemy-grpc-course/stream/proto
run-server-stream:
	go run stream/server/main.go
run-client-stream:
	go run stream/client/main.go