# How can I use it?

<img src="assets/simply.jpg" alt="simply" style="position: absolute; right: 44px; top: 33px" width=277 />

## Compiled languages
You can use a console command to compile your source to wasm
```bash
rustc --target wasm32-unknown-unknown my-project.rs
```

## Interpreted languages
There are pre-compiled interpreters available, they allow you to use JIT to virtually run any interpreted language [straight on your browser](https://wasmlabs.dev/projects/wasm-language-runtimes/)

As a sample, here's a [python runtime environment project](https://pyscript.net/)


<!-- interoperability is also one of the biggest strenghts of wasm, who has a good shot of being all that Java always wanted to be, through inclusion -->

<!-- offers interoperability API with Javascript, not here to compete but to join forces -->
<!-- JS runtime needs to parse, compile and optimize. WASM only need to decode it's Text Format to binary and run. Very straightforward -->
<!-- You can call WebAssembly functions in JavaScript code and you can call JavaScript functions in WebAssembly modules. -->