# popHTML
GGet input and populate HTML. Pure JS. Only demo purposes. The small code snippets I re-write every time to create quick browser demos.

[![](https://data.jsdelivr.com/v1/package/npm/pophtml/badge?style=rounded)](https://www.jsdelivr.com/package/npm/pophtml)

## Use


```HTML
<!-- HEAD-tag -->
<script src="https://cdn.jsdelivr.net/npm/pophtml@0.0.1/index.min.js"></script>

<!-- BODYtag -->
<button id="button">Click me</button>
<div id="populateElement"></div>
```

```javaScript
document.getElementById('button').onclick = function () {
  popHTML('some text to populate tag with', { tagToPop: 'populateElement', tagToPopWith: 'div', append: true })
}
```
