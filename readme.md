# Awesome Micro Libs [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of small, focused Node.js modules.

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. You might also like [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs).*


## Articles

* [One-line node modules](https://github.com/sindresorhus/ama/issues/10)
* [Build small single purpose modules](http://thenodeway.io/introduction/#build-small-single-purpose-modules)
* [Module best practices](https://github.com/mattdesl/module-best-practices)

## Modules

### Array

* [is-sorted](https://github.com/dcousens/is-sorted) - A small module to check if an Array is sorted.
* [array-first](https://github.com/jonschlinkert/array-first) - Get the first element or first n elements of an array.
* [array-last](https://github.com/jonschlinkert/array-last) - Return the last element in an array.
* [arr-flatten](https://github.com/jonschlinkert/arr-flatten) - Recursively flatten an array or arrays. 

### String

* [decamelize](https://github.com/sindresorhus/decamelize) - Convert a camelized string into a lowercased one with a custom separator: unicornRainbow → unicorn_rainbow.
* [to-camel-case](https://github.com/ianstormtaylor/to-camel-case) - Convert a string to a camel case.
* [to-capital-case](https://github.com/ianstormtaylor/to-capital-case) - Convert a string to a capital case.
* [to-constant-case](https://github.com/ianstormtaylor/to-constant-case) - Convert a string to a constant case.
* [to-dot-case](https://github.com/ianstormtaylor/to-dot-case) - Convert a string to a dot case.
* [to-no-case](https://github.com/ianstormtaylor/to-no-case) - Remove an existing case from a string.
* [to-pascal-case](https://github.com/ianstormtaylor/to-pascal-case) - Convert a string to a pascal case.
* [to-sentence-case](https://github.com/ianstormtaylor/to-sentence-case) - Convert a string to a sentence case.
* [to-slug-case](https://github.com/ianstormtaylor/to-slug-case) - Convert a string to a slug case.
* [to-snake-case](https://github.com/ianstormtaylor/to-snake-case) - Convert a string to a snake case.
* [to-space-case](https://github.com/ianstormtaylor/to-space-case) - Convert a string to a space case.
* [to-title-case](https://github.com/ianstormtaylor/to-title-case) - Convert a string to a title case.

### Date & Time

* [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: 1337000000 → 15d 11h 23m 20s.
* [hirestime](https://github.com/seriousManual/hirestime) - A wrapper around the built-in high resolution timer which simplifies the calculation of timestamps.

### Object

* [map-obj](https://github.com/sindresorhus/map-obj) - Map object keys and values into a new object.
* [filter-obj](https://github.com/sindresorhus/filter-obj) - Filter object keys and values into a new object.
* [object-values](https://github.com/sindresorhus/object-values) - Get the values of an object.
* [object-pairs](https://github.com/eush77/object-pairs) - Turn an object into list of [key, value] pairs for mapping, iterating or other purposes.
* [zipmap](https://github.com/landau/zipmap) - Returns a map with the keys mapped to the corresponding vals. zipmap also accepts a single value of objects or pairs.
* [just-pluck](https://github.com/jarofghosts/just-pluck) - Pluck without the madness.
* [deep-equal](https://github.com/substack/node-deep-equal) - Node's assert.deepEqual() algorithm as a standalone module.
* [deep-assign](https://github.com/sindresorhus/deep-assign) - Recursive Object.assign().
* [set-value](https://github.com/jonschlinkert/set-value) - Create nested values and any intermediaries dot notation (`'a.b.c'`) paths.  
* [get-value](https://github.com/jonschlinkert/get-value) - Use property paths (a.b.c) to get a nested value from an object.
* [has-value](https://www.npmjs.com/package/has-value) - Returns true if a value exists, false if empty. Works with deeply nested values using dot notation (`'a.b.c'`) paths.  

### Function

* [compose-function](https://github.com/stoeffel/compose-function) - Compose a new function from smaller functions `f(g(x)).
* [curry](https://github.com/dominictarr/curry) - A curry function without anything too clever.

### Stream
* [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
* [through2-filter](https://github.com/brycebaril/through2-filter) - A through2 to create an Array.prototype.filter analog for streams.
* [through2-map](https://github.com/brycebaril/through2-map) - A through2 to create an Array.prototype.map analog for streams.
* [stream-spigot](https://github.com/brycebaril/node-stream-spigot) - A readable stream generator, useful for testing or converting simple functions into Readable streams.
* [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result.
* [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify


### File System

* [rimraf](https://github.com/isaacs/rimraf) - A deep deletion module for node (like rm -rf).
* [mkdirp](https://github.com/substack/node-mkdirp) - Recursively mkdir, like mkdir -p.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Andrea Parodi](https://github.com/parro-it) has waived all copyright and related or neighboring rights to this work.
