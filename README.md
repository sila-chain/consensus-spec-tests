# Sila Proof-of-Stake Consensus Spec Tests

> [!IMPORTANT]
> This repository is **retired** and preserved only as a historical snapshot.
>
> The active authority for Sila consensus specifications and generated reference tests is
> [`sila-chain/consensus-specs`](https://github.com/sila-chain/consensus-specs).
> Current reference-test generation, sharded GitHub-hosted validation, nightly artifacts,
> and release publication are maintained there. No new Sila consensus test-vector work
> should be based on this repository.

## Historical context

This repository contains historical test vectors for the Sila [Proof-of-Stake Consensus Spec](https://github.com/sila-chain/consensus-specs).
Other types of testing (network, fuzzing, benchmarking, etc.) are currently a work in progress, and will be hosted in separate repositories.
The intention of this repository was to provide a solid base for Sila proof-of-stake clients (aka "beacon nodes") to consume as part of their unit-testing efforts around spec behavior.

The tests are YAML files following the [general testing format](https://github.com/sila-chain/consensus-specs/tree/main/tests/formats).

The generators responsible for current spec tests are maintained in [sila-chain/consensus-specs](https://github.com/sila-chain/consensus-specs/tree/main/tests/generators).

New or updated tests belong in the active consensus specifications repository rather than this retired snapshot.

The YAML test-vectors in this historical repository are tracked using [Git LFS](https://git-lfs.github.com/) to accommodate large test vectors.

## License

See [LICENSE](./LICENSE) file.
