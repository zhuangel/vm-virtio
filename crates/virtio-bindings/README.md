# virtio-bindings
Rust FFI bindings to virtio generated using [bindgen](https://crates.io/crates/bindgen).

# Usage
Add this to your `Cargo.toml`:
```toml
virtio-bindings = "0.1"
```
You can then import the bindings where you need them. As an example, to grab the
bindings for virtio-blk, you can do:
```rust
use virtio_bindings::bindings::virtio_blk::*;
```
