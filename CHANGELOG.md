# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.0.0-rc.2](https://github.com/nuxt/vue-meta/compare/v2.0.0-rc.1...v2.0.0-rc.2) (2019-06-06)


### Bug Fixes

* detect and apply changes triggered before or during initialization ([#377](https://github.com/nuxt/vue-meta/issues/377)) ([34c6ad9](https://github.com/nuxt/vue-meta/commit/34c6ad9))


### Features

* add basic support for multiple apps on one page ([#373](https://github.com/nuxt/vue-meta/issues/373)) ([024e7c5](https://github.com/nuxt/vue-meta/commit/024e7c5))



# [2.0.0-rc.1](https://github.com/nuxt/vue-meta/compare/v2.0.0-rc.0...v2.0.0-rc.1) (2019-04-23)


### Bug Fixes

* move addNavGuards check to mounted hook ([e80643b](https://github.com/nuxt/vue-meta/commit/e80643b)), closes [#348](https://github.com/nuxt/vue-meta/issues/348)
* use timers instead of requestAnimationFrame ([c040de7](https://github.com/nuxt/vue-meta/commit/c040de7)), closes [#313](https://github.com/nuxt/vue-meta/issues/313)



# [2.0.0-rc.0](https://github.com/nuxt/vue-meta/compare/v1.6.0...v2.0.0-rc.0) (2019-04-20)


### Bug Fixes

* add afterNavigation type ([722786d](https://github.com/nuxt/vue-meta/commit/722786d))
* add inject stub for browser build ([02e4094](https://github.com/nuxt/vue-meta/commit/02e4094))
* add ts type for refresh once ([5935cf3](https://github.com/nuxt/vue-meta/commit/5935cf3))
* afterNavigation logic (its never set in options) ([4a8f975](https://github.com/nuxt/vue-meta/commit/4a8f975))
* also render boolean attributes correctly for tags ([66e4fb4](https://github.com/nuxt/vue-meta/commit/66e4fb4))
* another inline array to const ([78f2c46](https://github.com/nuxt/vue-meta/commit/78f2c46))
* dev env name ([502c89e](https://github.com/nuxt/vue-meta/commit/502c89e))
* dont call changed with explicit this ([5ad6711](https://github.com/nuxt/vue-meta/commit/5ad6711))
* dont inline typeof definitions ([5031acf](https://github.com/nuxt/vue-meta/commit/5031acf))
* dont updateTags when the new info is not an array ([12c7949](https://github.com/nuxt/vue-meta/commit/12c7949))
* dont use object.assign/spread ([d717dbf](https://github.com/nuxt/vue-meta/commit/d717dbf))
* fix cjs build (for now) by adding var window ([95c138e](https://github.com/nuxt/vue-meta/commit/95c138e))
* ignore cssText for coverage ([e3fd8ab](https://github.com/nuxt/vue-meta/commit/e3fd8ab))
* ignore data when its not an object (fixes: [#253](https://github.com/nuxt/vue-meta/issues/253), [#279](https://github.com/nuxt/vue-meta/issues/279), [#297](https://github.com/nuxt/vue-meta/issues/297)) ([7615f41](https://github.com/nuxt/vue-meta/commit/7615f41))
* ignore package-lock not yarn.lock ([164cd8e](https://github.com/nuxt/vue-meta/commit/164cd8e))
* implement simply array polyfills (fixes [#328](https://github.com/nuxt/vue-meta/issues/328)) ([d38f81e](https://github.com/nuxt/vue-meta/commit/d38f81e))
* move rollup config and case fix ([76632ad](https://github.com/nuxt/vue-meta/commit/76632ad))
* one less thing to review ([bf864f6](https://github.com/nuxt/vue-meta/commit/bf864f6))
* only add navguards when refreshOnceOnNav is false ([93f021b](https://github.com/nuxt/vue-meta/commit/93f021b))
* prefer filter over slice ([82ba8c0](https://github.com/nuxt/vue-meta/commit/82ba8c0))
* prefer for..in instead keys.forEach ([6741897](https://github.com/nuxt/vue-meta/commit/6741897))
* prefer includes over indexOf ([6bbcf74](https://github.com/nuxt/vue-meta/commit/6bbcf74))
* remove leaked poc dependencies ([0dada3d](https://github.com/nuxt/vue-meta/commit/0dada3d))
* remove only descriptors ([c08e461](https://github.com/nuxt/vue-meta/commit/c08e461))
* rollup paths ([bfbd181](https://github.com/nuxt/vue-meta/commit/bfbd181))
* trigger meta refresh on page load (fixes [#283](https://github.com/nuxt/vue-meta/issues/283)) ([b824a27](https://github.com/nuxt/vue-meta/commit/b824a27))
* typo ([3631526](https://github.com/nuxt/vue-meta/commit/3631526))
* use Array.from ([f9604c0](https://github.com/nuxt/vue-meta/commit/f9604c0))
* use const arrays ([288871f](https://github.com/nuxt/vue-meta/commit/288871f))
* use correct var ([1e6c5b9](https://github.com/nuxt/vue-meta/commit/1e6c5b9))
* use single object prop on ([9c80dab](https://github.com/nuxt/vue-meta/commit/9c80dab))
* use undefined as child ignore indicator ([104113a](https://github.com/nuxt/vue-meta/commit/104113a))


### Features

* add afterNavigation callback (fix: [#259](https://github.com/nuxt/vue-meta/issues/259)) ([97badf6](https://github.com/nuxt/vue-meta/commit/97badf6))
* add amp as boolean attribute (resolves: [#311](https://github.com/nuxt/vue-meta/issues/311)) ([b7ee040](https://github.com/nuxt/vue-meta/commit/b7ee040))
* add browser build without ssr code ([2862a5b](https://github.com/nuxt/vue-meta/commit/2862a5b))
* add es build ([56f0b61](https://github.com/nuxt/vue-meta/commit/56f0b61))
* add getOptions method (resolves: [#215](https://github.com/nuxt/vue-meta/issues/215)) ([31e975d](https://github.com/nuxt/vue-meta/commit/31e975d))
* add option to refresh once during navigation (possible fix for [#320](https://github.com/nuxt/vue-meta/issues/320)) ([8e21175](https://github.com/nuxt/vue-meta/commit/8e21175))
* add pause/resume methods to pause updates ([d237180](https://github.com/nuxt/vue-meta/commit/d237180))
* attr keys can have array values (resolves [#231](https://github.com/nuxt/vue-meta/issues/231)) ([01edc8c](https://github.com/nuxt/vue-meta/commit/01edc8c))
* child can indicate its content should be ignored (resolves: [#204](https://github.com/nuxt/vue-meta/issues/204)) ([22e456c](https://github.com/nuxt/vue-meta/commit/22e456c))
* child can indicate parent vmid to be removed (resolves: [#288](https://github.com/nuxt/vue-meta/issues/288)) ([915fedf](https://github.com/nuxt/vue-meta/commit/915fedf))
* export hasMetaInfo helper function ([173b31d](https://github.com/nuxt/vue-meta/commit/173b31d))
* major refactor, cleanup and jest tests ([5d64d43](https://github.com/nuxt/vue-meta/commit/5d64d43))
* **ts:** update types for v2 ([#338](https://github.com/nuxt/vue-meta/issues/338)) ([7b85ff2](https://github.com/nuxt/vue-meta/commit/7b85ff2))
* render boolean attributes correctly (previously [#317](https://github.com/nuxt/vue-meta/issues/317)) ([deea5cf](https://github.com/nuxt/vue-meta/commit/deea5cf))
* track branches which contain metaInfo components ([f2e8eb5](https://github.com/nuxt/vue-meta/commit/f2e8eb5))
* use named exports to export helper functions ([95c3b7d](https://github.com/nuxt/vue-meta/commit/95c3b7d))
