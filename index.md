---
layout: default
title: Welcome!
---

to the International Game Developers Association Twin Cities chapter.

We have two meetings a month, our MAIN MEETING is on the 2nd Wednesday.

We also have a VR & HCI meeting on the 4th (or sometimes 5th) Wednesday.

Please find registration for our events at IGDATC.eventbrite.com.

Contributors:

{% for contributor in site.github.contributors %}
	{{ contributor.login }}
{% endfor %}

Files:
{% for file in site.static_files %}
	{{file.name}}
{% endfor %}
