---
layout: default
title:  "My First Jekyll Post"
date:   2014-03-09 16:56:39
categories: jekyll update
subject: cats
image_file: student.png
audio_file: welcome.mp3
---

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

Anything that appears between the dashed lines at the top is available inside the post via page object.
For example, to access the title:
{{ page.title }}

I just added a subject: {{ page.subject }}

There's an image file here: {{ page.image_file }}

There's an audio file here: {{ page.audio_file }}

Now testing watch feature.

Anything that's in _config.yml can be accessed via site object.

For example, markdown flavor is `{{ site.markdown }}`

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
