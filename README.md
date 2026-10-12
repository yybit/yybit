# yybit

**Rust Systems Programmer · AI Infrastructure**

Rust systems programmer working on LLM inference, filesystems, containers and package tooling.
Based in Shanghai, China. Open to roles in **Shanghai or remote**.

---

## Featured Projects

### [pllm](https://github.com/yybit/pllm) — Portable LLM

An LLM inference library written from scratch in Rust (ported from [llama2.c](https://github.com/karpathy/llama2.c)), targeting CPU and edge deployment.

- Supports LLaMA2 / Gemma architectures and the GGUF model format
- x86_64 AVX2 SIMD (inspired by candle) + multi-threaded inference, optimizing a 15M-parameter model from 81 to **204 tokens/s** on a 2.2 GHz quad-core i7
- Cross-compiles via `cargo zigbuild` to `x86_64-unknown-linux-musl` for container and edge deployment

### [nu_plugin_compress](https://github.com/yybit/nu_plugin_compress)

A Nushell plugin for compression and decompression supporting **zstd / gzip / bzip2 / xz**, published on [crates.io](https://crates.io/crates/nu_plugin_compress). My most-starred project (43 stars).

- Implements the Nushell plugin protocol with streaming compression and adjustable levels
- Automated crate publishing via GitHub Actions, semantic versioning, keeps pace with Nushell releases

### [ext4fs-rs](https://github.com/yybit/ext4fs-rs)

An ext4 filesystem implementation in Rust (user space), covering core data structures such as inodes, directory entries and block groups.

### [static-os](https://github.com/yybit/static-os)

A lightweight Linux distribution for hosting containers, running under QEMU / Lima virtualization, exploring static linking and minimal container runtimes.

### [rpmdb-rs](https://github.com/yybit/rpmdb-rs) · [nu_plugin_rpm](https://github.com/yybit/nu_plugin_rpm)

A Rust implementation of the RPM database plus a companion Nushell plugin, covering rpmdb parsing and RPM package reading.

### [zchunk-rs](https://github.com/yybit/zchunk-rs)

A pure Rust library for parsing and generating zchunk files — a chunked compression format for deduplication-aware syncing.

---

## Open Source Contributions

- **rpm-rs/rpm-rs** — [PR #201](https://github.com/rpm-rs/rpm-rs/pull/201) (merged): replaced the `capctl` crate with a minimal `filecaps` implementation, enabling the crate to build on non-Linux platforms.

---

## Tech Stack

- **Languages**: Rust (primary), C, Python
- **Systems**: filesystems, Linux distros / containers, RPM package management, SIMD optimization
- **AI**: LLM inference (Transformers, GGUF, CPU deployment)
- **Engineering**: crates.io publishing, GitHub Actions CI/CD, cross-platform cross-compilation

## Contact

- Email: <!-- TODO: fill in -->
- Blog / Social: <!-- TODO: fill in -->

Happy to talk about Rust, systems programming and AI infrastructure.
