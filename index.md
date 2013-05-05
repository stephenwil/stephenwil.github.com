---
layout: page
title: Stephen Wilson
tagline: Web Developer
---
{% include JB/setup %}

# Welcome

I'd thought I would give jekyll a go and found jekyll-bootstrap for blogging
    
## Post List

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




