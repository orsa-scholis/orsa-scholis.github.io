---
title: Orsa Scholis
---

## Orsa Scholis

Än Website für eusi Schuelprojekt

## Autorä
- Lukas Bischof
- Philipp Fehr

## Projekt
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
