---
title: Blog
---

## Derniers articles

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }}) ({{ post.date  | date: '%F' }})
  
  {{ post.excerpt }}
{% endfor %}

