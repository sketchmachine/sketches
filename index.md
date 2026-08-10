---
layout: default
title: sketchbook
---

# sketches by sketchmachine

Here are my latest posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
