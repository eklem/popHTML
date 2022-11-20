# popHTML
GGet input and populate HTML. Pure JS. Only demo purposes. The small code snippets I re-write every time to create quick browser demos.

[![NPM version][npm-version-image]][npm-url]
[![NPM downloads][npm-downloads-image]][npm-url]
[![](https://data.jsdelivr.com/v1/package/npm/pophtml/badge?style=rounded)](https://www.jsdelivr.com/package/npm/pophtml)
[![MIT License][license-image]][license-url]

## Use

```HTML
<!-- HEAD-tag -->
<script src="https://cdn.jsdelivr.net/npm/pophtml@0.0.1/index.min.js"></script>

<!-- BODY-tag -->
<button id="button">Click me</button>
<div id="populateElement"></div>
```

```javaScript
document.getElementById('button').onclick = function () {
  popHTML('some text to populate tag with', { tagToPop: 'populateElement', tagToPopWith: 'div', append: true })
}
```

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=rounded
[license-url]: LICENSE
[npm-url]: https://npmjs.org/package/pophtml
[npm-version-image]: https://img.shields.io/npm/v/pophtml.svg?style=rounded
[npm-downloads-image]: https://img.shields.io/npm/dm/pophtml.svg?style=rounded
