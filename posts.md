---
layout: default
title: Blog [RU]
---
{% for post in site.posts %}
	
- {{ post.date | date: "%Y-%m-%d" }} - [{{ post.title }}]({{ post.url | prepend: site.url }})
		
{% endfor %}