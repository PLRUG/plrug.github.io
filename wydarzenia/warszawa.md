---
layout: page
title: Wydarzenia - Warszawa
permalink: /wydarzenia/warszawa
---

Warszawska grupa użytkowników Ruby (PLRUG) działa od 201?.

Spotkania odbywają się w ?? miesiąca.

## Aktualni organizatorzy

- Oskar Lakner
- Mariusz Kozieł

## Social media

- [Discord PLRUG - kanał WRUG](https://discord.com/channels/929727331621306379/974672501022011393)
- [Facebook - WRUG](https://www.facebook.com/WRUGMeetup)
- [Facebook - PLRUG](https://www.facebook.com/PolishRubyUserGroup)

## Meetupy
<ul>
{% for post in site.categories.meetup %}
{% if post.categories contains "warszawa" %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
