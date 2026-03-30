webassembly-pointer-demo
========================
### Idea
- [js] Do heap memory allocation in `WebAssembly.Memory` -> [js] get/set data to it, also remember the beginning address -> [js] pass the beginning address as `i32` (e.g. not pointer `*` type) to .wasm -> [WASM] access the data according to the beginning address by `local.get`

### Tutorials
- [WebAssembly.Memory - WebAssembly | MDN](https://developer.mozilla.org/en-US/docs/WebAssembly/Reference/JavaScript_interface/Memory)
