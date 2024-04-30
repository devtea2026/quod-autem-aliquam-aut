# @devtea2026/quod-autem-aliquam-aut <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

`[].map(f)` for older browsers

# example

``` js
var map = require('@devtea2026/quod-autem-aliquam-aut');
var letters = map([97,98,99], function (c) {
	return String.fromCharCode(c);
});
console.log(letters.join(''));
```

output:

```
abc
```

# methods

``` js
var map = require('@devtea2026/quod-autem-aliquam-aut')
```

## var ys = map(xs, f)

Create a new array `ys` by applying `f(xs[i], i, xs)` to each element in `xs` at
index `i`.

# install

With [npm](https://npmjs.org) do:

```
npm install @devtea2026/quod-autem-aliquam-aut
```

# license

MIT

[package-url]: https://npmjs.org/package/@devtea2026/quod-autem-aliquam-aut
[npm-version-svg]: https://versionbadg.es/ljharb/@devtea2026/quod-autem-aliquam-aut.svg
[deps-svg]: https://david-dm.org/ljharb/@devtea2026/quod-autem-aliquam-aut.svg
[deps-url]: https://david-dm.org/ljharb/@devtea2026/quod-autem-aliquam-aut
[dev-deps-svg]: https://david-dm.org/ljharb/@devtea2026/quod-autem-aliquam-aut/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@devtea2026/quod-autem-aliquam-aut#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2026/quod-autem-aliquam-aut.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2026/quod-autem-aliquam-aut.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2026/quod-autem-aliquam-aut.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2026/quod-autem-aliquam-aut
[codecov-image]: https://codecov.io/gh/ljharb/@devtea2026/quod-autem-aliquam-aut/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@devtea2026/quod-autem-aliquam-aut/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@devtea2026/quod-autem-aliquam-aut
[actions-url]: https://github.com/devtea2026/quod-autem-aliquam-aut/actions
