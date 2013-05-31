---
layout: home
title: Stephen Wilson
tagline: Web Developer
icon: home
image: sunset-forth.jpg
---

## Latest Posts


<ul class="xicons-ul post post--list">
	<!-- <li><i class="icon-li icon-chevron-sign-right"></i> -->
{% for post in site.posts %}


	<li>
		<span class="bf post--date">{{ post.date | date: '%e' }} {{ post.date | date: '%B' }}, {{ post.date | date: '%Y' }} </span> 
		<h3 class="post--item"><a href="{{ post.url }}">{{ post.title }}</a></h3>
	</li>
	

{% endfor %}
</ul>