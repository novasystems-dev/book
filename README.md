<div align="center">

# 📖 The Nova Systems Language Book

**The Comprehensive Official Guide to Provable Systems Programming in Nova**

<br />

[![License](https://img.shields.io/badge/license-PolyForm-a855f7?style=flat&labelColor=0f172a&logo=open-source-initiative&logoColor=white)](LICENSE)
[![Nova](https://img.shields.io/badge/language-Nova_0.3.0-38bdf8?style=flat&labelColor=0f172a&logo=starship&logoColor=white)](https://github.com/novasystems-dev/nova)
[![Format](https://img.shields.io/badge/format-mdBook-10b981?style=flat&labelColor=0f172a&logo=gitbook&logoColor=white)](src/)
[![Ecosystem](https://img.shields.io/badge/ecosystem-10%20repos-f59e0b?style=flat&labelColor=0f172a&logo=github&logoColor=white)](https://github.com/novasystems-dev)

<br />

</div>

---

## 📖 Book Structure

- **Chapter 1: Getting Started**: Toolchain installation (`novac`, `orbit`), hello world, editor configuration.
- **Chapter 2: Primitive Types & Variables**: Integers, floats, booleans, immutability, type inference.
- **Chapter 3: The Perceus Memory Model**: Reference counting, destructive in-place buffer reuse, zero-GC execution.
- **Chapter 4: SMT Refinement Types**: Formal verification of bounds and non-zero division using Microsoft Z3.
- **Chapter 5: Concurrency Primitives**: Isolated memory (`iso`), immutable sharing (`val`), and fiber channels.
- **Chapter 6: Bare-Metal Systems Control**: Raw pointers (`*mut T`), inline assembly, and direct hardware interfacing.

---

## 🚀 Building the Book Locally

Install `mdbook` and run:

```bash
mdbook serve --open
```

---

## ⚖️ License

The Nova Book is released under the **PolyForm Noncommercial License 1.0.0**. Copyright (c) 2026 Fyew999 (Nova Systems).
