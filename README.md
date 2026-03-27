This is a fork of the [strict-num](https://crates.io/crates/strict-num) crate. The git repository is located at https://github.com/RazrFalcon/strict-num.

# ai-strict-num
![Build Status](https://github.com/atom-planet-embrace/ai-strict-num/workflows/Build/badge.svg)
[![Crates.io](https://img.shields.io/crates/v/ai-strict-num.svg)](https://crates.io/crates/ai-strict-num)
[![Documentation](https://docs.rs/ai-strict-num/badge.svg)](https://docs.rs/ai-strict-num)
[![Rust 1.56+](https://img.shields.io/badge/rust-1.56+-orange.svg)](https://www.rust-lang.org)

A collection of bounded numeric types.

Includes:

- `FiniteF32`
- `FiniteF64`
- `NonZeroPositiveF32`
- `NonZeroPositiveF64`
- `PositiveF32`
- `PositiveF64`
- `NormalizedF32`
- `NormalizedF64`

Unlike `f32`/`f64`, all float types implement `Ord`, `PartialOrd` and `Hash`,
since it's guaranteed that they all are finite.

## License

MIT
