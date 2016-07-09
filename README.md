Bricks
======

> Short and nice slogan please…

[View Demo](https://cdn.rawgit.com/tovic/bricks/master/bricks.html)

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
  padding:0 0 5px 5px;
  margin-right:auto;
  margin-left:auto;
}
#container > div {
  width:100px;
  margin:5px 5px 0 0;
}
~~~

### JavaScript

~~~ .javascript
var gap = 5; // same as `#container div` margin
var pad = 5; // same as `#container` padding
bricks('container', gap, pad);
~~~