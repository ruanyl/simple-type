simple-type
========
[![build status](https://secure.travis-ci.org/ruanyl/simple-type.svg)](http://travis-ci.org/ruanyl/simple-type)
[![NPM version](https://badge.fury.io/js/simple-type.svg)](http://badge.fury.io/js/simple-type)

enhance javascript typeof

support:array, object, number, null, boolean, function, regexp, date, undefined

## Installation

This module is installed via npm:

``` bash
$ npm install simple-type
```

## Example Usage

``` js
var simpleType = require('simple-type');

simpleType({name: 'ruan', age: 12}) === 'object' //true
simpleType(/$a/g) === 'regexp'                   //true
```
