---
layout: home-inuit
title: Stephen Wilson
tagline: Web Developer
icon: home
image: sunset-forth.jpg
---

# Latest Posts


<div class="grid">
	<div class="grid__item  one-half  palm--one-whole">

		<div class="grid">

			<div class="grid__item  one-half  palm--one-whole">

				<div class="grid"> 
					<div class="grid__item">
						<p class="demo-block">Grid 1.1</p>
					</div>

					<div class="grid__item  lap-one-whole  one-third">
						<p class="demo-block">Grid 1.2</p>
					</div>
					<div class="grid__item  lap-one-whole  two-thirds">
						<p class="demo-block">Grid 1.3</p>
					</div>

				</div>

			</div>

			<div class="grid__item  one-half  palm-one-whole">

				<div class="grid">


					<div class="grid__item  one-half">
						<p class="demo-block">Grid 2.1</p>
					</div>

					<div class="grid__item  one-half">
						<p class="demo-block">Grid 2.2</p>
					</div>

					<div class="grid__item  lap--one-half  desk--one-third">
						<p class="demo-block">Grid 2.3</p>
					</div>

					<div class="grid__item  lap--one-half  desk--one-third">
						<p class="demo-block">Grid 2.4</p>
					</div>

					<div class="grid__item  desk--one-third">
						<p class="demo-block">Grid 2.5</p>
					</div>

				</div>

			</div>
		</div>
	</div>
</div>



		<ul class="xicons-ul post-list">
			<!-- <li><i class="icon-li icon-chevron-sign-right"></i> -->
			{% for post in site.posts %}


			<li>
				<span class="highlight">{{ post.date | date: '%e' }} {{ post.date | date: '%B' }}, {{ post.date | date: '%Y' }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a></span> 
			</li>


			{% endfor %}
		</ul>