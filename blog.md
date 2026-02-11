---
title: Blog
permalink: /blog/
layout: default
---

# Blog Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{% endfor %}
