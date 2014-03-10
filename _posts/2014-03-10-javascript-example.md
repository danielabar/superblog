---
layout: post
title:  "JavaScript Google Maps Example"
date:   2014-03-10 15:15:39
categories: javascript
---

This post is to test out the syntax highlighting features of Jekyll.

Let's try some Javascript

{% highlight javascript linenos=table %}
var map;
var TILE_SIZE = 256;
var chicago = new google.maps.LatLng(41.850033,-87.6500523);

function bound(value, opt_min, opt_max) {
  if (opt_min != null) value = Math.max(value, opt_min);
  if (opt_max != null) value = Math.min(value, opt_max);
  return value;
}

function degreesToRadians(deg) {
  return deg * (Math.PI / 180);
}
{% endhighlight %}