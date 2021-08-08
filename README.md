# rust-recommended-libaries

A list of recommended libraries. 

There's a maximum two per task, of this grows to 58 libraries for error handling it doesn't help since people still don't know what to use.

## Error handling

### In libraries

[thiserror](https://crates.io/crates/thiserror)

### In applications

[anyhow](https://crates.io/crates/anyhow)

[eyere](https://crates.io/crates/eyre) / [color-eyere](https://crates.io/crates/color-eyre)

## Logging

[log](https://crates.io/crates/log) with [tracing](https://crates.io/crates/tracing) and [tracing-subscriber](https://crates.io/crates/tracing-subscriber)

## Want to contribute?

Great! Open a pull request, if you want a library added and there's already two for that task include motivation which should be removed and why.

## Why?

As an experienced (>10 years) backend developer the disconnect between the "Rust by example"-book and what I imagined "rust in production" to be was bugging me. I wasn't sure which libraries to go. A question on the rust discord led me to create this.
