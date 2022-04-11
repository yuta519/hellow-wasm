# Hellow WASM

## Create wasm project
> cargo new --lib hello-wasm

Before executing, you have to install wasm-pack,


## Compile from Rust to WASM
> wasm-pack build --target web

After above command, you can see the directory `pkg` is created.

## Check wasm running
> python3 -m http.server

Run above command and visit https://localhost:8000
