# Hello World in Rust

![Rust
Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Rust_programming_language_black_logo.svg/240px-Rust_programming_language_black_logo.svg.png)

This is a trivial 'Hello World' to check availability and configuration of the
Rust toolchain.

## Setup

```bash
git clone https://github.com/lwieske/rust-hello-world
cd rust-hello-world
```

## Prepare

```bash
cargo update
```

## Build

```bash
cargo build
```

## Run

```bash
cargo run
```

## Example

```bash
% rustc --version
rustc 1.62.0 (a8314ef7d 2022-06-27)
% cargo update
% cargo build
   Compiling hello_world v0.0.1 (/Users/lothar/GitHub/rust-hello-world)
    Finished dev [unoptimized + debuginfo] target(s) in 0.58s
% cargo run
   Compiling hello_world v0.0.1 (/Users/lothar/GitHub/rust-hello-world)
    Finished dev [unoptimized + debuginfo] target(s) in 0.12s
     Running `target/debug/hello_world`
Hello, world!
% 
```
