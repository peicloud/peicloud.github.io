---
layout: archive
title: "Academic Blog"
permalink: /blog/
author_profile: true
---

Welcome to my blog, where I share insights on ecological research, statistical methods, and R programming.

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
