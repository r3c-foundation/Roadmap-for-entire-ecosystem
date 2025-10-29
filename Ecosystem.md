# 🧩 R3C Ecosystem Structure

The R3C ecosystem is structured as layered repositories,  
each reinforcing independence, reproducibility, and transparency.

---

### 🌱 Core Repositories

| Layer | Repository | Description |
|:--|:--|:--|
| **Compiler Core** | [r3c](https://github.com/r3c-foundation/r3c) | Bidirectional C++ ↔ Rust transpiler |
| **Package Layer** | [cpppm](https://github.com/r3c-foundation/cpppm) | Reproducible package and build ecosystem |
| **Rust LTSS** | [rust-ltss](https://github.com/r3c-foundation/rust-ltss) | Frozen Rust baseline (v1.70.x) |
| **Beyond LLVM** | [beyond-llvm](https://github.com/r3c-foundation/beyond-llvm) | NASM backend and LLVM removal |
| **Roadmap Docs** | [roadmap-for-r3c](https://github.com/r3c-foundation/roadmap-for-r3c) | Strategic documentation center |

---

### 🧱 Layered Architecture

C++ Source ↓ [cpppm] Dependency Build ↓ [r3c] Transpile (C++ ↔ Rust) ↓ [rust-ltss] Compile (Rust LTSS v1.70) ↓ [beyond-llvm] Emit NASM Binary ↓ Reproducible Artifact

---

### 🪶 Auxiliary Projects

- **R3C-Nightly-LTSS** → Automated 3OS nightly builds  
- **LLVM-Zero-Ecosystem** → Experimental LLVM-free IRs  
- **Rust-Embedded-LTSS** → Long-term support for embedded targets

---

> Each layer sustains the next.  
> Independence is achieved through reproducibility.


---
