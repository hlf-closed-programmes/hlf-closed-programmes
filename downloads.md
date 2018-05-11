---
layout: page
title: Downloads
permalink: /downloads/
---

{% for documents in site.static_files %}

  {% if documents.path contains 'documents/' %}
    <img src="{{ documents.path }}" alt="">
  {% endif %}
{% endfor %}
