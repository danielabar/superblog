---
layout: default
title:  "Sharing Image"
date:   2014-03-09 19:15:39
categories: image png
image_file: student.png
image_alt: student
excerpt: This is an override of the jekyll excerpt because I don't want an image showing on the home page.
---

Here's an image for you:
<img src="{{ site.baseurl }}/images/{{ page.image_file }}" alt="{{ page.image_alt }}">

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
