---
title: Orsa Scholis
---

## Orsa Scholis

Ä Website für eusi ([@lukasbischof](https://github.com/lukasbischof), [@TheFehr](https://github.com/TheFehr)) Schuelprojekt und anderi gemeinsami Bastlereie

## Autorä
- Lukas Bischof [@lukasbischof](https://github.com/lukasbischof)
- Philipp Fehr [@TheFehr](https://github.com/TheFehr)

## Projekt
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
