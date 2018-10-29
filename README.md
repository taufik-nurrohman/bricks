Bricks
======

> Tiny grid layout plugin.

[![View Demo](https://3.bp.blogspot.com/-8FcU5n_DDao/V4CKBCr3z8I/AAAAAAAAIxU/0tTsnS1sQq0G4JBY1DVIbI5ZrVJrm3MUgCLcB/s1600/bricks.png)](//tovic.github.io/bricks/bricks.html "View Demo")

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

~~~ .js
var gap = 5; // same as `#container div` margin
var pad = 5; // same as `#container` padding

bricks('container', gap, pad);
~~~

Limitation
----------

 - Can’t handle bricks with different width.