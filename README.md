# Number.isInteger <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Number.isInteger` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@supernpm2024/voluptate-eos-animi-nobis).

## Getting started

```sh
npm install --save @supernpm2024/voluptate-eos-animi-nobis
```

## Usage/Examples

```js
console.log(Number.isInteger(-3)); // true
console.log(Number.isInteger(2 ** 54)); // true
console.log(Number.isInteger(2.3)); // false
console.log(Number.isInteger(Infinity)); // false
console.log(Number.isInteger("7")); // false
```

## Tests

Clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@supernpm2024/voluptate-eos-animi-nobis
[npm-version-svg]: https://versionbadg.es/supernpm2024/voluptate-eos-animi-nobis.svg
[deps-svg]: https://david-dm.org/supernpm2024/voluptate-eos-animi-nobis.svg
[deps-url]: https://david-dm.org/supernpm2024/voluptate-eos-animi-nobis
[dev-deps-svg]: https://david-dm.org/supernpm2024/voluptate-eos-animi-nobis/dev-status.svg
[dev-deps-url]: https://david-dm.org/supernpm2024/voluptate-eos-animi-nobis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@supernpm2024/voluptate-eos-animi-nobis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@supernpm2024/voluptate-eos-animi-nobis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@supernpm2024/voluptate-eos-animi-nobis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@supernpm2024/voluptate-eos-animi-nobis
[codecov-image]: https://codecov.io/gh/supernpm2024/voluptate-eos-animi-nobis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/supernpm2024/voluptate-eos-animi-nobis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/supernpm2024/voluptate-eos-animi-nobis
[actions-url]: https://github.com/supernpm2024/voluptate-eos-animi-nobis/actions
