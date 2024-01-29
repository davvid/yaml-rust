# Changelog

## v0.6.0

**Features**:

- Error messages now contain a byte offset to aid debugging.
  ([#176](https://github.com/chyh1990/yaml-rust/pull/176))

- Yaml now has `or` and `borrowed_or` methods.
  ([#179](https://github.com/chyh1990/yaml-rust/pull/179))

- The `info` field has been expoed via a new `Yaml::info()` API method.
  ([#190](https://github.com/chyh1990/yaml-rust/pull/190))

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
