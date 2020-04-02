---
title: Live Like A Hydra
layout: page
path: /
---

This is a personal mythology that helps us grow even when things are chaotic.

<section class="posts">
<ul>
{% for post in site.posts %}
	<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%m-%d-%Y" }}</time></li>
{% endfor %}
</ul>
</section>