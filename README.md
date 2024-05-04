# @hutechwebsite/ab-quibusdam-pariatur-beatae <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @hutechwebsite/ab-quibusdam-pariatur-beatae
```

## Usage/Examples

```js
var regexTester = require('@hutechwebsite/ab-quibusdam-pariatur-beatae');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@hutechwebsite/ab-quibusdam-pariatur-beatae
[npm-version-svg]: https://versionbadg.es/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae.svg
[deps-svg]: https://david-dm.org/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae.svg
[deps-url]: https://david-dm.org/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae
[dev-deps-svg]: https://david-dm.org/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hutechwebsite/ab-quibusdam-pariatur-beatae.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hutechwebsite/ab-quibusdam-pariatur-beatae.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hutechwebsite/ab-quibusdam-pariatur-beatae.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hutechwebsite/ab-quibusdam-pariatur-beatae
[codecov-image]: https://codecov.io/gh/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hutechwebsite/ab-quibusdam-pariatur-beatae
[actions-url]: https://github.com/hutechwebsite/ab-quibusdam-pariatur-beatae/actions
