---
layout: article
permalink: /jekyllsetup/
title: "Local Build Setup Instructions"
share: false
---

## Setting up  Jekyll on WSL

WSL doesn't come with a lot of the compilers and other tools necessary to run Jekyll, but with a little bit of setup you can have a compatible toolset. The following should ensure you have a sufficient environment to build and develop material locally.

```bash
sudo apt install ruby ruby-dev build-essential make gcc zlib1g-dev patch liblzma-dev nodejs
sudo gem install pkg-config
sudo gem install nokogiri jekyll
```
Other references: [<sup>1</sup>](https://lucasg.github.io/2017/01/22/Running-Jekyll-on-WSL/)
[<sup>2</sup>](https://www.richard-banks.org/2016/08/jekyll-on-bash-on-ubuntu-on-windows.html)
