---
title: Blog
---

## Derniers articles

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }}) ({{ post.date }}
  
  {{ post.excerpt }}
{% endfor %}

