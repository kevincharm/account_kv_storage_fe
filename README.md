# Account KV Storage

Store a Merkleised state of any kind of data for the entire set of Ethereum addresses efficiently! This KV storage is backed by a sparse Merkle tree, which has a depth of 160. An Ethereum address is interpreted as a number and used as the index for each leaf. In addition to membership proofs as in regular Merkle teres, it's also possible to prove non-membership!

## Dependencies

Use `git clone --recurse-submodules` when cloning, as there are vendored dependencies:

- [smt_fe](https://github.com/kevincharm/smt_fe): Sparse Merkle Tree library
