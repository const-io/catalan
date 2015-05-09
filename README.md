Catalan's Constant
===
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coverage Status][coveralls-image]][coveralls-url] [![Dependencies][dependencies-image]][dependencies-url]

> [Catalan's constant](http://en.wikipedia.org/wiki/Catalan%27s_constant).

Catalan's constant `C` (also denoted `K` or `G`) commonly appears in estimates of combinatorial functions and may be defined by the following infinite series

<div align="center">
	<img src="https://github.com/compute-io/const-catalan/blob/master/docs/img/eqn.png" alt="Calatan's constant." height="48px">
	<br>
</div>


## Installation

``` bash
$ npm install compute-const-catalan
```

For use in the browser, use [browserify](https://github.com/substack/node-browserify).


## Usage

``` javascript
var CATALAN = require( 'compute-const-catalan' );
```

#### CATALAN

[Catalan's constant](http://en.wikipedia.org/wiki/Catalan%27s_constant).

``` javascript
CATALAN === 0.915965594177219
```


## Examples

``` javascript
var C = require( 'compute-const-catalan' );

console.log( C );
// returns 0.915965594177219
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


## Tests

### Unit

Unit tests use the [Mocha](http://mochajs.org/) test framework with [Chai](http://chaijs.com) assertions. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul](https://github.com/gotwarlost/istanbul) as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


---
## License

[MIT license](http://opensource.org/licenses/MIT). 


## Copyright

Copyright &copy; 2015. Athan Reines.


[npm-image]: http://img.shields.io/npm/v/compute-const-catalan.svg
[npm-url]: https://npmjs.org/package/compute-const-catalan

[travis-image]: http://img.shields.io/travis/compute-io/const-catalan/master.svg
[travis-url]: https://travis-ci.org/compute-io/const-catalan

[coveralls-image]: https://img.shields.io/coveralls/compute-io/const-catalan/master.svg
[coveralls-url]: https://coveralls.io/r/compute-io/const-catalan?branch=master

[dependencies-image]: http://img.shields.io/david/compute-io/const-catalan.svg
[dependencies-url]: https://david-dm.org/compute-io/const-catalan

[dev-dependencies-image]: http://img.shields.io/david/dev/compute-io/const-catalan.svg
[dev-dependencies-url]: https://david-dm.org/dev/compute-io/const-catalan

[github-issues-image]: http://img.shields.io/github/issues/compute-io/const-catalan.svg
[github-issues-url]: https://github.com/compute-io/const-catalan/issues
