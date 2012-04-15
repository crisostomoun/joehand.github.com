---
layout: page
title: Hello World!
tagline: Welcome to my _temporary_ internet home. Perhaps it will be temporarily permanent.
---
{% include JB/setup %}

{{ page.tagline }}


<a href="/about.html"><pre>Joe Hand</pre></a>

>	Resident of Portland, Oregon.

>	Information explorer, bike commuter, average joe.

>	_Doing Good with Data_ at [Periscopic](http://periscopic.com), Project Manager.

	


<!---

	From My Own Two Hands

{% for category in site.categories %}

<ul class="posts list_style_none">
<h3 class="unit-head-inner" id="{{ category[0] }}-ref"><a href="/categories.html#{{ category[0] }}-ref">{{ category[0] | join: "/" }}</a></h3>

  {% for post in site.tags.featured %}

{% if post.category == category[0] %}

    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
  {% endfor %}
	
</ul>
	{% endfor %}

	-->
