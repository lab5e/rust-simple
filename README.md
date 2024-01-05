# Simple Rust example

This is a very simple example that uses the Span client library. Build the sample with
`cargo build`.

Create a new API token in the [Span dashboard](https://span.lab5e.com/) and run 
the sample with `cargo run [api token]`

## Adding the API client dependency

Add the following lines to the `[dependencies]`  section of your `Cargo.toml` file:

```text
spanapi = { git = "https://github.com/lab5e/rust-spanapi" }
futures = "0.3"
tokio = { version = "1", features = ["macros", "rt-multi-thread" ] }
```