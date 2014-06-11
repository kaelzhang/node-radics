# radics [![NPM version](https://badge.fury.io/js/radics.svg)](http://badge.fury.io/js/radics) [![Build Status](https://travis-ci.org/kaelzhang/node-radics.svg?branch=master)](https://travis-ci.org/kaelzhang/node-radics) [![Dependency Status](https://gemnasium.com/kaelzhang/node-radics.svg)](https://gemnasium.com/kaelzhang/node-radics)

Converts numbers between different bases even between custom radix.

## Install

```bash
$ npm install radics --save
```

## Usage

```js
var radics = require('radics');
radics('FF').from(16).to(10); // '255'
radics('FF').from('0123456789ABCDEF').to('0123456789'); // '255'
radics('FF').from(''); 
```

## .from(base)

- base
  - `String` your custom radix base
  - `Number` number system

Define the base of the "number".

## .to(base)

Converts to the destination radix system, and always returns `String`.

## Licence

MIT
<!-- do not want to make nodeinit to complicated, you can edit this whenever you want. -->