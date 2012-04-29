---
layout: default
title: Home
header: Joe Hand
---
{% include JB/setup %}


<section id="content">
	<header><h3 id="today" class="date">Last Updated on {{ site.time | date: "%B %d, %Y" }}</h3></header>
	
{% for post in site.tags.featured %}
<article class="post">
    <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
	<h3 class="date"><time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date: "%b %d, %Y" }}</time></h3>
	
	{{ post.content }}
	
</article>
{% endfor %}
</section>