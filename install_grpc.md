### go 安装 grpc
``` git 
 git clone https://github.com/grpc/grpc-go.git $GOPATH/src/google.golang.org/grpc
 git clone https://github.com/golang/net.git $GOPATH/src/golang.org/x/net
 git clone https://github.com/golang/text.git $GOPATH/src/golang.org/x/text 
 go get -u github.com/golang/protobuf/{proto,protoc-gen-go}
 git clone https://github.com/google/go-genproto.git $GOPATH/src/google.golang.org/genproto
 git clone https://e.coding.net/robinqiwei/googleprotobuf.git $GOPATH/src/google.golang.org/protobuf

 cd $GOPATH/src/
 go install google.golang.org/grpc
```
