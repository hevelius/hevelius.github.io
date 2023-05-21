---
layout: default
---

# My Blog

Welcome to my blog! Here are some of my latest posts:

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})

{{ post.excerpt }}

[Read more]({{ post.url }})

{% endfor %}
