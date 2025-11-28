---
layout: page
title: "Blog"
---

# Blog

Bienvenue sur mon blog !

Vous trouverez ici mes articles sur la conception pédagogique, mes analyses, et mes retours d’expérience.

---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d/%m/%Y" }}
{% endfor %}
