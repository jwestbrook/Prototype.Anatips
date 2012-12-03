Prototype.Anatips
=================

Mirrored from http://www.anaema.com/the_smallest_unbloated_tooltips_library.html



__Anatips : the small, unbloated tooltips library__

Sometimes you're seeking for something that's should be so simple, so small that you think you'll find it in a couple of seconds. And you don't.

Because pure css tooltips don't behaved the way I wanted, I googled everywhere to find a library and I found tons of them, but none fit the bill. So I did this small one.

Anatips has been loosely tested with FF3, IE7, Opera 9 and Safari 3.1

1) Anatips requires [PrototypeJS](http://prototypejs.org/download) and `builder.js` from Script.aculo.us

```html
<script src="prototype.js" type="text/javascript"></script>
<script src="builder.js" type="text/javascript"></script> 
```

2) Download anatips

3) Then 

```html
<script src="anatips.js" type="text/javascript"></script> 
<link href="anatips.css" media="screen" rel="stylesheet" type="text/css" />
```

4) set the class attribute to `anatips` and the `title` attribute to the text to display for every node of the page for which you want a tooltip.


```html
<img src="foo.jpg" class="anatips" title="this text will displayed as a tooltip"/>
```

5) Optionnally, after an ajax call you can refresh the tooltips by calling `ANAEMA.tips.setupTooltips();`