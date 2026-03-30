webassembly-pointer-demo
========================
### Idea
- [js] Do heap memory allocation in `WebAssembly.Memory` -> [js] get/set data to it, also remember the beginning address -> [js] pass the beginning address as `i32` (e.g. not pointer `*` type) to .wasm -> [WASM] access the data according to the beginning address by `local.get`

### Tutorials
- [WebAssembly.Memory - WebAssembly | MDN](https://developer.mozilla.org/en-US/docs/WebAssembly/Reference/JavaScript_interface/Memory)
  - [webassembly-examples/js-api-examples/memory.wat at main · mdn/webassembly-examples](https://github.com/mdn/webassembly-examples/blob/main/js-api-examples/memory.wat)
  - [webassembly-examples/js-api-examples/memory.html at main · mdn/webassembly-examples](https://github.com/mdn/webassembly-examples/blob/main/js-api-examples/memory.html)
- [Compiling C to WebAssembly without Emscripten — surma.dev](https://surma.dev/things/c-to-webassembly/)
