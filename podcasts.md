<h1>The IGDATC Podcast</h1>

<h4>Listen on:</h4>
<ul>
  <li>
    <a href="http://itunes.apple.com/us/podcast/id420860430"
      target="_blank">iTunes</a>
  </li>
  <li>
    <a href="https://redcircle.com/shows/igda-twin-cities-podcast/"
      target="_blank">RedCircle</a>
  </li>
</ul>


{% assign year = "" %}

{% for post in site.categories.podcast %}
{% assign postyear = post.date | date: "%Y" %}

{% if year != postyear %}
{% assign year = postyear %}
### {{ year }}
{% endif %}

  * {{ post.date | date: "%m/%d" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
