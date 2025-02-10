---
title: "Sparta"
layout: archive
permalink: /sparta/
author_profile: true
sidebar:
  nav: "sidebar-category"
---

{% raw %}
{% assign posts = site.categories.sparta %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
{% endraw %}        