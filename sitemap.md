---
title: Sitemap
permalink: /sitemap/
layout: page
---

<!-- TODO: figure out why static files appear in this list.
MDG. -->

{% for p in site.pages %}
  {% unless p.sitemap_exclude %}
    * [{{ p.title }}]({{ p.url | absolute_url }})
  {% endunless %}
{% endfor %}
