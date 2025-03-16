# askama_playground

This is the source code for https://askama-rs.github.io/askama_playground/ which allows you to
test the [askama](https://crates.io/crates/askama) directly in your web browser.

To run this website locally:

```
git submodule update --remote --no-recommend-shallow
rustup target add wasm32-unknown-unknown
cargo install trunk
trunk serve
```
