# object.pick [![NPM version](https://badge.fury.io/js/object.pick.svg)](http://badge.fury.io/js/object.pick)  [![Build Status](https://travis-ci.org/jonschlinkert/object.pick.svg)](https://travis-ci.org/jonschlinkert/object.pick) 

> Returns a filtered copy of an object with only the specified keys, like `pick` from lo-dash / underscore.

## Install with [npm](npmjs.org)

```bash
npm i object.pick --save
```

## benchmarks

This is the [fastest implementation](http://jsperf.com/pick-props) I tested. Pull requests welcome!


## Usage

```js
var pick = require('object.pick');

pick({a: 'a', b: 'b'}, 'a')
//=> {a: 'a'}

pick({a: 'a', b: 'b', c: 'c'}, ['a', 'b'])
//=> {a: 'a', b: 'b'}
```

## Run tests

```bash
npm test
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on December 20, 2014._