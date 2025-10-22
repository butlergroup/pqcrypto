[![CodeQL](https://github.com/butlergroup/pqcrypto/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/butlergroup/pqcrypto/actions/workflows/github-code-scanning/codeql)
[![Rust](https://github.com/butlergroup/pqcrypto/actions/workflows/ci.yml/badge.svg)](https://github.com/butlergroup/pqcrypto/actions/workflows/ci.yml)
[![Snyk Security-Monitored](https://img.shields.io/badge/Snyk%20Security-Monitored-purple)](https://app.snyk.io/share/784f6fef-6aaf-47ed-81ba-99e05b854665)
[![dependency status](https://deps.rs/repo/github/rustpq/pqcrypto/status.svg)](https://deps.rs/repo/github/rustpq/pqcrypto)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/11339/badge)](https://www.bestpractices.dev/projects/11339)
[![Scorecard supply-chain security](https://github.com/butlergroup/pqcrypto/actions/workflows/scorecard.yml/badge.svg)](https://github.com/butlergroup/pqcrypto/actions/workflows/scorecard.yml)
[![Microsoft Defender For Devops](https://github.com/butlergroup/pqcrypto/actions/workflows/defender-for-devops.yml/badge.svg)](https://github.com/butlergroup/pqcrypto/actions/workflows/defender-for-devops.yml)
[![Coverage Status](https://coveralls.io/repos/github/butlergroup/pqcrypto/badge.svg?branch=main)](https://coveralls.io/github/butlergroup/pqcrypto?branch=main)
[![Feature Requests](https://img.shields.io/github/issues/butlergroup/pqcrypto/feature-request.svg)](https://github.com/butlergroup/pqcrypto/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement)
[![Bugs](https://img.shields.io/github/issues/butlergroup/pqcrypto/bug.svg)](https://github.com/butlergroup/pqcrypto/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3Abug)

# Bindings to quantum-safe cryptographic libraries

This repository contains bindings to C implementations of cryptographic algorithms part of the [NIST competition][nist].
These bindings are generated based on the [PQClean][pqclean] project, which aims to collect 'clean' implementations of cryptographic algorithms.

## How to generate the bindings

The `pqcrypto-templates` folder contains the master copies of the Rust files.
The binding libraries are generated from the PQClean meta files and PQClean specified API.
The file `implementations.yaml` controls the version numbers and included variants of each scheme.
The generation of the different pq-crates is done by the `generate-implementation.py` script.

## Documentation

See the [documentation of the master project on docs.rs][docsrs].

[nist]: https://nist.gov/pqcrypto
[pqclean]: https://github.com/pqclean/pqclean/
[docsrs]: https://docs.rs/pqcrypto/

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=butlergroup/pqcrypto&type=Date)](https://www.star-history.com/#butlergroup/pqcrypto&Date)
