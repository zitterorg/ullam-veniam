# @zitterorg/ullam-veniam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@zitterorg/ullam-veniam');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zitterorg/ullam-veniam
[npm-version-svg]: https://versionbadg.es/inspect-js/@zitterorg/ullam-veniam.svg
[deps-svg]: https://david-dm.org/inspect-js/@zitterorg/ullam-veniam.svg
[deps-url]: https://david-dm.org/inspect-js/@zitterorg/ullam-veniam
[dev-deps-svg]: https://david-dm.org/inspect-js/@zitterorg/ullam-veniam/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@zitterorg/ullam-veniam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zitterorg/ullam-veniam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zitterorg/ullam-veniam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zitterorg/ullam-veniam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zitterorg/ullam-veniam
[codecov-image]: https://codecov.io/gh/inspect-js/@zitterorg/ullam-veniam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@zitterorg/ullam-veniam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@zitterorg/ullam-veniam
[actions-url]: https://github.com/zitterorg/ullam-veniam/actions
