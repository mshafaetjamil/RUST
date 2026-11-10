# RUST

A workspace for learning Rust, starting with a Hello World program.

## Run

Install Rust and Cargo with [rustup](https://rust-lang.org/tools/install/), then run:

```sh
cargo run
```

Expected output:

```text
Hello, world!
```

If your terminal cannot find Cargo after installation, load its environment first:

```sh
source "$HOME/.cargo/env"
```

## Run in Zed

Open this folder in Zed, press **Cmd+Shift+R** on macOS, select **Run Rust**, and press Enter. The task saves your changes and runs the program in Zed's terminal.

## Project files

- `src/main.rs`: the program's entry point.
- `Cargo.toml`: package configuration.
- `Cargo.lock`: locked dependency versions.
- `.zed/tasks.json`: the Zed run task.

Build output, macOS metadata, and local book downloads are excluded from Git.
