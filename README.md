# golang-communicate-with-python-by-using-grpc
https://youtu.be/8QRhlPnOKhM

## generate protobuff files and grpc files
```bash
python3 -m grpc_tools.protoc -I protos/  --python_out=py_protos --grpc_python_out=py_protos hi.proto
```

```bash
sudo apt install -y protobuf-compiler

protoc --go_out=go_protos --go_opt=paths=source_relative --go-grpc_out=go_protos --go-grpc_opt=paths=source_relative ./protos/hi.proto
```
