---
layout: page
title: Downloads
permalink: /downloads/
---

{% assign documents_files = site.static_files | where: "documents", true %}

{% for mydocuments in dosucments_files %}
  {{ documents.path }}
{% endfor %}