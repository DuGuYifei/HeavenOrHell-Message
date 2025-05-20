# README

All the enums classes related to message should also be stored here, no matter it is `.h` or `.csharp`. Because it will eaiser to cooperate between clients and server while we will not have enough time to create docs for it.

for `csharp`:
```sh
protoc --csharp_out=./gen_cs/ ./*.proto
```

for compiling in `csharp`:

1. add NuGet for Unity by `add package from git URL` in the Package Manager
    ```
    https://github.com/GlitchEnzo/NuGetForUnity.git?path=/src/NuGetForUnity
    ```
2. search `Google.Protobuf` from the NuGetForUnity window. (NuGet in the top bar) 