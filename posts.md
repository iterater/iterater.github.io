---
layout: default
title: Blog
---
{% for post in site.posts %}
	
- [{{ post.date | date: "%A %-d %B %Y" }} - {{ post.title }}]({{ post.url | prepend: site.url }})
		
{% endfor %}