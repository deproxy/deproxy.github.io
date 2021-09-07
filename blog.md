---
layout: default
title: "Blog"
---

{% if site.show_excerpts %}
  {% include index.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
