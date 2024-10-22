> [!IMPORTANT]  
> `rust-url-wasmcloud` is a fork of [rust-url](https://github.com/servo/rust-url) that removes an unstable library feature that prevents the `url` crate from compiling on stable `wasm32-wasip2`. When [rust-url PR #983](https://github.com/servo/rust-url/pull/983) is merged and released, this crate will be deprecated in favor of the original crate.

rust-url-wasmcloud
========

[![Build status](https://github.com/servo/rust-url/workflows/CI/badge.svg)](https://github.com/servo/rust-url/actions?query=workflow%3ACI)
[![Coverage](https://codecov.io/gh/servo/rust-url/branch/master/graph/badge.svg)](https://codecov.io/gh/servo/rust-url)
[![Chat](https://img.shields.io/badge/chat-%23rust--url:mozilla.org-%2346BC99?logo=Matrix)](https://matrix.to/#/#rust-url:mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE-MIT)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE-APACHE)

URL library for Rust, based on the [URL Standard](https://url.spec.whatwg.org/).

[Documentation](https://docs.rs/url)

Please see [UPGRADING.md](https://github.com/servo/rust-url/blob/main/UPGRADING.md) if you are upgrading from a previous version.
