---
layout: default
title: My Blog
desc: welcome to my blog
---
{{ site.source }}
{{ site.destination }}
{% for post in site.posts %}
* {{ post.date | date_to_string }} &raquo; [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
