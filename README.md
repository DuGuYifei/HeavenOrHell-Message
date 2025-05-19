# README

All the enums classes related to message should also be stored here, no matter it is `.h` or `.csharp`. Because it will eaiser to cooperate between clients and server while we will not have enough time to create docs for it.

for `csharp`:
```sh
protoc --csharp_out=./gen_cs/ ./*.proto
```