---
layout: page
title: Wydarzenia - Poznań
permalink: /wydarzenia/poznan
---

Poznańska grupa użytkowników Ruby (PRUG - Poznań Ruby User Group) działa od 2012. 

Spotkania odbywają się w czwarty czwartek miesiąca.

## Aktualni organizatorzy

- Piotr Wasiak

## Social media

- [Discord PLRUG - kanał PRUG](https://discord.com/channels/929727331621306379/971508899159097387)
- [Discord PRUG](https://discord.gg/de3NvTHA)
- [Facebook](https://www.facebook.com/rubypoznan)
- [meetup](https://www.meetup.com/PoznanRUG/)
- [Oficjalna strona](https://ruby.poznan.dev/)
- [GitHub](https://github.com/prug)

## Meetupy

<ul>
{% for post in site.categories.meetup %}
{% if post.categories contains "poznan" %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
