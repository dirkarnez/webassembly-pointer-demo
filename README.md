webassembly-pointer-demo
========================
### Idea
- Do heap memory allocation in `WebAssembly.Memory` -> js get/set data to it, also remember the beginning address -> pass the beginning address as `i32` (e.g. not pointer `*` type) to .wasm

### Tutorials
- [WebAssembly.Memory - WebAssembly | MDN](https://developer.mozilla.org/en-US/docs/WebAssembly/Reference/JavaScript_interface/Memory)
