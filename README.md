```wasmtime```

cargo build --features component-model,wasi-nn,wasmtime-wasi-nn/onnx

./target/debug/wasmtime run -Snn --dir ../wasi-nn/rust/examples/classification-example/fixture/::fixture ../wasi-nn/rust/examples/classification-example/target/wasm32-wasip1/debug/classification-component-onnx.wasm
