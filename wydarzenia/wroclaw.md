---
layout: page
title: Wydarzenia - Wrocław
permalink: /wydarzenia/wroclaw
---

Dolnośląska grupa użytkowników Ruby (DRUG) działa od 201?.

Spotkania odbywają się w ?? miesiąca.

## Aktualni organizatorzy

## Social media

- [Discord PLRUG - kanał DRUG](https://discord.com/channels/929727331621306379/971508934072483880)
- Slack DRUG - zaproszenie dostępne u organizatorów
- [Facebook](https://www.facebook.com/drugpl)
- [Oficjalna strona](https://drug.org.pl/)
- [meetup](https://www.meetup.com/drugpl/)
- [Email - all@drug.org.pl](mailto:all@drug.org.pl)
- [GitHub](https://github.com/drugpl)
- [Twitter](https://twitter.com/drugpl)

<h3>Konferencje</h3>
<ul>
{% for post in site.categories.conference %}
{% if post.categories contains "wroclaw" %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>

<h3>Meetupy</h3>
<ul>
{% for post in site.categories.meetup %}
{% if post.categories contains "wroclaw" %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
