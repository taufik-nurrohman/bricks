Bricks
======

> Tiny grid layout plugin.

[![View Demo](data:image/png;base64,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)](https://cdn.rawgit.com/tovic/bricks/master/bricks.html "View Demo")

Usage
-----

### HTML

~~~ .html
<div id="container">
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
~~~

### CSS

~~~ .css
#container {
  padding: 0 0 5px 5px;
  margin-right: auto;
  margin-left: auto;
  overflow: hidden;
}

#container > div {
  width: 100px;
  float: left;
  margin: 5px 5px 0 0;
}
~~~

### JavaScript

~~~ .javascript
var gap = 5; // same as `#container div` margin
var pad = 5; // same as `#container` padding
bricks('container', gap, pad);
~~~

Limitation
----------

 - Can’t handle bricks with different width.