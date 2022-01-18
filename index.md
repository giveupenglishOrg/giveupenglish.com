---
layout: default
---

<h1><a href="/">{{ site.title }}</a></h1>
<ul>
{% for post in site.posts %}
<li>{{ post.date | date: "%Y-%m-%d" }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
<p>{{ post.description }}</p>
{% endfor %}
</ul>
