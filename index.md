---
layout: page
title: zachphillips
---

<div class="posts">
  {% for post in site.posts limit:5 %}
    <div class="post">
		  {% if post.link %}<h1><a href="{{ post.link }}">{{ post.title }}</a></h1><a href="{{ post.link }}"><p class="small"><em>{{ post.link }}→</em></p></a>{% else %}<h1><a href="{{ post.url }}">{{ post.title }}</a></h1>{% endif %}
			{{ post.content }}
			<h4>Posted {{ post.date | date: "%A, %B %d, %Y" }}</h4>
		</div>
  {% endfor %}
</div>