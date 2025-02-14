# Changelog

This file was generated using [@jscutlery/semver](https://github.com/jscutlery/semver).

# 1.0.0 (2022-11-19)


### Bug Fixes

* fix node plugin fs augments when outside next child compiler ([#284](https://github.com/module-federation/nextjs-mf/issues/284)) ([dfa99c8](https://github.com/module-federation/nextjs-mf/commit/dfa99c86fdd8d73091764532d52be5f81b89a508))
* **package.json:** fix package export fields for utils ([#285](https://github.com/module-federation/nextjs-mf/issues/285)) ([99d6b77](https://github.com/module-federation/nextjs-mf/commit/99d6b779696b5dbebea9cf3c870a5caa5d9d7c6f))
* remove exports field from package.json ([#318](https://github.com/module-federation/nextjs-mf/issues/318)) ([a9148ae](https://github.com/module-federation/nextjs-mf/commit/a9148ae27f1c05fe4c1586ed5769c79054a7033e))
* set peer dependencies ([#341](https://github.com/module-federation/nextjs-mf/issues/341)) ([fec9608](https://github.com/module-federation/nextjs-mf/commit/fec960813a4e3859a5fb24863bb55e463a2fdfa3))
* **typescript:** fix exposePages type ([#309](https://github.com/module-federation/nextjs-mf/issues/309)) ([c0be839](https://github.com/module-federation/nextjs-mf/commit/c0be839787f97c5e23cea3d7cf501caaa469972f))
* **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))


### Features

*  Automatic Async boundary loader ([#330](https://github.com/module-federation/nextjs-mf/issues/330)) ([7e3c08c](https://github.com/module-federation/nextjs-mf/commit/7e3c08cf7835c0407bdce7ed6865b864153074a4))
* implement __webpack_require__.l functionality in server builds ([99d1231](https://github.com/module-federation/nextjs-mf/commit/99d12314f68ac526000fa5410a14072a11b260a4))
* **typescript:** excessive recompilation prevention ([#306](https://github.com/module-federation/nextjs-mf/issues/306)) ([6e1967f](https://github.com/module-federation/nextjs-mf/commit/6e1967f019afb25dfbcfe83627b08ae8b1fe97b2))
* **utils:** configurable logger using webpack infrastructure logger ([#355](https://github.com/module-federation/nextjs-mf/issues/355)) ([d6ffcd0](https://github.com/module-federation/nextjs-mf/commit/d6ffcd0de1662c410f33a7742db1fd02aba24aef)), closes [#243](https://github.com/module-federation/nextjs-mf/issues/243)


### BREAKING CHANGES

* **typescript:** Reimplemented the whole plugin from round-up to enhance performance, prevent excessive recompilation and other issues.

Some key changes to the plugin includes:

- Downloading remote types before compilation starts.
- Caching remote types for better performance.
- Ability to provide Plugin options.

Please go through plugin `readme.md` file to understand what's changed and how to use the plugin.



# [0.5.0](https://github.com/module-federation/nextjs-mf/compare/utils-0.4.1...utils-0.5.0) (2022-10-31)


### Features

* **utils:** configurable logger using webpack infrastructure logger ([#355](https://github.com/module-federation/nextjs-mf/issues/355)) ([d6ffcd0](https://github.com/module-federation/nextjs-mf/commit/d6ffcd0de1662c410f33a7742db1fd02aba24aef)), closes [#243](https://github.com/module-federation/nextjs-mf/issues/243)



## [0.4.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.4.0...utils-0.4.1) (2022-10-26)


### Bug Fixes

* set peer dependencies ([#341](https://github.com/module-federation/nextjs-mf/issues/341)) ([fec9608](https://github.com/module-federation/nextjs-mf/commit/fec960813a4e3859a5fb24863bb55e463a2fdfa3))



# [0.4.0](https://github.com/module-federation/nextjs-mf/compare/utils-0.3.4...utils-0.4.0) (2022-10-26)


### Features

*  Automatic Async boundary loader ([#330](https://github.com/module-federation/nextjs-mf/issues/330)) ([7e3c08c](https://github.com/module-federation/nextjs-mf/commit/7e3c08cf7835c0407bdce7ed6865b864153074a4))



## [0.3.4](https://github.com/module-federation/nextjs-mf/compare/utils-0.3.3...utils-0.3.4) (2022-10-17)


### Bug Fixes

* remove exports field from package.json ([#318](https://github.com/module-federation/nextjs-mf/issues/318)) ([a9148ae](https://github.com/module-federation/nextjs-mf/commit/a9148ae27f1c05fe4c1586ed5769c79054a7033e))



## [0.3.3](https://github.com/module-federation/nextjs-mf/compare/utils-0.3.2...utils-0.3.3) (2022-10-13)


### Bug Fixes

* **typescript:** fix exposePages type ([#309](https://github.com/module-federation/nextjs-mf/issues/309)) ([c0be839](https://github.com/module-federation/nextjs-mf/commit/c0be839787f97c5e23cea3d7cf501caaa469972f))



## [0.3.2](https://github.com/module-federation/nextjs-mf/compare/utils-0.3.1...utils-0.3.2) (2022-10-12)



## [0.3.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.3.0...utils-0.3.1) (2022-10-11)



# [0.3.0](https://github.com/module-federation/nextjs-mf/compare/utils-0.2.1...utils-0.3.0) (2022-10-07)


### Features

* implement __webpack_require__.l functionality in server builds ([99d1231](https://github.com/module-federation/nextjs-mf/commit/99d12314f68ac526000fa5410a14072a11b260a4))



## [0.2.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.2.0...utils-0.2.1) (2022-10-07)


### Bug Fixes

* fix node plugin fs augments when outside next child compiler ([#284](https://github.com/module-federation/nextjs-mf/issues/284)) ([dfa99c8](https://github.com/module-federation/nextjs-mf/commit/dfa99c86fdd8d73091764532d52be5f81b89a508))
* **package.json:** fix package export fields for utils ([#285](https://github.com/module-federation/nextjs-mf/issues/285)) ([99d6b77](https://github.com/module-federation/nextjs-mf/commit/99d6b779696b5dbebea9cf3c870a5caa5d9d7c6f))



## [0.2.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.2.0...utils-0.2.1) (2022-10-07)


### Bug Fixes

* fix node plugin fs augments when outside next child compiler ([#284](https://github.com/module-federation/nextjs-mf/issues/284)) ([dfa99c8](https://github.com/module-federation/nextjs-mf/commit/dfa99c86fdd8d73091764532d52be5f81b89a508))
* **package.json:** fix package export fields for utils ([#285](https://github.com/module-federation/nextjs-mf/issues/285)) ([99d6b77](https://github.com/module-federation/nextjs-mf/commit/99d6b779696b5dbebea9cf3c870a5caa5d9d7c6f))



## [0.2.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.2.0...utils-0.2.1) (2022-10-06)


### Bug Fixes

* fix node plugin fs augments when outside next child compiler ([#284](https://github.com/module-federation/nextjs-mf/issues/284)) ([dfa99c8](https://github.com/module-federation/nextjs-mf/commit/dfa99c86fdd8d73091764532d52be5f81b89a508))
* **package.json:** fix package export fields for utils ([#285](https://github.com/module-federation/nextjs-mf/issues/285)) ([99d6b77](https://github.com/module-federation/nextjs-mf/commit/99d6b779696b5dbebea9cf3c870a5caa5d9d7c6f))



## [0.2.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.2.0...utils-0.2.1) (2022-10-06)


### Bug Fixes

* fix node plugin fs augments when outside next child compiler ([#284](https://github.com/module-federation/nextjs-mf/issues/284)) ([dfa99c8](https://github.com/module-federation/nextjs-mf/commit/dfa99c86fdd8d73091764532d52be5f81b89a508))



# [0.2.0](https://github.com/module-federation/nextjs-mf/compare/utils-0.1.0...utils-0.2.0) (2022-10-06)



## [0.1.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.1.0...utils-0.1.1) (2022-10-06)



## [0.1.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.1.0...utils-0.1.1) (2022-10-06)



## [0.1.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.1.0...utils-0.1.1) (2022-10-06)



## [0.1.1](https://github.com/module-federation/nextjs-mf/compare/utils-0.1.0...utils-0.1.1) (2022-10-06)

# [0.2.0](https://github.com/module-federation/nextjs-mf/compare/utils-0.1.0...utils-0.2.0) (2022-10-05)

# [0.1.0](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.3...utils-0.1.0) (2022-10-05)

### Bug Fixes

- **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))

## [0.0.4](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.3...utils-0.0.4) (2022-10-05)

### Bug Fixes

- **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))

## [0.0.4](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.3...utils-0.0.4) (2022-10-05)

### Bug Fixes

- **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))

## [0.0.4](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.3...utils-0.0.4) (2022-10-04)

### Bug Fixes

- **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))

## [0.0.4](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.3...utils-0.0.4) (2022-10-04)

### Bug Fixes

- **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))

## [0.0.4](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.3...utils-0.0.4) (2022-10-04)

### Bug Fixes

- **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))

## [0.0.5](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.4...utils-0.0.5) (2022-10-04)

## [0.0.4](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.3...utils-0.0.4) (2022-10-04)

### Bug Fixes

- **update versions:** bumping versions ([f72209a](https://github.com/module-federation/nextjs-mf/commit/f72209ae070fb50c9d317e764caf872facd4b887))

## 0.0.1 (2022-10-04)

## [0.0.2](https://github.com/module-federation/nextjs-mf/compare/utils-0.0.1...utils-0.0.2) (2022-09-29)

## 0.0.1 (2022-09-29)

## 0.0.1 (2022-09-29)
