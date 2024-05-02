# @firanorg/placeat-illo-dolorem <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@firanorg/placeat-illo-dolorem');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@firanorg/placeat-illo-dolorem
[npm-version-svg]: https://versionbadg.es/inspect-js/@firanorg/placeat-illo-dolorem.svg
[deps-svg]: https://david-dm.org/inspect-js/@firanorg/placeat-illo-dolorem.svg
[deps-url]: https://david-dm.org/inspect-js/@firanorg/placeat-illo-dolorem
[dev-deps-svg]: https://david-dm.org/inspect-js/@firanorg/placeat-illo-dolorem/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@firanorg/placeat-illo-dolorem#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@firanorg/placeat-illo-dolorem.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@firanorg/placeat-illo-dolorem.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@firanorg/placeat-illo-dolorem.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@firanorg/placeat-illo-dolorem
[codecov-image]: https://codecov.io/gh/inspect-js/@firanorg/placeat-illo-dolorem/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@firanorg/placeat-illo-dolorem/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@firanorg/placeat-illo-dolorem
[actions-url]: https://github.com/firanorg/placeat-illo-dolorem/actions
