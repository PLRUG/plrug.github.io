---
layout: page
title: Wydarzenia
permalink: /wydarzenia/
---

<h3>Conferences</h3>
<ul>
{% for post in site.categories.conference %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<h3>Meetups</h3>
<ul>
{% for post in site.categories.meetup %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
