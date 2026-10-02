# hatter-owner-contracts

Identify an owner process consistently across startup, observation and restart.

## What you can do

- Validate owner reference, incarnation, protocol generation and executable identity.
- Distinguish process life, transport, readiness and dispatch state.

## Current scope

PID alone is not process identity. These contracts do not start processes or authorize replay of a domain command.

Package distribution is not activated by this documentation. Use the checked-in source and the declared dependency versions; published availability must be verified separately.

## Getting started

Install Rust 1.97.0 or newer and make the declared dependencies available. Use the configured private registry when a dependency is not distributed publicly. Run from this repository:

```sh
cargo test --locked
```

## Documentation and source

[Usage guide](docs/getting-started.md)

[Implementation and public interfaces](src) · [Contributing](CONTRIBUTING.md) · [Security reporting](SECURITY.md) · [License](LICENSE) · [Attribution notices](NOTICE)
