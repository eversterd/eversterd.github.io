---
layout: page
title: Fiat lux
tagline: Supporting tagline
---
{% include JB/setup %}

Read [eversterd](https://eversterd.github.io)


Here's a sample "posts list".

<div id="content">
    <div class="text-post posts">

	{% for post in site.posts limit:5 %}

		<h2><a class="post_title" href="{{ post.url }}">{{post.title}}</a></h2>

		<div class="caption rich-content">
			{{ post.content }}
		</div>

	{% endfor %}

    </div>
</div>
