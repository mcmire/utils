# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [7.0.0]
### Uncategorized
- Bump semver from 7.3.8 to 7.5.2 ([#110](https://github.com/mcmire/utils/pull/110))
- 6.1.0 ([#109](https://github.com/mcmire/utils/pull/109))
- 6.0.1 ([#106](https://github.com/mcmire/utils/pull/106))
- 6.0.0 ([#104](https://github.com/mcmire/utils/pull/104))
- 5.0.2 ([#101](https://github.com/mcmire/utils/pull/101))
- 5.0.1 ([#97](https://github.com/mcmire/utils/pull/97))
- Use PAT for publishing docs ([#96](https://github.com/mcmire/utils/pull/96))
- Update GitHub Actions to match module template ([#95](https://github.com/mcmire/utils/pull/95))
- 5.0.0 ([#93](https://github.com/mcmire/utils/pull/93))
- Bump `peaceiris/actions-gh-pages` to more recent version ([#88](https://github.com/mcmire/utils/pull/88))
- 4.0.0 ([#87](https://github.com/mcmire/utils/pull/87))
- 3.6.0 ([#84](https://github.com/mcmire/utils/pull/84))
- 3.5.0 ([#83](https://github.com/mcmire/utils/pull/83))
- Revert "BREAKING: Handle `toJSON` in JSON validation and sizing (#52)" ([#52](https://github.com/mcmire/utils/pull/52))
- Add tests for misc types and type guards ([#78](https://github.com/mcmire/utils/pull/78))
- Bump json5 from 1.0.1 to 1.0.2 ([#77](https://github.com/mcmire/utils/pull/77))
- Bump http-cache-semantics from 4.1.0 to 4.1.1 ([#76](https://github.com/mcmire/utils/pull/76))
- BREAKING: Handle `toJSON` in JSON validation and sizing ([#52](https://github.com/mcmire/utils/pull/52))
- 3.4.1 ([#72](https://github.com/mcmire/utils/pull/72))
- 3.4.0 ([#70](https://github.com/mcmire/utils/pull/70))
- Bump @metamask/eslint-config-jest from 11.0.0 to 11.1.0 ([#66](https://github.com/mcmire/utils/pull/66))
- Bump @metamask/eslint-config-typescript from 11.0.2 to 11.1.0 ([#65](https://github.com/mcmire/utils/pull/65))
- Bump @metamask/eslint-config-nodejs from 11.0.1 to 11.1.0 ([#64](https://github.com/mcmire/utils/pull/64))
- Bump @metamask/eslint-config from 11.0.2 to 11.1.0 ([#63](https://github.com/mcmire/utils/pull/63))
- Bump @metamask/eslint-config from 11.0.1 to 11.0.2 ([#61](https://github.com/mcmire/utils/pull/61))
- Bump @metamask/eslint-config-typescript from 11.0.0 to 11.0.2 ([#62](https://github.com/mcmire/utils/pull/62))
- Bump ESLint configs and related dependencies ([#60](https://github.com/mcmire/utils/pull/60))
- Use latest workflow from module template ([#48](https://github.com/mcmire/utils/pull/48))
- 3.3.1 ([#53](https://github.com/mcmire/utils/pull/53))
- 3.3.0 ([#50](https://github.com/mcmire/utils/pull/50))
- 3.2.0 ([#44](https://github.com/mcmire/utils/pull/44))
- Add tests for `Json` and `Hex` type ([#42](https://github.com/mcmire/utils/pull/42))
- 3.1.0 ([#37](https://github.com/mcmire/utils/pull/37))
- Bump Yarn to v3 and patch jest-worker ([#36](https://github.com/mcmire/utils/pull/36))
- 3.0.3 ([#30](https://github.com/mcmire/utils/pull/30))
- 3.0.2 ([#27](https://github.com/mcmire/utils/pull/27))
- 3.0.1 ([#24](https://github.com/mcmire/utils/pull/24))
- 3.0.0 ([#22](https://github.com/mcmire/utils/pull/22))
- Upgrade TypeScript to 4.7 ([#21](https://github.com/mcmire/utils/pull/21))
- 2.1.0 ([#15](https://github.com/mcmire/utils/pull/15))
- Bump @metamask/auto-changelog from 2.6.0 to 2.6.1 ([#13](https://github.com/mcmire/utils/pull/13))
- Bump @metamask/auto-changelog from 2.5.0 to 2.6.0 ([#12](https://github.com/mcmire/utils/pull/12))
- 2.0.0 ([#11](https://github.com/mcmire/utils/pull/11))
- Fix link to API docs in README ([#10](https://github.com/mcmire/utils/pull/10))
- 1.0.0 ([#6](https://github.com/mcmire/utils/pull/6))
- Add automated API docs generation and publishing ([#7](https://github.com/mcmire/utils/pull/7))
- Initial implementation ([#3](https://github.com/mcmire/utils/pull/3))
- Rename package ([#1](https://github.com/mcmire/utils/pull/1))
- Initial commit

## [6.1.0]
### Added
- Add optional `destroy` method to `Keyring` type ([#108](https://github.com/MetaMask/utils/pull/108))

## [6.0.1]
### Fixed
- Strip `__proto__` and `constructor` JSON properties in `getSafeJson` ([#105](https://github.com/MetaMask/utils/pull/105))

## [6.0.0]
### Changed
- **BREAKING:** Bump minimum Node version to 16 ([#102](https://github.com/MetaMask/utils/pull/102))
- **BREAKING:** Target `ES2020` ([#102](https://github.com/MetaMask/utils/pull/102))

### Fixed
- Fix JSON validation security issue ([#103](https://github.com/MetaMask/utils/pull/103))
  - This adds a new function `getSafeJson` which validates and returns sanitized JSON.

## [5.0.2]
### Changed
- The `Keyring` exposes a new optional method `init` ([#99](https://github.com/MetaMask/utils/pull/99))

### Fixed
- Bump `@ethereumjs/tx` to `4.1.2` to address runtime compatibility issues ([#100](https://github.com/MetaMask/utils/pull/100))

## [5.0.1]
### Fixed
- Keep original type when using `hasProperty` if defined ([#94](https://github.com/MetaMask/utils/pull/94))

## [5.0.0]
### Changed
- **BREAKING:** Update `Keyring` type ([#89](https://github.com/MetaMask/utils/pull/89))
  - The `Keyring` class now uses the data types `TypedTransaction` and `TxData` from `@ethereumjs/tx` (`v4.1.1`).
  - The `Keyring` now exposes a new optional method called `generateRandomMnemonic`.

## [4.0.0]
### Changed
- Export new modules (`keyring`, `transaction-types`, and `encryption-types`) ([#86](https://github.com/MetaMask/utils/pull/86))
- **BREAKING:** Improve JSON validation ([#85](https://github.com/MetaMask/utils/pull/85))
  - Fixes edge cases in our JSON validation logic.
  - The previous function used for JSON validation (`validateJsonAndGetSize`) was removed.
    - The `isValidJson` function now uses the new JSON validation logic.
    - To get the size of a JSON value, you can use the `getJsonSize` function.

## [3.6.0]
### Added
- Add `Keyring` types ([#74](https://github.com/MetaMask/utils/pull/74))
  -  New data types added. These are `Keyring`, `Transaction` (`LegacyTransaction`, `EIP2930Transaction`, `EIP1559Transaction`), `SignedTransaction`, `Signature`, and `Eip1024EncryptedData`.

## [3.5.0]
### Changed
- Improve the `hasProperty` function ([#79](https://github.com/MetaMask/utils/pull/79), [#80](https://github.com/MetaMask/utils/pull/80))
  - This function now acts as a type guard, informing TypeScript that the property exists.
  - The function is now compatible with more types of objects, such as Errors and class instances.

## [3.4.1]
### Fixed
- Bump `superstruct` to `^1.0.3` ([#71](https://github.com/MetaMask/utils/pull/71))

## [3.4.0]
### Added
- Add types and utility functions for validating versions and checksums ([#67](https://github.com/MetaMask/utils/pull/67), [#69](https://github.com/MetaMask/utils/pull/69))

### Fixed
- JSON-RPC types now have a default generic `Params` value ([#54](https://github.com/MetaMask/utils/pull/54))

## [3.3.1]
### Fixed
- JSON-RPC parameters are now properly cast to Json upon validation ([#51](https://github.com/MetaMask/utils/pull/51))

## [3.3.0]
### Added
- Add more assertion utils ([#49](https://github.com/MetaMask/utils/pull/49))
- Add JSON-RPC error validation functions ([#46](https://github.com/MetaMask/utils/pull/46))
- Add convenience function for creating a `DataView` ([#45](https://github.com/MetaMask/utils/pull/45))

### Fixed
- Update JSON validation logic ([#47](https://github.com/MetaMask/utils/pull/47))
  - Validation would previously allow for `undefined` values, which is not a standard JSON type

## [3.2.0]
### Added
- Add `PendingJsonRpcResponse` type ([#43](https://github.com/MetaMask/utils/pull/43))
- Add utils for converting between numbers and hex ([#41](https://github.com/MetaMask/utils/pull/41))
- Add coercion utils ([#38](https://github.com/MetaMask/utils/pull/38))

## [3.1.0]
### Added
- Add assertion utils ([#33](https://github.com/MetaMask/utils/pull/33))
- Add util functions for encoding and decoding bytes ([#34](https://github.com/MetaMask/utils/pull/34))

### Fixed
- Make JSON-RPC error `data` property optional ([#31](https://github.com/MetaMask/utils/pull/31))
- Don't include test files in dist folder ([#35](https://github.com/MetaMask/utils/pull/35))
- Fix typo in README ([#28](https://github.com/MetaMask/utils/pull/28))

## [3.0.3]
### Fixed
- Allow omitting JSON-RPC params when params can be undefined ([#29](https://github.com/MetaMask/utils/pull/29))

## [3.0.2]
### Fixed
- Bump `superstruct` to ^0.16.5 ([#26](https://github.com/MetaMask/utils/pull/26))
  - `superstruct`s 0.16.1 through 0.16.4 were not compatible with Node 14; this restores that compatibility.

## [3.0.1]
### Fixed
- Promote `@types/debug` from development dependencies to production dependencies ([#23](https://github.com/MetaMask/utils/pull/23))

## [3.0.0]
### Added
- Add logging functions ([#20](https://github.com/MetaMask/utils/pull/20))
- Add frozen collections (implemented in [#5](https://github.com/MetaMask/utils/pull/5) but exported in [#19](https://github.com/MetaMask/utils/pull/19))

### Changed
- **BREAKING:** Improve types and type validation ([#19](https://github.com/MetaMask/utils/pull/19))
  - Various type changes have been made that might be breaking:
    - The `JsonRpcRequest` and `JsonRpcNotification` types now include a generic constraint requiring that the `Params` type extends the `JsonRpcParams` type.
    - The `JsonRpcSuccess` and `JsonRpcResponse` types now include a generic contraint for the `Result` type, requiring that it extends the `Json` type.
    - Various validation functions now accept `unknown` parameters rather than specific types. This should not be breaking except that it may affect type inference for the parameters passed in.
  - New JSON-related functions have been added:
    - `assertIsJsonRpcResponse`
    - `isJsonRpcResponse`
    - `InferWithParams`
    - `JsonRpcParams`
  - New JSON Struct types have been added:
    - `JsonRpcErrorStruct`
    - `JsonRpcFailureStruct`
    - `JsonRpcIdStruct`
    - `JsonRpcParamsStruct`
    - `JsonRpcRequestStruct`
    - `JsonRpcResponseStruct`
    - `JsonRpcSuccessStruct`
    - `JsonRpcVersionStruct`
    - `JsonStruct`

## [2.1.0]
### Added
- Add JSON storage validation and limit utilities ([#14](https://github.com/MetaMask/utils/pull/14))
  - Adds a new function `validateJsonAndGetSize`.

## [2.0.0]
### Added
- Add more JSON utils ([#8](https://github.com/MetaMask/utils/pull/8))

### Changed
- **BREAKING:** Refactor and expand time utils ([#9](https://github.com/MetaMask/utils/pull/9))
  - Adds a new function, `inMilliseconds`, and moves the time constants into a TypeScript `enum`.

## [1.0.0]
### Added
- Initial release

[Unreleased]: https://github.com/mcmire/utils/compare/v7.0.0...HEAD
[7.0.0]: https://github.com/mcmire/utils/compare/v6.1.0...v7.0.0
[6.1.0]: https://github.com/mcmire/utils/compare/v6.0.1...v6.1.0
[6.0.1]: https://github.com/mcmire/utils/compare/v6.0.0...v6.0.1
[6.0.0]: https://github.com/mcmire/utils/compare/v5.0.2...v6.0.0
[5.0.2]: https://github.com/mcmire/utils/compare/v5.0.1...v5.0.2
[5.0.1]: https://github.com/mcmire/utils/compare/v5.0.0...v5.0.1
[5.0.0]: https://github.com/mcmire/utils/compare/v4.0.0...v5.0.0
[4.0.0]: https://github.com/mcmire/utils/compare/v3.6.0...v4.0.0
[3.6.0]: https://github.com/mcmire/utils/compare/v3.5.0...v3.6.0
[3.5.0]: https://github.com/mcmire/utils/compare/v3.4.1...v3.5.0
[3.4.1]: https://github.com/mcmire/utils/compare/v3.4.0...v3.4.1
[3.4.0]: https://github.com/mcmire/utils/compare/v3.3.1...v3.4.0
[3.3.1]: https://github.com/mcmire/utils/compare/v3.3.0...v3.3.1
[3.3.0]: https://github.com/mcmire/utils/compare/v3.2.0...v3.3.0
[3.2.0]: https://github.com/mcmire/utils/compare/v3.1.0...v3.2.0
[3.1.0]: https://github.com/mcmire/utils/compare/v3.0.3...v3.1.0
[3.0.3]: https://github.com/mcmire/utils/compare/v3.0.2...v3.0.3
[3.0.2]: https://github.com/mcmire/utils/compare/v3.0.1...v3.0.2
[3.0.1]: https://github.com/mcmire/utils/compare/v3.0.0...v3.0.1
[3.0.0]: https://github.com/mcmire/utils/compare/v2.1.0...v3.0.0
[2.1.0]: https://github.com/mcmire/utils/compare/v2.0.0...v2.1.0
[2.0.0]: https://github.com/mcmire/utils/compare/v1.0.0...v2.0.0
[1.0.0]: https://github.com/mcmire/utils/releases/tag/v1.0.0
