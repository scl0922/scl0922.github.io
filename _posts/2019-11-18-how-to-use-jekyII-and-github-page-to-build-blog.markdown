---
layout: post
title:  "how to use jekyII and github page to build blog"
date:   2019-11-18 12:15:27 +0800
categories: how-to
---
JekyII and github page can be used to build a free blog conveniently.This post shows a record about how to build a blog by jekyII and github page.
# Environment Install
{% highlight shell %}
1. Install a full Ruby development environment
\curl -sSL https://get.rvm.io | bash -s stable # install nvm
[[ -s "$HOME/.rvm/scripts/rvm" ]] && source "$HOME/.rvm/scripts/rvm" # add rvm path to bash_profile
rvm list # show ruby version
rvm use 2.6.3 --default # switch ruby version (ruby version should be over 2.4)
2. Install Jekyll and bundler gems
gem install jekyll bundler
3. Create a new Jekyll site at ./myblog
jekyll new myblog
4. Build the site and make it available on a local server
bundle exec jekyll serve
5. Now browse to http://localhost:4000
{% endhighlight %}

# Github Page Configuration
browse [this website](https://pages.github.com/)

# JekyII Tutorial
browse [this website](https://jekyllrb.com/docs/)