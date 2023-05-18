---
layout: default
---

## Latest post

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}