# rust-recommended-libaries

A list of recommended libraries. "std required" is okay for libraries on this list.

There's a maximum two-three per task, of this grows to 58 libraries for error handling it doesn't help since people still don't know what to use.

# Error handling

## In libraries

[thiserror](https://crates.io/crates/thiserror)

## In applications

[anyhow](https://crates.io/crates/anyhow)

[eyere](https://crates.io/crates/eyre) / [color-eyere](https://crates.io/crates/color-eyre)

maybe:?

[snafu](https://crates.io/crates/snafu)

# Iterators

[itertools](https://crates.io/crates/itertools)

# Logging

## Libraries

[log](https://crates.io/crates/log) with [tracing](https://crates.io/crates/tracing) and [tracing-subscriber](https://crates.io/crates/tracing-subscriber)

## Applications

Can use log from above, or these:

[env_logger](https://crates.io/crates/env_logger)

# Serialization

[serde](https://crates.io/crates/serde), usually with [serde-json](https://crates.io/crates/serde_json)

# Data types

## Dates, times etc

[chrono](https://crates.io/crates/chrono)

## Float values

[float-ord](https://crates.io/crates/float-ord)

[noisy_float](https://crates.io/crates/noisy_float)

## Enums

[strum](https://crates.io/crates/strum)

## Bit flags

[bitflags](https://crates.io/crates/bitflags)

# Parse command line

[clap](https://crates.io/crates/clap)

[structopt](https://crates.io/crates/structopt)

# Web

[hyper](https://crates.io/crates/hyper) (low level server & client)

## Clients

[reqwest](https://crates.io/crates/reqwest)

## Servers

[actix](https://crates.io/crates/actix)

[rocket](https://crates.io/crates/rocket)

[warp](https://crates.io/crates/warp)

## WASM

[wasm-bindgen](https://crates.io/crates/wasm-bindgen)

[web-sys](https://crates.io/crates/web-sys)

## Frontend

[seed](https://crates.io/crates/seed)

[yew](https://crates.io/crates/yew)

# Async runtimes

[tokio](https://crates.io/crates/tokio)

[async-std](https://crates.io/crates/async-std)

# Linear algebra

[nalgebra](https://crates.io/crates/nalgebra)

[ndarray](https://crates.io/crates/ndarray)

# Byte juggling

[bytemuck](https://crates.io/crates/bytemuck) for generic byte mucking

[byteorder](https://crates.io/crates/byteorder)

# Cryptography

[crypto](https://crates.io/crates/crypto) has generic crypto algorithms.

[rustls](https://crates.io/crates/rustls) has a full TLS suite.

# Randomness

[rand](https://crates.io/crates/rand)

# Procedual Macros

[syn](https://crates.io/crates/syn) for parsing macro input

[quote](https://crates.io/crates/quote) for assambling macro output

[darling](https://crates.io/crates/darling) for parsing macro input into structs

# RegEx

[regex](https://crates.io/crates/regex)

# Database

## SQL

[sqlx](https://crates.io/crates/sqlx) for creating queries.

## ORM

[diesel](https://crates.io/crates/diesel)

# Want to contribute?

Great! Open a pull request, if you want a library added and there's already two for that task include motivation which should be removed and why.

# Why this list?

As an experienced (>10 years) backend developer the disconnect between the "Rust by example"-book and what I imagined "rust in production" to be was bugging me. I wasn't sure which libraries to go. A question on the rust reddit led me to create this.
