# grpc_lib

A small library of some functions that are shared between the grpc
application (gRPC server in Erlang) and the grpc_client application (gRPC 
client in Erlang).

## Build
gRPC uses [erlang.mk](https://erlang.mk/) as build tool. On Unix systems it can be built
with: 

```
make
```

`make edoc` can be used to generate documentation for the individual
modules from edoc comments in those modules.

See the [erlang.mk documentation](https://erlang.mk/guide/installation.html#_on_windows) for
an explanation on how the tool can be used in a Windows environment.

## Dependencies

- [gpb](https://github.com/tomas-abrahamsson/gpb) is used to encode and
  decode the protobuf messages. This is a 'build' dependency: the generated 
  modules do not need gpb at run time.

## License

Apache 2.0

