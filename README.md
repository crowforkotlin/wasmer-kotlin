# The following content is from research prior to December 4, 2025.

# ✅ wasmtime (Only the minimum supported Kotlin version is 2.3.0-RC)
> [wasmline-kotlin multiplatform](https://github.com/crowforkotlin/wasmline) based on > [wasmtime](https://github.com/bytecodealliance/wasmtime)


# ❌ wasmer 
> Seems unusable. Running it on Windows throws an error: note: `run with RUST_BACKTRACE=1 environment variable to display a backtrace.` This option is currently discarded.
- [wasmer](https://github.com/wasmerio/wasmer)
- [wasmer-java](https://github.com/wasmerio/wasmer-java)

# ❌ wazero
> wazero does not support some new features and, like most other mainstream WASM runners, suffers from the same problem: read 0-th type: invalid byte: 0x5e != 0x60 (gc not support)
- [wazero](https://github.com/wazero/wazero)

# ❌ wasmedge 
> The compilation process is overly complex. Android support seems to have a demo, but after trying multi-platform compilation, I encountered problems on Windows that I feel are quite tricky to resolve.
- [wasmedge android bug](https://github.com/issues/created?issue=WasmEdge%7CWasmEdge%7C4426)
- [wasmedge](https://github.com/WasmEdge/WasmEdge)
- [wasmedge-android-demo](https://github.com/second-state/wasmedge-android)

# ❌ wasm-micro-runtime
> The description claims multi-platform support, but there is no Java sample. Might it require kn?
> Kotlin Wasm adopts new official WebAssembly proposals, such as WasmGC. Since most mainstream libraries do not support these yet, errors like 'invalid section id' or 'invalid byte: 0x5e != 0x60' are thrown when loading the Wasm file.
- [wasm-micro-runtime](https://github.com/bytecodealliance/wasm-micro-runtime)

# ❌ wasm3
> Has not been updated for a year, and the issues list suggests numerous problems. Tentatively rejected.
- [wasm3](https://github.com/wasm3/wasm3)
