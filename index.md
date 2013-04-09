---
layout: default
title: My Blog
desc: welcome to my blog
---
* [new post]({{ site.baseurl }}new/gh-pages/_posts)
{% for post in site.posts %}
* {{ post.date | date_to_string }} &raquo; [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
