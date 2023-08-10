# Web Assembly
The WebAssembly Binary Toolkit [Github.com/WebAssembly/wabt](https://github.com/WebAssembly/wabt)
-

- wat2wasm: translate from WebAssembly text format to the WebAssembly binary format
- wasm2wat: the inverse of wat2wasm, translate from the binary format back to the text format (also known as a .wat)
- wasm-objdump: print information about a wasm binary. Similiar to objdump.
- wasm-interp: decode and run a WebAssembly binary file using a stack-based interpreter
- wasm-decompile: decompile a wasm binary into readable C-like syntax.
- wat-desugar: parse .wat text form as supported by the spec interpreter (s-expressions, flat syntax, or mixed) and print "canonical" flat format
- wasm2c: convert a WebAssembly binary file to a C source and header
- wasm-strip: remove sections of a WebAssembly binary file
- wasm-validate: validate a file in the WebAssembly binary format
- wast2json: convert a file in the wasm spec test format to a JSON file and associated wasm binary files
- wasm-opcodecnt: count opcode usage for instructions
- spectest-interp: read a Spectest JSON file, and run its tests in the interpreter
