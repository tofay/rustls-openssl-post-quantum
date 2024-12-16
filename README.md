# rustls-openssl-post-quantum
Experimental post-quantum key exchange algorithms from [liboqs](https://github.com/open-quantum-safe/liboqs) for use with
[rustls](https://docs.rs/rustls/latest/rustls/crypto/struct.CryptoProvider.html).


[![crates.io](https://img.shields.io/crates/v/rustls-openssl-post-quantum?style=flat-square&logo=rust)](https://crates.io/crates/rustls-openssl-post-quantum)
[![Build Status](https://github.com/tofay/rustls-openssl-post-quantum/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/tofay/rustls-openssl-post-quantum/actions/workflows/ci.yml?query=branch%3Amain)
[![Documentation](https://docs.rs/rustls-openssl-post-quantum/badge.svg)](https://docs.rs/rustls-openssl-post-quantum/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Coverage Status (codecov.io)](https://codecov.io/gh/tofay/rustls-openssl-post-quantum/branch/main/graph/badge.svg)](https://codecov.io/gh/tofay/rustls-openssl-post-quantum/)

## Key Exchange Algorithms
* MLKEM768
* X25519MLKEM768

## Pre-requisites
The following need to be installed for this crate to function:
* OpenSSL 3.0 or later
* liboqs
* oqsprovider

## Usage

See the [client example](./examples/client.rs).