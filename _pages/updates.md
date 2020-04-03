---
title: Updates
layout: page
---

<!-- This lists posts that are in the _posts folder --> 
<section class="posts">
<ul>
{% for post in site.posts %}
	<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%m-%d-%Y" }}</time></li>
{% endfor %}
</ul>
</section>
<!-- End of /posts list -->