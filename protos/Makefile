run:
	protoc --go_out=../pb/golang/ --go_opt=paths=source_relative \
    --go-grpc_out=../pb/golang/ --go-grpc_opt=paths=source_relative \
    helloworld/helloworld.proto 

	# protoc -I=helloworld --java_out=../pb/java helloworld/helloworld.proto

clean:
	rm -r ../pb/golang/*
	rm -r ../pb/java/*