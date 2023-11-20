---
lang : "en"
lang-ref : blog
title: "blog"
layout: archive
permalink: /en/blog
---

{% assign posts = site.categories.blog %}
{% for post in posts %}
  {% if post.lang == "en" %}
    {% include archive-single.html type=page.entries_layout %}
  {% endif %}
{% endfor %}