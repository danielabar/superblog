---
layout: post
title: How to create a draft post in Jekyll
---

Good news, Jekyll has native support for drafts, no hacks required. Just follow these steps to create and view drafts.

* Create a `_drafts` folder in the root of your Jekyll project

* Create a new markdown file in `_drafts` and name it just with the slug,
i.e. do not include the date as part of the file name the way you would with a regular post

* Edit the draft post, including the usual YAML Front Matter at the top,
i.e. two lines of three dashes, with attributes in the middle such as layout, title etc.

* Make sure jekyll is started with `--drafts` command line option: `$ jekyll --watch --drafts`

* Refresh your local site, all the drafts should appear at the top,
this is because Jekyll automatically dates them with the current date