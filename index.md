---
layout: home
title: "Home"
---

Welcome to my blog! Here are my posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}
