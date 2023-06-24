# Wasmini

Proof of concept on how to create minimal wasm module.

- Doesn't require Emscripten
- Simple toolchain, compiles to wasm in a single step. See & run `build.bat` (Windows) or `build.sh` (Linux)

## Toolchain

You need Clang and its linker to run the build scripts, which can be downloaded from the [LLVM project](https://releases.llvm.org/download.html).

On Windows, the [Chocolatey](https://chocolatey.org/) package manager can also be used to install Clang.