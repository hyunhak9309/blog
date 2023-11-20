---
lang : "ko"
lang-ref : blog
title: "blog"
layout: archive
permalink: /blog
---

{% assign posts = site.categories.blog %}
{% for post in posts %}
  {% if post.lang == "ko" %}
    {% include archive-single.html type=page.entries_layout %}
  {% endif %}
{% endfor %}
