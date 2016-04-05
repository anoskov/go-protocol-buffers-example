## Install protocol buffers

$ git clone https://github.com/google/protobuf

$ cd protobuf

$ ./autogen.sh

$ ./configure

$ make

$ make check

$ make install

## Install dependencies

$ go get github.com/gogo/protobuf/proto

$ go get github.com/gogo/protobuf/protoc-gen-gogo

$ go get github.com/gogo/protobuf/gogoproto

$ go get github.com/gogo/protobuf/protoc-gen-gofast

## Generate Code

$ protoc --gogo_out=target/ --proto_path=templates/ templates/company.proto
