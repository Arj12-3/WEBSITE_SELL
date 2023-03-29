# is-directory [![NPM version](https://img.shields.io/npm/v/is-directory.svg?style=flat)](https://www.npmjs.com/package/is-directory) [![NPM downloads](https://img.shields.io/npm/dm/is-directory.svg?style=flat)](https://npmjs.org/package/is-directory) [![Build Status](https://img.shields.io/travis/jonschlinkert/is-directory.svg?style=flat)](https://travis-ci.org/jonschlinkert/is-directory)

Returns true if a filepath exists on the file system and it's directory.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install is-directory --save
```

## Usage

```js
var isDirectory = require('is-directory');

isDirectory('node_modules', function(err, dir) {
  if (err) throw err;
  console.log(dir);
  //=> true
});

isDirectory.sync('README.md');
//=> false
```

## Related projects

You might also be interested in these projects:

* [is-absolute](https://www.npmjs.com/package/is-absolute): Polyfill for node.js `path.isAbolute`. Returns true if a file path is absolute. | [homepage](https://github.com/jonschlinkert/is-absolute)
* [is-glob](https://www.npmjs.com/package/is-glob): Returns `true` if the given string looks like a glob pattern or an extglob pattern.… [more](https://www.npmjs.com/package/is-glob) | [homepage](https://github.com/jonschlinkert/is-glob)
* [is-relative](https://www.npmjs.com/package/is-relative): Returns `true` if the path appears to be relative. | [homepage](https://github.com/jonschlinkert/is-relative)

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/is-directory/issues/new).

## Building docs

Generate readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install verb && npm run docs
```

Or, if [verb](https://github.com/verbose/verb) is installed globally:

```sh
$ verb
```

## Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

## Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](https://github.com/jonschlinkert/is-directory/blob/master/LICENSE).

***

_This file was generated by [verb](https://github.com/verbose/verb), v0.9.0, on May 21, 2016._