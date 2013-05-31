---
layout: home-inuit
title: Stephen Wilson
tagline: Web Developer
icon: home
image: sunset-forth.jpg
---

# Latest Posts

<ul class="xicons-ul post-list">
	<!-- <li><i class="icon-li icon-chevron-sign-right"></i> -->
{% for post in site.posts %}


	<li>
		<span class="highlight">{{ post.date | date: '%e' }} {{ post.date | date: '%B' }}, {{ post.date | date: '%Y' }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a></span> 
	</li>
	

{% endfor %}
</ul>