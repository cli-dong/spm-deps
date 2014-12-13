# spm-deps

[![NPM version](https://img.shields.io/npm/v/spm-deps.svg?style=flat-square)](https://npmjs.org/package/spm-deps)
[![Build Status](https://img.shields.io/travis/crossjs/spm-deps.svg?style=flat-square)](https://travis-ci.org/crossjs/spm-deps)
[![NPM downloads](http://img.shields.io/npm/dm/spm-deps.svg?style=flat-square)](https://npmjs.org/package/spm-deps)
[![David](http://img.shields.io/david/crossjs/spm-deps.svg?style=flat-square)](https://npmjs.org/package/spm-deps)
[![David](http://img.shields.io/david/dev/crossjs/spm-deps.svg?style=flat-square)](https://npmjs.org/package/spm-deps)

  > parse tree of spm dependencies for seajs config

## usage

```bash
$ npm install spm-deps
```

```js
var deps = require('spm-deps');

// get dependencies tree
var depsTree = deps({
  // if need
  idleading: 'static'
});

// get devDependencies tree
var devDepsTree = deps({
  dev: true,
  // if need
  idleading: 'static'
});
```
