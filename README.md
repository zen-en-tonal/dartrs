# dartrs

> [!WARNING]
> wip

## Rust

```bash
cargo test
```

```bash
cargo run --manifest-path src/cli/Cargo.toml --release -- \
  --prompt "1girl" \
  --model-type mixtral \
  --model-name "p1atdev/dart-v2-mixtral-160m-sft-8"
```

Python bindings and packaging have been removed. The repository now exposes a Rust library plus the example CLI under `src/cli/`.
