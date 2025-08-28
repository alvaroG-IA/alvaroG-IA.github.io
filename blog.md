---
title: Blog
---

# Blog

Aquí encontrarás mis publicaciones sobre proyectos y desarrollo en IA.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %B %Y" }}
{% endfor %}
s