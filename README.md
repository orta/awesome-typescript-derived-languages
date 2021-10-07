# awesome-typescript-derived-languages

These projects aim to be (mostly) syntax compatible with TypeScript, but with different end goals than what TypeScript has. 

## TypeScript to Native

#### Static TypeScript

A re-implementaion of TypeScript designed for the small memory-constrained devices.

- [Used in production at MakeCode Arcade](https://arcade.makecode.com)
- [Research Paper](https://www.microsoft.com/en-us/research/publication/static-typescript/)

#### TypeScriptCompiler

An LLVM-backed implementation of TypeScript which can be built as native binaries or WASM

- [GitHub](https://github.com/ASDAlexander77/TypeScriptCompiler)

#### BorrowScript

A Rust-inspired version of TypeScript which adds syntax to describe how variables will be used in functions, allowing for reliable fast multi-threaded applications.

- [GitHub](https://github.com/alshdavid/BorrowScript)

## TypeScript to WASM

#### BorrowScript

A re-implementation of TypeScript built specifically with the goals of compiling to WASM via [Binaryen](https://github.com/WebAssembly/binaryen).

- [Docs](https://www.assemblyscript.org)
- [Repo](https://github.com/AssemblyScript)
