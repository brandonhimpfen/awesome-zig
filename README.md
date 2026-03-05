# Awesome Zig [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, libraries, frameworks, compilers, build systems, learning resources, and real-world projects for **Zig**, a general-purpose systems programming language focused on performance, safety, and simplicity.

## Contents

- [Official Resources](#official-resources)
- [Language Tooling & Build System](#language-tooling--build-system)
- [Standard Library & Core Utilities](#standard-library--core-utilities)
- [Package Management & Registries](#package-management--registries)
- [C/C++ Interoperability](#cc-interoperability)
- [Web, Networking & APIs](#web-networking--apis)
- [Game Development & Graphics](#game-development--graphics)
- [Embedded, OS & Low-Level Systems](#embedded-os--low-level-systems)
- [Testing, Debugging & Profiling](#testing-debugging--profiling)
- [Editor & IDE Support](#editor--ide-support)
- [Learning Resources](#learning-resources)
- [Real-World Projects & Examples](#real-world-projects--examples)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [Zig Language](https://ziglang.org/) – Official website with downloads, documentation, and language overview.
- [Zig Documentation](https://ziglang.org/documentation/) – Authoritative docs covering language features and the standard library.
- [Zig GitHub Repository](https://github.com/ziglang/zig) – Source code, issues, and development roadmap for Zig.
- [Zig Community](https://ziglang.org/community/) – Official community links including forums, Discord, and mailing lists.

## Language Tooling & Build System

- [Zig Compiler](https://ziglang.org/download/) – Self-hosted compiler supporting cross-compilation without external dependencies.
- [Zig Build System](https://ziglang.org/documentation/master/#The-Build-System) – Built-in build system replacing Make, CMake, and Meson.
- [Zig Cross Compilation](https://ziglang.org/learn/overview/#cross-compilation) – First-class cross-compilation with bundled libc targets.
- [Zig cc / c++](https://ziglang.org/learn/overview/#zig-cc) – Drop-in C/C++ compiler replacement powered by Zig.
- [Zig Toolchain](https://ziglang.org/learn/overview/) – End-to-end toolchain for building, linking, and testing binaries.

## Standard Library & Core Utilities

- [Zig Standard Library](https://ziglang.org/documentation/master/std/) – Core library providing allocators, containers, IO, and OS abstractions.
- [Allocator API](https://ziglang.org/documentation/master/std/#A;std.mem.Allocator) – Explicit memory management interface central to Zig’s design.
- [Async I/O](https://ziglang.org/documentation/master/#Async-Functions) – Language-level async support without hidden runtimes.
- [Error Handling](https://ziglang.org/documentation/master/#Errors) – Explicit error unions for predictable failure handling.

## Package Management & Registries

- [Zig Package Manager](https://ziglang.org/documentation/master/#Package-Management) – Native package management integrated into the build system.
- [Zigmod](https://github.com/nektro/zigmod) – Dependency manager for Zig projects using a lockfile-based workflow.
- [gyro](https://github.com/mattnite/gyro) – Zig package manager inspired by Cargo-style dependency resolution.
- [Astrolabe.pm](https://github.com/ziglang/astrolabe) – Experimental package registry tooling for Zig ecosystems.

## C/C++ Interoperability

- [@cImport](https://ziglang.org/documentation/master/#cImport) – Import C headers directly into Zig code.
- [Zig as a C Compiler](https://ziglang.org/learn/overview/#zig-cc) – Use Zig to compile C projects with simplified cross-platform builds.
- [C ABI Compatibility](https://ziglang.org/documentation/master/#C) – Seamless interoperability with existing C libraries.
- [Build.zig C Integration](https://ziglang.org/documentation/master/#The-Build-System) – Native support for compiling and linking C/C++ sources.

## Web, Networking & APIs

- [zap](https://github.com/zigzap/zap) – High-performance HTTP server library built on Zig.
- [http.zig](https://github.com/karlseguin/http.zig) – Lightweight HTTP server and client library.
- [zig-network](https://github.com/MasterQ32/zig-network) – Cross-platform networking abstractions for Zig.
- [zig-json](https://github.com/ziglibs/json) – JSON parsing and serialization utilities.
- [zfetch](https://github.com/ziglibs/zfetch) – Simple HTTP client for Zig applications.

## Game Development & Graphics

- [mach](https://github.com/hexops/mach) – Game engine and graphics framework written in Zig.
- [zglfw](https://github.com/ziglibs/zglfw) – GLFW bindings for windowing and input in Zig.
- [zgpu](https://github.com/zig-gamedev/zgpu) – GPU abstraction layer supporting modern graphics APIs.
- [zmath](https://github.com/zig-gamedev/zmath) – SIMD-friendly math library for games and simulations.
- [raylib-zig](https://github.com/Not-Nik/raylib-zig) – Zig bindings for the raylib game programming library.

## Embedded, OS & Low-Level Systems

- [Zig Embedded](https://ziglang.org/documentation/master/#Embedded) – Bare-metal and embedded development support.
- [microzig](https://github.com/ZigEmbeddedGroup/microzig) – Embedded HAL and tooling for microcontrollers.
- [Zig Bootloaders](https://github.com/ziglang/zig/issues/390) – Experimental work on bootloaders and OS components.
- [Zig OS Dev Examples](https://github.com/ziglang/zig/tree/master/examples) – Low-level examples including freestanding binaries.
- [freestanding Zig](https://ziglang.org/documentation/master/#Freestanding) – Building kernels and firmware without an OS.

## Testing, Debugging & Profiling

- [Zig Test Framework](https://ziglang.org/documentation/master/#Testing) – Built-in unit testing integrated into the language.
- [Zig Debugging](https://ziglang.org/documentation/master/#Debugging) – Native debug symbols and tooling support.
- [Valgrind with Zig](https://valgrind.org/) – Memory debugging for Zig programs compiled with debug info.
- [perf + Zig](https://perf.wiki.kernel.org/) – Linux profiling tools compatible with Zig binaries.
- [Sanitizers](https://ziglang.org/documentation/master/#Sanitizers) – Address and undefined behavior sanitizers support.

## Editor & IDE Support

- [Zig Language Server (ZLS)](https://github.com/zigtools/zls) – Language server providing autocomplete, diagnostics, and navigation.
- [VS Code Zig Extension](https://marketplace.visualstudio.com/items?itemName=ziglang.vscode-zig) – Official VS Code support for Zig.
- [Neovim Zig Support](https://github.com/ziglang/zig.vim) – Syntax highlighting and editor integration for Vim/Neovim.
- [Emacs Zig Mode](https://github.com/ziglang/zig-mode) – Emacs major mode for Zig development.
- [JetBrains Zig Plugin](https://plugins.jetbrains.com/) – Community-driven Zig support for JetBrains IDEs.

## Learning Resources

### Tutorials
- [Zig Learn](https://ziglang.org/learn/) – Official learning resources and guided examples.
- [Ziglings](https://github.com/ratfactor/ziglings) – Hands-on exercises for learning Zig fundamentals.
- [Zig by Example](https://zig-by-example.com/) – Practical examples demonstrating core Zig concepts.

### Guides
- [Zig Language Reference](https://ziglang.org/documentation/master/) – Complete technical reference for the language.
- [Why Zig When There Is C++?](https://ziglang.org/learn/why_zig_rust_d_cpp/) – Design philosophy and comparisons.
- [Memory Management in Zig](https://ziglang.org/documentation/master/#Memory) – Deep dive into allocators and safety guarantees.

### Courses
- *Systems Programming with Zig* – Course focused on low-level programming concepts using Zig.
- *Zig for C Developers* – Transition guide for experienced C programmers.
- *Game Development with Zig* – Course exploring graphics and engine design using Zig.

## Real-World Projects & Examples

- [Bun (Zig components)](https://bun.sh/) – JavaScript runtime leveraging Zig for performance-critical components.
- [TigerBeetle](https://github.com/tigerbeetle/tigerbeetle) – Distributed financial database written in Zig.
- [Zig Self-Hosted Compiler](https://github.com/ziglang/zig) – Large-scale real-world Zig codebase.
- [Zig Game Projects](https://github.com/zig-gamedev) – Community-driven game development repositories.

## Related Awesome Lists

- [Awesome C](https://github.com/awesomelistsio/awesome-c)
- [Awesome Rust](https://github.com/awesomelistsio/awesome-rust)
- [Awesome Systems Programming](https://github.com/awesomelistsio/awesome-systems-programming)
- [Awesome Compilers](https://github.com/awesomelistsio/awesome-compilers)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
