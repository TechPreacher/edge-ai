# Changelog

## [2.9.0](https://github.com/microsoft/edge-ai/compare/v2.8.0...v2.9.0) (2026-05-08)


### ✨ Features

* **500-application:** add 514-wasm-msg-to-dss WASM map operator with DSS enrichment pattern ([#356](https://github.com/microsoft/edge-ai/issues/356)) ([db882a5](https://github.com/microsoft/edge-ai/commit/db882a572928e47df9c7a8d0bbf952d1dfb0c7fe))
* add unit tests for application services (Rust + Python) ([#372](https://github.com/microsoft/edge-ai/issues/372)) ([220ab28](https://github.com/microsoft/edge-ai/commit/220ab2895d503fe5fd1d2221a612a37e4756abea))
* **avro-to-json:** add unit tests for wire format config parsing ([#368](https://github.com/microsoft/edge-ai/issues/368)) ([65bc924](https://github.com/microsoft/edge-ai/commit/65bc9247b76bb881a7c4663ba0d368b30623a03c))
* **build:** add multi-language fuzzing infra (CFLite + Codecov flags) ([#453](https://github.com/microsoft/edge-ai/issues/453)) ([7407230](https://github.com/microsoft/edge-ai/commit/7407230cb18238ce143cfbf7531032160bf9651e))
* **ci:** enforce rust crate registration in codecov coverage ([#155](https://github.com/microsoft/edge-ai/issues/155)) ([#449](https://github.com/microsoft/edge-ai/issues/449)) ([9b33d69](https://github.com/microsoft/edge-ai/commit/9b33d69fdf39cf4c77eb95453048977b30b46462))
* **docs:** migrate from Docsify to Docusaurus ([#399](https://github.com/microsoft/edge-ai/issues/399)) ([ca06002](https://github.com/microsoft/edge-ai/commit/ca060022c4a2a81dda97d488bbc56e9baa0d1c91))
* **iot-ops:** upgrade AIO 2604 release (1.3.70), harden schema-registry RBAC ([#471](https://github.com/microsoft/edge-ai/issues/471)) ([e772b74](https://github.com/microsoft/edge-ai/commit/e772b74a968efdfa76854383886ca61fa9eb273f))


### 🐛 Bug Fixes

* **ai-edge-inference:** bump notify 7 to 8 (partial RUSTSEC-2024-0384) ([#469](https://github.com/microsoft/edge-ai/issues/469)) ([f548586](https://github.com/microsoft/edge-ai/commit/f548586af63f42f138541a4bdb0531b8c524f56c))
* **build:** pin all dependencies for OSSF Scorecard ([#402](https://github.com/microsoft/edge-ai/issues/402)) ([79e6971](https://github.com/microsoft/edge-ai/commit/79e6971628287bce6439a6459445ab715ba17a87))
* **build:** resolve all 4 main branch CI lint failures ([#365](https://github.com/microsoft/edge-ai/issues/365)) ([f90ad6f](https://github.com/microsoft/edge-ai/commit/f90ad6f2815ba05d90fad1e632d812385c9ba972))
* **build:** use valid 'rust' cataloger tag for Syft v1.42.3+ ([#423](https://github.com/microsoft/edge-ai/issues/423)) ([f168e56](https://github.com/microsoft/edge-ai/commit/f168e56a9477fb8f05a73a4fdd8355af842e8982))
* **deps:** bump openssl to 0.10.79 across remaining Rust services ([#480](https://github.com/microsoft/edge-ai/issues/480)) ([14e6f16](https://github.com/microsoft/edge-ai/commit/14e6f16c767e907d9ef313756d1c557083805696))
* **docs:** remove ignoreDeprecations in tsconfig.json ([#488](https://github.com/microsoft/edge-ai/issues/488)) ([1b4af53](https://github.com/microsoft/edge-ai/commit/1b4af53d9a35d9f9c14ec152041d98eb65fd5d9f))
* **docs:** silence TS5101 baseUrl deprecation in docusaurus tsconfig ([#475](https://github.com/microsoft/edge-ai/issues/475)) ([ff9d53f](https://github.com/microsoft/edge-ai/commit/ff9d53f86da41a979b714f9918f3867339b3a348))
* **scripts:** align Grype writer/reader naming so security gate fails closed ([#362](https://github.com/microsoft/edge-ai/issues/362)) ([#411](https://github.com/microsoft/edge-ai/issues/411)) ([64b3db3](https://github.com/microsoft/edge-ai/commit/64b3db30c81e2cc01ea775946fdd5e59d0844a26))
* **workflows:** harden CI workflows to fail-fast on lint, security, and doc-gen errors ([#393](https://github.com/microsoft/edge-ai/issues/393)) ([4669835](https://github.com/microsoft/edge-ai/commit/4669835bc57f7862b99c61388472754045a7b8e5))


### 📚 Documentation

* add OpenSSF Scorecard badge to README ([#371](https://github.com/microsoft/edge-ai/issues/371)) ([917851b](https://github.com/microsoft/edge-ai/commit/917851bc5a3db1136490f5d61d126c7f872ab3b1))
