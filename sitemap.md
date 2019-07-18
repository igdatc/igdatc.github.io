---
title: Sitemap
permalink: /sitemap/
layout: default
---

<!-- TODO: figure out why static files appear in this list. MDG. -->

{% for p in site.pages %}
{% if p.title != "" %}
* [{{ p.title |  }}]({{ p.url | absolute_url }})
{% endif $}
{% endfor %}


