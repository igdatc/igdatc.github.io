---
title: Events
permalink: /events/
layout: page
---

{% assign year = "" %}

{% for post in site.categories.events %}
{% assign postyear = post.date | date: "%Y" %}

{% if year != postyear %}
{% assign year = postyear %}
### {{ year }}
{% endif %}

  * {{ post.date | date: "%m/%d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
