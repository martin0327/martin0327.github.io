---
layout: post
title:  "Set up SSH short-cut"
date:   2020-10-29
categories: jekyll update
---

Given a `key_name.pem` key file, place it in `~/.ssh` directory.

Then open the `ssh config` file:

```console
vim ~/.ssh/config
```

Add the following lines
```console
Host server_name                    # name of the server
  HostName 127.0.0.1                # host address
  User user_name                    # user name
  IdentityFile ~/.ssh/key_name.pem  # pem key location
```

<!-- to render in localhost:
bundle exec jekyll serve -->