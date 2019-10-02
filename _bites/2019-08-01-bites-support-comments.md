---
layout: post
identifier: bites-support-comments
title: "Bites support comments"
date: 2019-08-01
comments: true
---

Bites are [Jekyll collections](https://jekyllrb.com/docs/collections/). For most part, they
behave just like posts but there are a few downsides. Pagination doesn't work out of the box
for collections (see this [GitHub issue](https://github.com/sverrirs/jekyll-paginate-v2/issues/58)).

Implementing Bites as
[regular posts](https://stackoverflow.com/questions/20606197/jekyll-multiple-post-types)
also lacks pagination because Jekyll pagination
[does not support](https://jekyllrb.com/docs/pagination/) categories.

But, Bites still support comments. Simply go to the [Bite's permalink]({{ page.url }}).