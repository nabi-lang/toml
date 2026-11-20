# Changelog

All notable changes to this package. Versions follow semver, independent of the Nabi toolchain.

## 0.1.0 (unreleased)

First release.

- TOML 1.1.0 parser (`parse`) with `line:col` errors; `Version::V1_0` reads
  strictly as 1.0.
- `Value` tree with typed `Date`, `Time` and `Datetime`.
- Writer that lays documents out as people write them.
- Typed conversion with `#[derive(Toml)]` and the `ToToml` / `FromToml`
  traits: `from_str`, `to_str`, `to_value`, `from_value`, as in std's
  `nabion` module.
- Tested against toml-test. Needs Nabi 0.1 or later.
