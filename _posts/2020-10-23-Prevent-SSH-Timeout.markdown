---
layout: post
title:  "Prevent SSH timeout"
date:   2020-10-23
categories: jekyll update
---

To prevent SSH timeout, open the ssh config file,

```console
vim ~/.ssh/config
```

and add the following option:

> `ServerAliveInterval 30`


<!-- to render in localhost:
bundle exec jekyll serve -->