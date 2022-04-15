# Crypto Fintech Tools for Rust (CFT)

## Dependencies

- Rust

### MacOS

- [Homebrew](https://brew.sh/)

```Shell
# xcode cli tools
xcode-select --install

# install dependencies using Homebrew
brew install cmake rust
```

---

## Build

```Shell
cargo build
```

### Prepare library

Using pkg-config, build is quickly.

```Shell
# decompress
sudo unzip -d / cft-sys-v0.0.1-osx-xcode9.4-static_x86_64.zip
# build
cargo build
```

---

## Test and Example

### Test

```
cargo test
```

### Example

```
cargo run --example create_pubkey_address
```

---

### formatter

- rustfmt

### linter

- clippy

### document tool

- cargo
  ```
  cargo doc
  ```

