[![Latest Version](https://img.shields.io/crates/v/motors?logo=Rust)](https://crates.io/crates/motors)
![Minimum Supported Rust Version](https://img.shields.io/crates/msrv/motors?logo=Rust)
[![License](https://img.shields.io/crates/l/motors)](https://crates.io/crates/motors)
[![Docs](https://img.shields.io/docsrs/motors?logo=docs.rs)](https://docs.rs/motors/latest/motors/)
[![CI](https://github.com/hansingt/motors/actions/workflows/ci.yml/badge.svg)](https://github.com/hansingt/motors/actions/workflows/ci.yml)
[![Code Coverage](https://codecov.io/gh/hansingt/motors/graph/badge.svg?token=udooUR2bx7)](https://codecov.io/gh/hansingt/motors)

# Motors

A platform and hardware independent, `no_std` crate implementing drivers for multiple
motors.

This crate uses [`embedded-hal`](https://github.com/rust-embedded/embedded-hal) traits
to allow it to be reused on multiple platforms and boards.

## Features

- [ ] Brushed DC Motor driver
- [ ] Brushless DC Motor driver
- [ ] Stepper Motor driver
- [ ] Synchronous AC Motor driver

## Minimum Supported Rust Version (MSRV)

This crate is guaranteed to compile on stable Rust 1.60 and up.
It *might* compile with older versions but that may change in any new patch release.

The MSRV may be updated according to the rules defined by
[embedded-hal](https://github.com/rust-embedded/embedded-hal/blob/HEAD/docs/msrv.md).

## License

Licensed under the MIT license
(either [LICENSE](LICENSE) or http://opensource.org/licenses/MIT).
