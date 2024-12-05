---
title: Rijksdienst voor Verbetering van Gebaande Paden
layout: default
---
Bestuurlijk rollenspel voor gesprekken over waardenspanningen en dilemma’s op basis van casus van een fictieve overheidsorganisatie

# Spelregels

## Doel
Bewustwording

## Spelers
Elke deelnemer krijgt een rol met een zorg/dilemma om in gesprek te brengen.

## Casus

{% for casus in site.casus %}
- [{{ casus.title }}]({{ casus.url }})
{% endfor %}
