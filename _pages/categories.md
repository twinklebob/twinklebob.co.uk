---
layout: page
title: Categories
exclude: true
---

{% for category in site.categories %}
* {{ category[0] }}
{% endfor %}
