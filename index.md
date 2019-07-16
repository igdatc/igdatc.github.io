---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Welcome!
to the International Game Developers Association Twin Cities chapter.

We have two meetings a month, our MAIN MEETING is on the 2nd Wednesday.

We also have a VR & HCI meeting on the 4th (or sometimes 5th) Wednesday.

Please find registration for our events at IGDATC.eventbrite.com.

{% for contributor in site.github.contributors %}
	<a href='{{contributor.url}}'>
		<img src='{{contributor.avatar_url}}' alt='{{contributor.login}}' />
	</a>
{% endfor %}
