---
layout: default
title: My Blog
desc: welcome to my blog
---
{% for post in site.posts %}
* {{ post.date | date_to_string }} &raquo; [{{ post.title }}]({{ post.url }})
{% endfor %}

* item1
* item2
* item3
