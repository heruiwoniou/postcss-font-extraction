
[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url]

[npm-url]: https://www.npmjs.com/package/postcss-font-extraction
[npm-image]: https://img.shields.io/npm/v/postcss-font-extraction.svg

[downloads-image]: https://img.shields.io/npm/dm/postcss-font-extraction.svg
[npm-url]: https://www.npmjs.com/package/gulp

## What is postcss-font-extraction?
This is a plugin of postcss to extract font
## How to use ?
It work by postcss

```js

const postcss = require('postcss');
const fontextract = require('postcss-font-extraction');

postcss()
  .use(fontextract({
    name: 'FontAwesome',
    src: 'src/assets/font/fontawesome-webfont',
    dest: 'dist/src/assets/font'
  }))

```
