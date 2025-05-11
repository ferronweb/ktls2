# ktls2

Configures kTLS ([kernel TLS
offload](https://www.kernel.org/doc/html/latest/networking/tls-offload.html))
for any type that implements `AsRawFd`, given a rustls `ServerConnection`, with Monoio support.

This crate is based on the [`ktls`](https://github.com/rustls/ktls) crate.

## License

This project is primarily distributed under the terms of both the MIT license
and the Apache License (Version 2.0).

See [LICENSE-APACHE](LICENSE-APACHE) and [LICENSE-MIT](LICENSE-MIT) for details.
