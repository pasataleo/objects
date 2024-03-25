# objects
 
The objects repository contains a generic implementation of a Type system based in protocol buffers. 
The idea is to have a generic way to represent data that can be easily serialized and deserialized.

## Languages

### Go

The Go implementation is held in the `go\` directory. 
It contains a single package, which is compiled from the `proto\objects.proto` file.

#### Compiling the Go package

```bash
protoc -I=./proto --go_out=./go ./proto/objects.proto
```
