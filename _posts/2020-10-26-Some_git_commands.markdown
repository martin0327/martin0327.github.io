---
layout: post
title:  "Some useful git commands"
date:   2020-10-26
categories: jekyll update
---

Here are some useful git commands:

```console
git log --oneline

git checkout -b feature/feature_name
git push origin feature/feature_name
git branch -d feature/feature_name

git checkout feature/feature_name
git rebase master

git pull --rebase

git reset --hard HEAD^
```



<!-- to render in localhost:
bundle exec jekyll serve -->