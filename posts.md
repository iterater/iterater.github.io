---
layout: default
title: Blog
---
{% for post in site.posts %}
	{% if post.archive == false %}
		
		- [{{ post.date | date: "%A %-d %B %Y" }} - {{ post.title }}]({{ post.url | prepend: site.url }})
		
	{% endif %}
{% endfor %}