# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.9.1](https://github.com/cssninjaStudio/bulma-css-vars/compare/v0.9.0...v0.9.1) (2023-01-02)


### Bug Fixes

* **cli:** allow to load cjs file, and force cjs for cli for node 18+ ([e7fa9a0](https://github.com/cssninjaStudio/bulma-css-vars/commit/e7fa9a044aab5243ff76128cf9180fe7874d403c))

## 0.9.0 (2023-01-02)


### ⚠ BREAKING CHANGES

* **lib:** Possible issues with backwards compatibility for bulma
lower than v0.9.2.

Adds support to bulma v0.9.2 by copying and addjusting derived-variables
from bulma.
This might create issues with backwards compatibility, which is why this
is a new major version.

### Features

* add bulma-css-vars ([e4a5c27](https://github.com/cssninjaStudio/bulma-css-vars/commit/e4a5c27b642726c1651c1e9f9d1fb8c8b82890fd))
* add direct web usage option ([0b56e57](https://github.com/cssninjaStudio/bulma-css-vars/commit/0b56e572fef4dc7e1b465af59ca467c362c0e7be))
* add fallback css for variables ([b3739bc](https://github.com/cssninjaStudio/bulma-css-vars/commit/b3739bc9ace5ceda6c06ef35a0f0a36978fe4ae7))
* **build:** add bundle to dist, add bin ([1abc124](https://github.com/cssninjaStudio/bulma-css-vars/commit/1abc12486aa8987c7b520c0df1bf0226a17b5198))
* cli init command (--init) ([7e06677](https://github.com/cssninjaStudio/bulma-css-vars/commit/7e06677dc325b61abeb1b59c5f08b44bb9c3ff82))
* compatibility with bulma v0.9 ([#14](https://github.com/cssninjaStudio/bulma-css-vars/issues/14)) ([c573369](https://github.com/cssninjaStudio/bulma-css-vars/commit/c5733691fbe837d7fae036e085146caf4761168d))
* generate transitions for smooth var udpates ([85ac057](https://github.com/cssninjaStudio/bulma-css-vars/commit/85ac057f6ec12b50bebb13951daa1fe8627605bd))
* **lib:** add esm build ([892baa8](https://github.com/cssninjaStudio/bulma-css-vars/commit/892baa8dad6c5082367159c2605853d6a7973b51))
* **lib:** support bulma v0.9.2 ([e6cb7bc](https://github.com/cssninjaStudio/bulma-css-vars/commit/e6cb7bc1d815e38e63fb2ce980ddc391e5a1346d))
* **lib:** support bulma v0.9.3 ([7d69403](https://github.com/cssninjaStudio/bulma-css-vars/commit/7d69403846e3acccd5c6aec20b5c3cae3f072d63))


### Bug Fixes

* add better diagnostics output on errors ([3625edf](https://github.com/cssninjaStudio/bulma-css-vars/commit/3625edffb9ad4ba842f740c066747611b341c19a))
* add sass files to npm publish ([c13517f](https://github.com/cssninjaStudio/bulma-css-vars/commit/c13517f07fc62a14660bf115f29aadd176986cae))
* **cli:** change jsOutputContent's exports to match docs ([#6](https://github.com/cssninjaStudio/bulma-css-vars/issues/6)) ([8ccac88](https://github.com/cssninjaStudio/bulma-css-vars/commit/8ccac8848c07e5ca0556bb092c314a8288afe255)), closes [#3](https://github.com/cssninjaStudio/bulma-css-vars/issues/3)
* compatibility with bulma v0.9.2 ([7b47443](https://github.com/cssninjaStudio/bulma-css-vars/commit/7b474435ac9d578b6615824c427679b86839be2f))
* ignore comment type declarations in post processor ([#8](https://github.com/cssninjaStudio/bulma-css-vars/issues/8)) ([65b6cd9](https://github.com/cssninjaStudio/bulma-css-vars/commit/65b6cd92982fa6060bbfc7135cd425ef56b3c44e))
* **lib:** support rgba with four args ([0ff588e](https://github.com/cssninjaStudio/bulma-css-vars/commit/0ff588e19f9903064bf4c8b309e409070916518e))
* **typscript:** update ColorFnCall typings ([#198](https://github.com/cssninjaStudio/bulma-css-vars/issues/198)) ([7bfe1bf](https://github.com/cssninjaStudio/bulma-css-vars/commit/7bfe1bf07e6a7934d5d4081f108ac693fe935632))
* use dist/index for browser pkg.json ([17fb49f](https://github.com/cssninjaStudio/bulma-css-vars/commit/17fb49fe7cfa6153d83a2a2ec0c3d2758f3bc657))
* use right sass variable in fallback rgba fn ([e497b1e](https://github.com/cssninjaStudio/bulma-css-vars/commit/e497b1eaf420e9e43aa1c7863d50947294db61f8))
* workaround for bulma functions ([bb7d221](https://github.com/cssninjaStudio/bulma-css-vars/commit/bb7d2215dd824e7464df7777694e1e9407e7c505))
