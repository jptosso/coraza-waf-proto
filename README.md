## Coraza WAF PROTO spec

This repository may be used to integrate your own technologies with Coraza WAF gRPC service.

## Building wrappers

You may check the official references for each wrapper.

## Testing

You may test it using the command ``$ protoc -I internal/proto --go_out=plugins=grpc:. internal/proto/*.proto`` or using our Dockerfile.
