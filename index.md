---
layout: default
title: Home
---

{% for post in site.posts %}
####[<span class="title-time">{{ post.date | date:"%Y-%m-%d" }}</span> {{ post.title }}]({{ post.url }})
{% endfor %}
