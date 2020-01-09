---
layout: page
title: Authors
image: /files/covers/author.jpg
permalink: /authors/
sitemap:
  priority: 0.7
---
{% for author in site.authors %}
* [{{ author.name }}]({{ site.baseurl }}/authors/{{ author.name }})
{% endfor %}
