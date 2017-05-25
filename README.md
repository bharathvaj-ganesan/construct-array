 
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.svg)](https://gruntjs.com/)
[![Build Status](https://travis-ci.org/bharathvaj1995/array-random-shuffle.svg?branch=master)](https://travis-ci.org/bharathvaj1995/make-array) 
[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate/badges/gpa.svg)](https://codeclimate.com/github/codeclimate/codeclimate)
 
# construct-array     

Returns the passing value(anything .. string,number,null,undefined,object,array) as an array.

## Motivation

Inspired by [Sindre Sorhus](https://sindresorhus.com)

## Installation
```
$ npm install --save construct-array 
```
## Usuage
```javascript
let arrayify = require('construct-array');

arrayify('India');
//=>['India']
arrayify(null);
//=>[null]
arrayify(undefined);
//=> [undefined]
arrayify([2,3]);
//=> [[2,3]] i.e arr[0]=[2,3]
arrayify(undefined);
//=> [undefined]
arrayify({name : "april"});
//=> [{name : "april"}] i.e array of objects
```

## Related
- [arrify](https://github.com/sindresorhus/arrify) - Convert a value to an array

The difference that is this module does **NOT** turn `null` or `undefined` to an empty array.

- [array-ify](https://github.com/stevemao/array-ify) - Turn anything into an array

The difference that is this module does **NOT** turn `array` to array.

## License

MIT © [Bharathvaj Ganesan](https://github.com/bharathvaj1995)