# Global Map Tile [![Build Status](https://github.com/tigroo31/globalmaptile/workflows/Rust/badge.svg)](https://github.com/tigroo31/globalmaptile/actions) [![crates.io](https://img.shields.io/crates/v/globalmaptile)](https://crates.io/crates/globalmaptile)

Ported from Python implementation https://gist.github.com/maptiler/fddb5ce33ba995d5523de9afdf8ef118

Convert a raster into TMS tiles.

## Build

* Install Rust using rustup `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
* Install rustfmt

```shell script
$ source $HOME/.cargo/env
$ rustup component add rustfmt
...
$
```

* To compile and build the library, run using `cargo`:

```shell script
$ cargo fmt
$ cargo build --all
$ cargo build --all --release
```

## Use

Import the library into your Rust development.
Check the documentation on https://docs.rs/globalmaptile

## Development

The project stays public.

### Environment

Clone the the repository from https://github.com/tigroo31/globalmaptile.git .

### Contribution

See https://github.com/tigroo31/globalmaptile
