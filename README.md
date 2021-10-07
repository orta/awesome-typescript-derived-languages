# awesome-typescript-derived-languages

These projects aim to be (mostly) syntax compatible with TypeScript, but with different end goals than what TypeScript has. 

## TypeScript to Native

#### Static TypeScript

A re-implementation of TypeScript designed for the small memory-constrained devices with a visual programming environment.

- [Used in production at MakeCode Arcade](https://arcade.makecode.com)
- [Playground](https://makecode.com/playground#functions)
- [Research Paper](https://www.microsoft.com/en-us/research/publication/static-typescript/)
- [Repo](https://github.com/microsoft/pxt/tree/master/pxtcompiler)

#### TypeScriptCompiler

An LLVM-backed C++ implementation of TypeScript which can be built as native binaries or WASM.

- [Repo](https://github.com/ASDAlexander77/TypeScriptCompiler)

#### BorrowScript

A Rust-inspired specification for a version of TypeScript which adds syntax to describe how variables will be used in functions, allowing for reliable fast multi-threaded applications with a higher-level language than Rust.

- [Repo](https://github.com/alshdavid/BorrowScript)

## TypeScript to WASM

#### AssemblyScript

A re-implementation of TypeScript built specifically with the goals of compiling to WASM via [Binaryen](https://github.com/WebAssembly/binaryen).

- [Docs](https://www.assemblyscript.org)
- [Repo](https://github.com/AssemblyScript)

## TypeScript to JavaScript

#### DScript

A re-implementation of TypeScript in C# built with the goals of restricting dynamic features and allowing for predictive codeflow and parallel evaluation. 

- [Docs](https://github.com/microsoft/BuildXL/blob/master/Documentation/Wiki/DScript/Introduction.md#DScript-guiding-principles)
- [Repo](https://github.com/microsoft/BuildXL/tree/master/Public/Src/FrontEnd/TypeScript.Net/TypeScript.Net)

#### TS--

A TypeScript re-implementation of TypeScript built to be evaluated reactively (like a speadsheet), has a sound type-checker and restricts mutable state.

- [Repo](https://github.com/jaked/programmable-matter#language)
- [Write-up](https://jaked.org/blog/2021-09-07-Reconstructing-TypeScript-part-0)

