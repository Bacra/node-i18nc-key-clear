I18NC-KEY-TRIM
==================


[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Coveralls][coveralls-image]][coveralls-url]
[![NPM License][license-image]][npm-url]

# Install
```
npm install i18nc-key-clear
```

# Useage

```javascript
var i18nc = require('i18nc');
require('i18nc-key-clear')(i18nc);

i18nc('var str="中文<!--注释-->词典"', {pluginEnabled: {keyClear: true}});
console.log(i18nc.code);	// var str=I18N('中文词典');
```


[npm-image]: http://img.shields.io/npm/v/i18nc-key-clear.svg
[downloads-image]: http://img.shields.io/npm/dm/i18nc-key-clear.svg
[npm-url]: https://www.npmjs.org/package/i18nc-key-clear
[travis-image]: http://img.shields.io/travis/Bacra/node-i18nc-key-clear/master.svg?label=linux
[travis-url]: https://travis-ci.org/Bacra/node-i18nc-key-clear
[coveralls-image]: https://img.shields.io/coveralls/Bacra/node-i18nc-key-clear.svg
[coveralls-url]: https://coveralls.io/github/Bacra/node-i18nc-key-clear
[license-image]: http://img.shields.io/npm/l/i18nc-key-clear.svg
