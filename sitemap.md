---
title: Sitemap
permalink: /sitemap/
layout: page
---

<!-- TODO: figure out why static files appear in this list.
MDG. -->

{% for p in site.pages %}
  {% unless p.redirect_to %}
* [{{ p.title }}]({{ p.url | absolute_url }})
  {% endunless %}
{% endfor %}
