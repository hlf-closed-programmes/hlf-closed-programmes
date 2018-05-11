---
layout: page
title: Downloads
permalink: /downloads/
---

{% for documents in site.static_files %}

  {% if image.path contains 'documents/' %}
    <img src="{{ image.path }}" alt="">
  {% endif %}
{% endfor %}
