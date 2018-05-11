---
layout: page
title: Downloads
permalink: /downloads/
---
{% assign file_files = site.static_files | where: "file", true %}
{% for myfile in file_files %}
  {{ myfile.path }}
{% endfor %}
