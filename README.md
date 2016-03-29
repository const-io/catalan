Catalan's Constant
===
[![NPM version][npm-image]][npm-url] [![Build Status][build-image]][build-url] [![Coverage Status][coverage-image]][coverage-url] [![Dependencies][dependencies-image]][dependencies-url]

> [Catalan's constant][catalan-constant].

[Catalan's constant][catalan-constant] `C` (also denoted `K` or `G`) commonly appears in estimates of combinatorial functions and may be defined by the following infinite series

<!-- <equation class="equation" label="eq:catalan_constant" align="center" raw="C = \sum_{n=0}^{\infty} \frac{(-1)^{n}}{(2n+1)^2} = \frac{1}{1^2} - \frac{1}{3^2} + \frac{1}{5^2} - \frac{1}{7^2} + \cdots" alt="Catalan's constant"> -->
<div class="equation" align="center" data-raw-text="C = \sum_{n=0}^{\infty} \frac{(-1)^{n}}{(2n+1)^2} = \frac{1}{1^2} - \frac{1}{3^2} + \frac{1}{5^2} - \frac{1}{7^2} + \cdots" data-equation="eq:catalan_constant">
	<img src="https://cdn.rawgit.com/const-io/catalan/566611cc15795f650b5a99c8a416b9ce333185d9/docs/img/catalan.svg" alt="Catalan's constant">
	<br>
</div>
<!-- </equation> -->


## Installation

``` bash
$ npm install const-catalan
```


## Usage

``` javascript
var CATALAN = require( 'const-catalan' );
```

#### CATALAN

[Catalan's constant][catalan-constant].

``` javascript
CATALAN === 0.915965594177219;
```


## Examples

``` javascript
var CATALAN = require( 'const-catalan' );

console.log( CATALAN );
// returns 0.915965594177219
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


---
## Tests

### Unit

This repository uses [tape][tape] for unit tests. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul][istanbul] as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


### Browser Support

This repository uses [Testling][testling] for browser testing. To run the tests in a (headless) local web browser, execute the following command in the top-level application directory:

``` bash
$ make test-browsers
```

To view the tests in a local web browser,

``` bash
$ make view-browser-tests
```

<!-- [![browser support][browsers-image]][browsers-url] -->


---
## License

[MIT license](http://opensource.org/licenses/MIT).


## Copyright

Copyright &copy; 2015-2016. The [Compute.io][compute-io] Authors.


[npm-image]: http://img.shields.io/npm/v/const-catalan.svg
[npm-url]: https://npmjs.org/package/const-catalan

[build-image]: http://img.shields.io/travis/const-io/catalan/master.svg
[build-url]: https://travis-ci.org/const-io/catalan

[coverage-image]: https://img.shields.io/codecov/c/github/const-io/catalan/master.svg
[coverage-url]: https://codecov.io/github/const-io/catalan?branch=master

[dependencies-image]: http://img.shields.io/david/const-io/catalan.svg
[dependencies-url]: https://david-dm.org/const-io/catalan

[dev-dependencies-image]: http://img.shields.io/david/dev/const-io/catalan.svg
[dev-dependencies-url]: https://david-dm.org/dev/const-io/catalan

[github-issues-image]: http://img.shields.io/github/issues/const-io/catalan.svg
[github-issues-url]: https://github.com/const-io/catalan/issues

[tape]: https://github.com/substack/tape
[istanbul]: https://github.com/gotwarlost/istanbul
[testling]: https://ci.testling.com

[compute-io]: https://github.com/compute-io

[catalan-constant]: http://en.wikipedia.org/wiki/Catalan%27s_constant
