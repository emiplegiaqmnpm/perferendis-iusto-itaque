# @emiplegiaqmnpm/perferendis-iusto-itaque <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@emiplegiaqmnpm/perferendis-iusto-itaque');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@emiplegiaqmnpm/perferendis-iusto-itaque
[npm-version-svg]: https://versionbadg.es/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque.svg
[deps-svg]: https://david-dm.org/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque.svg
[deps-url]: https://david-dm.org/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque
[dev-deps-svg]: https://david-dm.org/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@emiplegiaqmnpm/perferendis-iusto-itaque.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@emiplegiaqmnpm/perferendis-iusto-itaque.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@emiplegiaqmnpm/perferendis-iusto-itaque.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@emiplegiaqmnpm/perferendis-iusto-itaque
[codecov-image]: https://codecov.io/gh/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@emiplegiaqmnpm/perferendis-iusto-itaque
[actions-url]: https://github.com/emiplegiaqmnpm/perferendis-iusto-itaque/actions
