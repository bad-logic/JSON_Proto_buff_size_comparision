
Comparing json and protocol buffers Sizes

step1: Run ./jsond.js in terminal to check fileSize of serialized jsondata\
step2: Download protoc compiler and generate proto_buf.js file\
step3: Run ./proto_buf.js in terminal to check fileSize of serialized protocol buffers\

step4: compare the file size generated by the same data as json and protocol buffers 

Download protoc compiler for your os:\
Link: https://github.com/protocolbuffers/protobuf/releases

generate proto_buf.js file from proto file:\
COMMAND: <extracted_folder>/bin/protoc --js_out=import_style=commonjs,binary:.<space><proto_filename.proto>
