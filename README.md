doc-metrix-cpu
===
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coverage Status][coveralls-image]][coveralls-url] [![Dependencies][dependencies-image]][dependencies-url] [![Github Issues][github-issues-image]][github-issues-url]

Provides an API to doc-metrix CPU performance metrics.


## Installation

``` bash
$ npm install doc-metrix-cpu
```

For use in the browser, use [browserify](https://github.com/substack/node-browserify).


## API




## Usage





## Examples

``` javascript
var lib = require( 'doc-metrix-cpu' );
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


## Tests

### Unit

Unit tests use the [Mocha](http://visionmedia.github.io/mocha) test framework with [Chai](http://chaijs.com) assertions. To run the tests, execute the following command in the top-level application directory:

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
$ open reports/coverage/lcov-report/index.html
```


## License

[MIT license](http://opensource.org/licenses/MIT). 


---
## Copyright

Copyright &copy; 2014. Athan Reines.


[npm-image]: http://img.shields.io/npm/v/doc-metrix-cpu.svg
[npm-url]: https://npmjs.org/package/doc-metrix-cpu

[travis-image]: http://img.shields.io/travis/doc-metrix/cpu-node/master.svg
[travis-url]: https://travis-ci.org/doc-metrix/cpu-node

[coveralls-image]: https://img.shields.io/coveralls/doc-metrix/cpu-node/master.svg
[coveralls-url]: https://coveralls.io/r/doc-metrix/cpu-node?branch=master

[dependencies-image]: http://img.shields.io/david/doc-metrix/doc-metrix-cpu.svg
[dependencies-url]: https://david-dm.org/doc-metrix/doc-metrix-cpu

[dev-dependencies-image]: http://img.shields.io/david/dev/doc-metrix/doc-metrix-cpu.svg
[dev-dependencies-url]: https://david-dm.org/dev/doc-metrix/doc-metrix-cpu

[github-issues-image]: http://img.shields.io/github/issues/doc-metrix/cpu-node.svg
[github-issues-url]: https://github.com/doc-metrix/cpu-node/issues