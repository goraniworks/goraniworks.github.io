---
layout: default
title: Home
---

# Welcome to my Blog!

Here are my recent posts:

{% for post in site.posts limit:5 %}
  - [{{ post.title }}]({{ post.url | absolute_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
