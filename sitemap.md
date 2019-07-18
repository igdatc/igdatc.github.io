---
title: Sitemap
permalink: /sitemap/
layout: default
---

<!-- TODO: figure out why static files appear in this list.
MDG. -->

{% for p in site.pages %}
* [{{ p.title }}]({{ p.url | absolute_url }})
{% endfor %}


