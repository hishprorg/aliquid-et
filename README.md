# @hishprorg/aliquid-et <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@hishprorg/aliquid-et');
const Eval = require('@hishprorg/aliquid-et/eval');
const Range = require('@hishprorg/aliquid-et/range');
const Ref = require('@hishprorg/aliquid-et/ref');
const Syntax = require('@hishprorg/aliquid-et/syntax');
const Type = require('@hishprorg/aliquid-et/type');
const URI = require('@hishprorg/aliquid-et/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@hishprorg/aliquid-et
[npm-version-svg]: https://versionbadg.es/ljharb/@hishprorg/aliquid-et.svg
[deps-svg]: https://david-dm.org/ljharb/@hishprorg/aliquid-et.svg
[deps-url]: https://david-dm.org/ljharb/@hishprorg/aliquid-et
[dev-deps-svg]: https://david-dm.org/ljharb/@hishprorg/aliquid-et/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hishprorg/aliquid-et#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/aliquid-et.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/aliquid-et.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/aliquid-et.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/aliquid-et
[codecov-image]: https://codecov.io/gh/ljharb/@hishprorg/aliquid-et/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hishprorg/aliquid-et/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hishprorg/aliquid-et
[actions-url]: https://github.com/hishprorg/aliquid-et/actions
