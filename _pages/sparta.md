---
title: "Sparta"
layout: category
permalink: /categories/sparta/
taxonomy: sparta
author_profile: true
---

{% raw %}
{% assign posts = site.categories.sparta %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
{% endraw %}        