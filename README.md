# pleme-deref-derive

Newtype Deref: impl Deref for Wrapper with Target = Inner. Makes every method on Inner reachable through a Wrapper.

[![Build](https://github.com/pleme-io/pleme-deref-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-deref-derive.svg)](https://crates.io/crates/pleme-deref-derive)

## Install

```toml
[dependencies]
pleme-deref-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
