# Changelog

## v0.6.3 FINAL RELEASE

- The maintenance status was set to "deprecated" in `Cargo.toml`.

## v0.6.2

- The maintenance status was set to "as-is" in `Cargo.toml`.

## v0.6.1

- All development has moved to [yaml-rust2](https://github.com/Ethiraric/yaml-rust2).
  `yaml-rust-davvid` has been merged into `yaml-rust2` and will not have any
  further releases.

## v0.6.0

**Features**:

- Error messages now contain a byte offset to aid debugging.
  ([#176](https://github.com/chyh1990/yaml-rust/pull/176))

- Yaml now has `or` and `borrowed_or` methods.
  ([#179](https://github.com/chyh1990/yaml-rust/pull/179))

- The `info` field has been exposed via a new `Yaml::info()` API method.
  ([#190](https://github.com/chyh1990/yaml-rust/pull/190))

- `Yaml::load_from_bytes()` is now available.
  ([#156](https://github.com/chyh1990/yaml-rust/pull/156))

- The parser now supports tag directives.
  ([#135](https://github.com/chyh1990/yaml-rust/pull/135)
  ([#35](https://github.com/chyh1990/yaml-rust/issues/35)

**Development**:

- The documentation was updated to include a security note mentioning that
  yaml-rust is safe because it does not interpret types.
  ([#195](https://github.com/chyh1990/yaml-rust/pull/195))

- Updated to quickcheck 1.0.
  ([#188](https://github.com/chyh1990/yaml-rust/pull/188))


## v0.5.2

**Development**:

- `hashlink` is [now used](https://github.com/chyh1990/yaml-rust/pull/157)
  instead of `linked_hash_map`.


## v0.5.1

**Features**:

- Multi-line strings are now [emitted using block scalars](https://github.com/chyh1990/yaml-rust/pull/136).
