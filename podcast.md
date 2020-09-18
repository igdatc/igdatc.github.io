---
layout: default
title: The IGDATC Podcast
---

<a href='https://redcircle.com/shows/igda-twin-cities-podcast/' class='btn btn-sm btn-outline-primary' target="_blank">Listen on RedCircle</a>
<a href='http://itunes.apple.com/us/podcast/id420860430' class='btn btn-sm btn-outline-primary' target="_blank">Listen on iTunes</a>

{% assign year = "" %}

{% for post in site.categories.podcast %}
{% assign postyear = post.date | date: "%Y" %}

{% if year != postyear %}
{% assign year = postyear %}
### {{ year }}
{% endif %}

  * {{ post.date | date: "%m/%d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
