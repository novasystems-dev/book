# The Nova Systems Programming Language Book

> **The Official Guide to Deterministic Zero-GC Systems Programming**

This repository hosts the official textbook and guide for the **Nova Systems Programming Language**, published online at [novasystems-dev.github.io/book](https://novasystems-dev.github.io/book/).

---

## Contents

1. **Getting Started**: Installation, Toolchain, Hello World
2. **Deterministic Memory**: The Perceus In-Place Recycling Model
3. **Formal Correctness**: Refinement Types & Z3 SMT Proofs
4. **Fearless Concurrency**: Isolated Actor Channels & Capabilities
5. **Bare-Metal Parity**: Hardware Pointers, Memory-Mapped I/O, Inline Assembly
6. **Standard Library**: High-Performance Data Structures & Cryptography

---

## Building Locally

```bash
# Requires mdbook
cargo install mdbook
mdbook serve --open
```

---

## License

PolyForm Noncommercial License 1.0.0. Copyright (c) 2026 Fyew999 (Nova Systems).
See [LICENSE](LICENSE) for details.
