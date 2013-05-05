---
layout: page
title: Stephen Wilson
tagline: Web Developer
---
{% include JB/setup %}

# Welcome

I'd thought I would give jeykll a go and found jeykll-bootstrap for blogging
    
## Post List

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




