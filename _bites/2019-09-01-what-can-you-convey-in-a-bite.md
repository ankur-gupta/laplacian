---
layout: post
identifier: what-can-you-convey-in-a-bite
title: "What can you convey in a bite?"
date: 2019-09-01
comments: true
---

Bites are intended to lie somewhere between a tweet and a regular post or article.
Let's say, you find a cool shell trick that you want to share with a short explanation.
Below is one such example. Often, we need to recursively seek and destroy all `.pyc` files
within current directly. The following command does that for us in bash shell.

```bash
find . -name "*.pyc" -type f -exec rm "{}" \;
```

Simply typing `find . -name "*.pyc" -type f` would list all files (and not directories)
whose name matches the glob `*.pyc` within the directory `.` (current directory).
`find` also accepts `-exec` option in both Linux and MacOS (though `-delete`
option [may not](https://unix.stackexchange.com/questions/167823/find-exec-rm-vs-delete)
always be available). See other variants
[here](https://unix.stackexchange.com/questions/167823/find-exec-rm-vs-delete).

