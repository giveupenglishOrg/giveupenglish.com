---
layout: default
---

<h1>{{ site.title }}</h1>
<ul>
{% for post in site.posts %}
<li>{{ post.date | date: "%Y-%m-%d" }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
