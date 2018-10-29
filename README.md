[![Build Status](https://travis-ci.org/fastgrin/rust-secp256k1-zkp.png?branch=master)](https://travis-ci.org/fastgrin/rust-secp256k1-zkp)

### rust-secp256k1-zkp

This is a rust wrapper around **secp256k1-zkp** library.

`secp256k1-zkp` is an optimized C library for EC(Elliptic Curve) operations on curve secp256k1, the [main contributors](https://github.com/ElementsProject/secp256k1-zkp/graphs/contributors) include:
* [Peter Wuille](https://www.linkedin.com/in/pieterwuille), Co-founder and Core Tech Engineer of Blockstream. 
* [Gregory Maxwell](https://github.com/gmaxwell), Bitcoin Core developer, Co-Founder and CTO of Blockstream ([resigned](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2018-January/015586.html) from Blockstream 2017 Nov.).
* [Andrew Poelstra](https://www.linkedin.com/in/andrew-poelstra-958a75106/), Mathematician at Blockstream.
* [Grin Developers](https://github.com/orgs/mimblewimble/people) on repo [mimblewimble/secp256k1-zkp](https://github.com/mimblewimble/secp256k1-zkp).
* And all [other contributors](https://github.com/fastgrin/secp256k1-zkp/graphs/contributors).

You can find more detail about it on [bitcoin/secp256k1](https://github.com/bitcoin/secp256k1), [mimblewimble/secp256k1-zkp](https://github.com/mimblewimble/secp256k1-zkp) and [fastgrin/secp256k1-zkp](https://github.com/fastgrin/secp256k1-zkp).

This `rust-secp256k1-zkp` library forked from [rust-bitcoin/rust-secp256k1](https://github.com/rust-bitcoin/rust-secp256k1). Based on `rust-secp256k1` library, it add the following features for ZKP (Zero Knowledge Proof):
* Pedersen Commitment
* Schnorr Signature
* Bullet Range Proof

### Documents
* [Rustdoc of crate secp256k1](https://docs.rs/secp256k1/0.11.3/secp256k1/)
* [Rustdoc of crate grin_secp256k1zkp](https://docs.rs/grin_secp256k1zkp/0.7.1/secp256k1zkp/)
