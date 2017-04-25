# Creating a crate

## Start a new **crate**: 

```bash
$ cargo new rust-tutorial
```

* `src/lib.rs` - this is the root of your library. In an executable crate it's named `main.rs`.
* Cargo.toml

## Build your new crate: 

```bash
$ cargo build
```

## Run tests 

```bash
$ cargo test
```

## Import a dependency

```toml
// Cargo.toml
[dependencies]
serde_json = "1.0.0"
```

For the record, serde is a **ser**ialization and **de**serialization library. Think Json.NET for Rust.

Now, let's do a build to pull it down from [crates.io](crates.io) and compile it.
```bash
$ cargo build
```