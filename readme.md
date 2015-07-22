# Tzu.js

A pocket of mathematical operations in JavaScript

## Install

```sh
$ npm install tzu
```

## Usage

### romanize

Convert arabic number to **roman number**

```javascript
var tzu = require('tzu');
tzu.romanize('5053'); // MMMMMLIII
```

### deromanize

Convert roman number to **arabic number**

```javascript
var tzu = require('tzu');
tzu.deromanize('MLVII'); // 1057
```

### range

Built-in function to generate array ranges.

```javascript
var tzu = require('tzu');
tzu.range(5, 3); // [5,6,7] 
```

## About

This module is a tribute to Sun Tzu.

### Algorithms References

romanize | deromanize: http://blog.stevenlevithan.com/archives/javascript-roman-numeral-converter

### MIT LICENSED