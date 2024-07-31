# awesome-typescript-derived-languages

These projects aim to be (mostly) syntax compatible with TypeScript, but with different end goals than what TypeScript has. 

## TypeScript to Native

#### DeviceScript (2023 - Present)

TypeScript for Tiny IoT Devices. DeviceScript brings a professional TypeScript developer experience to low-resource microcontroller-based devices. DeviceScript is compiled to a custom VM bytecode, which can run in very constrained environments.

- [Site](https://microsoft.github.io/devicescript/)
- [Repo](https://github.com/microsoft/devicescript/)

#### Static TypeScript (2019 - Present)

A re-implementation of TypeScript designed for small memory-constrained devices with a visual programming environment.

- [Used in production at MakeCode Arcade](https://arcade.makecode.com)
- [Playground](https://makecode.com/playground#functions)
- [Research Paper](https://www.microsoft.com/en-us/research/publication/static-typescript/)
- [Repo](https://github.com/microsoft/pxt/tree/master/pxtcompiler)

#### TypeScriptCompiler (2021 - Present)

An LLVM-backed C++ implementation of TypeScript which can be built as native binaries or WASM.

- [Repo](https://github.com/ASDAlexander77/TypeScriptCompiler)

#### Porffor (2024 - Present)

A from-scratch experimental ahead-of-time JS engine with native TypeScript support

Porffor is a unique JS engine/compiler/runtime, compiling JS code to WebAssembly or native ahead-of-time.
It is seriously limited for now; intended for research, not serious use!

- [Site](https://porffor.dev)
- [Repo](https://github.com/CanadaHonk/porffor)

## TypeScript to WASM

#### AssemblyScript (2017 - Present)

A re-implementation of TypeScript built specifically with the goals of compiling to WASM via [Binaryen](https://github.com/WebAssembly/binaryen).

- [Docs](https://www.assemblyscript.org)
- [Repo](https://github.com/AssemblyScript)

## TypeScript to Many Languages

#### roblox-ts (2020 - Present)

roblox-ts is an attempt to bridge the abilities of TypeScript to work in a Roblox environment. We break down your code into an abstract syntax tree and emit functionally similar structures in Luau so that the code behaves the same.

- [Site](https://roblox-ts.com/)
- [Repo](https://github.com/roblox-ts/roblox-ts)


#### JSii (2018 - Present)

A project using a modified TypeScript compiler to allow a subset of JS/TS code to be portable across Python, Java, C# and other .NET languages. Built to make it easy to create polyglot libraries.

- [Overview](https://aws.amazon.com/blogs/opensource/how-the-jsii-open-source-framework-meets-developers-where-they-are/)
- [Repo](https://github.com/aws/jsii/tree/main/packages/jsii)

## TypeScript to JavaScript

#### DScript (2019 - Present)

A re-implementation of TypeScript in C# built with the goals of restricting dynamic features and allowing for predictive codeflow and parallel evaluation. 

- [Docs](https://github.com/microsoft/BuildXL/blob/master/Documentation/Wiki/DScript/Introduction.md#DScript-guiding-principles)
- [Repo](https://github.com/microsoft/BuildXL/tree/master/Public/Src/FrontEnd/TypeScript.Net/TypeScript.Net)

#### TS-- (2021)

A TypeScript re-implementation of TypeScript built to be evaluated reactively (like a spreadsheet), has a sound type-checker and restricts mutable state.

- [Repo](https://github.com/jaked/programmable-matter#language)
- [Write-up](https://jaked.org/blog/2021-09-07-Reconstructing-TypeScript-part-0)

#### Mini Typescript (2021)

Mini Typescript (_yes, with the lowercase-s_) is a miniature version of the TypeScript compiler, built with the goal of helping you understand the compiler architcture of the main TypeScript compiler

- [Repo](https://github.com/sandersn/mini-typescript).


#### BorrowScript (2022)

A Rust-inspired specification for a version of TypeScript which adds syntax to describe how variables will be used in functions, allowing for reliable fast multi-threaded applications with a higher-level language than Rust.

- [Repo](https://github.com/alshdavid/BorrowScript)
