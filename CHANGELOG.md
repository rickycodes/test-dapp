# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [5.2.1]
### Uncategorized
- add Release & Publishing section to README.md
- add create-release-pr.yml and publish-release.yml
- revoke NFT allowances ([#187](https://github.com/rickycodes/test-dapp/pull/187))
- Bump eventsource from 1.0.7 to 1.1.2 ([#177](https://github.com/rickycodes/test-dapp/pull/177))
- Bump terser from 4.8.0 to 4.8.1 ([#182](https://github.com/rickycodes/test-dapp/pull/182))
- v5.2.0 ([#185](https://github.com/rickycodes/test-dapp/pull/185))
- v5.1.1 ([#179](https://github.com/rickycodes/test-dapp/pull/179))
- fix version in packagae.json ([#176](https://github.com/rickycodes/test-dapp/pull/176))
- v5.1.0 ([#175](https://github.com/rickycodes/test-dapp/pull/175))
- Bump async from 2.6.3 to 2.6.4 ([#168](https://github.com/rickycodes/test-dapp/pull/168))
- Bump ajv from 6.10.2 to 6.12.6 ([#154](https://github.com/rickycodes/test-dapp/pull/154))
- Bump url-parse from 1.5.3 to 1.5.10 ([#156](https://github.com/rickycodes/test-dapp/pull/156))
- Bump follow-redirects from 1.14.7 to 1.14.9 ([#161](https://github.com/rickycodes/test-dapp/pull/161))
- Bump minimist from 1.2.5 to 1.2.6 ([#158](https://github.com/rickycodes/test-dapp/pull/158))
- v5.0.0 ([#151](https://github.com/rickycodes/test-dapp/pull/151))
- add auto-changelog and create CHANGELOG.md ([#150](https://github.com/rickycodes/test-dapp/pull/150))
- Bump follow-redirects from 1.12.1 to 1.14.7 ([#148](https://github.com/rickycodes/test-dapp/pull/148))
- Add type-0 to legacy transaction ([#126](https://github.com/rickycodes/test-dapp/pull/126))
- Bump tar from 6.1.4 to 6.1.11 ([#123](https://github.com/rickycodes/test-dapp/pull/123))
- Bump url-parse from 1.5.1 to 1.5.3 ([#122](https://github.com/rickycodes/test-dapp/pull/122))
- Bump path-parse from 1.0.6 to 1.0.7 ([#121](https://github.com/rickycodes/test-dapp/pull/121))
- Bump tar from 6.0.2 to 6.1.4 ([#120](https://github.com/rickycodes/test-dapp/pull/120))
- make chainId string in one test for increased type coverage ([#116](https://github.com/rickycodes/test-dapp/pull/116))
- Bump ws from 6.2.1 to 6.2.2 ([#115](https://github.com/rickycodes/test-dapp/pull/115))
- Bump dns-packet from 1.3.1 to 1.3.4 ([#113](https://github.com/rickycodes/test-dapp/pull/113))
- Repo standardization ([#109](https://github.com/rickycodes/test-dapp/pull/109))
- Fix lockfile
- hosted-git-info@2.8.9 ([#108](https://github.com/rickycodes/test-dapp/pull/108))
- Use Node 12 ([#107](https://github.com/rickycodes/test-dapp/pull/107))
- Bump ssri@8.0.0 to 8.0.1 ([#106](https://github.com/rickycodes/test-dapp/pull/106))
- Bump url-parse from 1.4.7 to 1.5.1 ([#105](https://github.com/rickycodes/test-dapp/pull/105))
- Bump lodash from 4.17.19 to 4.17.21 ([#104](https://github.com/rickycodes/test-dapp/pull/104))
- webpack-dev-server@3.11.2 ([#103](https://github.com/rickycodes/test-dapp/pull/103))
- Bump ssri from 6.0.1 to 6.0.2 ([#101](https://github.com/rickycodes/test-dapp/pull/101))
- Bump y18n from 4.0.0 to 4.0.1 ([#99](https://github.com/rickycodes/test-dapp/pull/99))
- Use gh-pages package for deployment ([#98](https://github.com/rickycodes/test-dapp/pull/98))
- Fix deploy script by parameterizing init branch ([#97](https://github.com/rickycodes/test-dapp/pull/97))
- Bump elliptic from 6.5.3 to 6.5.4 ([#96](https://github.com/rickycodes/test-dapp/pull/96))
- Replace 'master' references with 'main' ([#94](https://github.com/rickycodes/test-dapp/pull/94))
- ethers@5.0.32 ([#95](https://github.com/rickycodes/test-dapp/pull/95))
- Fix `remote` option of deploy script ([#91](https://github.com/rickycodes/test-dapp/pull/91))
- Include sourcemaps in bundle ([#89](https://github.com/rickycodes/test-dapp/pull/89))
- Bump ini from 1.3.5 to 1.3.8 ([#88](https://github.com/rickycodes/test-dapp/pull/88))

## [5.2.0]
### Added
- Add NFT contract interaction buttons ([#181](git+https://github.com/MetaMask/test-dapp/pull/181))
- Allow specifying already existing contract address ([#180](git+https://github.com/MetaMask/test-dapp/pull/180))

## [5.1.1]
### Fixed
- Fix RPC info for local Ganache instance ([#178](git+https://github.com/MetaMask/test-dapp/pull/178))

## [5.1.0]
### Added
- Use local Ganache instance for `wallet_addEthereumChain` instead of XDAI ([#174](git+https://github.com/MetaMask/test-dapp/pull/174))

### Fixed
- Fix event used for accessing provider ([#163](git+https://github.com/MetaMask/test-dapp/pull/163))
- fix: replace networkChanged with chainChanged ([#162](git+https://github.com/MetaMask/test-dapp/pull/162))
- wait for the transaction to be mined ([#138](git+https://github.com/MetaMask/test-dapp/pull/138))

## [5.0.0]
### Added
- Add buttons to send transaction and deploy contract that will fail([#139](git+https://github.com/MetaMask/test-dapp/pull/139))
- add deploy and mint buttons for collectibles flow ([#136](git+https://github.com/MetaMask/test-dapp/pull/136))
- Add warning when using Test Dapp on Mainnet ([#134](git+https://github.com/MetaMask/test-dapp/pull/134))
- Add form to send transaction with parameters([#132](git+https://github.com/MetaMask/test-dapp/pull/132))
- Add button to send EIP1559 transaction ([#117](git+https://github.com/MetaMask/test-dapp/pull/117))
- Add button to suggest switching Ethereum chains([#102](git+https://github.com/MetaMask/test-dapp/pull/102))
- Add button to call watch-asset ([#112](git+https://github.com/MetaMask/test-dapp/pull/112))
- Add button to suggest adding Ethereum chain ([#92](git+https://github.com/MetaMask/test-dapp/pull/92))

### Fixed
- Remove known hacked address from send flow. ([#129](git+https://github.com/MetaMask/test-dapp/pull/129))
- Fix decimal unit error in send token flow ([#131](git+https://github.com/MetaMask/test-dapp/pull/131))
- Fix signTypedData_v3 message ([#133](git+https://github.com/MetaMask/test-dapp/pull/133))
- Fix repository standardization issues ([#118](git+https://github.com/MetaMask/test-dapp/pull/118))
- Fix addEthereumChain button disable logic ([#93](git+https://github.com/MetaMask/test-dapp/pull/93))

[Unreleased]: https://github.com/rickycodes/test-dapp/compare/v5.2.1...HEAD
[5.2.1]: https://github.com/rickycodes/test-dapp/compare/v5.2.0...v5.2.1
[5.2.0]: https://github.com/rickycodes/test-dapp/compare/v5.1.1...v5.2.0
[5.1.1]: https://github.com/rickycodes/test-dapp/compare/v5.1.0...v5.1.1
[5.1.0]: https://github.com/rickycodes/test-dapp/compare/v5.0.0...v5.1.0
[5.0.0]: https://github.com/rickycodes/test-dapp/releases/tag/v5.0.0
