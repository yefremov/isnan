# isnan [![Build Status](https://travis-ci.org/yefremov/isnan.svg?branch=master)](https://travis-ci.org/yefremov/isnan) [![Coverage Status](https://coveralls.io/repos/github/yefremov/isnan/badge.svg?branch=master)](https://coveralls.io/github/yefremov/isnan?branch=master) [![npm version](https://badge.fury.io/js/isnan.svg)](https://badge.fury.io/js/isnan)

Test whether value is NaN.

## Installation

```bash
$ npm install isnan
```

## API

```js
const isNaN = require('isnan');

isNaN('foo' / 1);
// => true

isNaN({ foo: 'bar' });
// => false
```

## Running tests

```bash
$ npm test
```

## License

[MIT](LICENSE)
