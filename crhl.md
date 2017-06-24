---
layout: page
title: "CRHL"
description: "Cercle de Recherche Historique de Lezennes."
---

Le Cercle de Recherche Historique de Lezennes est une association loi 1901 dont je
  suis le secrétaire depuis 2017.

Nous faisons des expositions sur des événements historique (les anciens bar, la guerre, ... ).
Nous éditons entre autres le coup d’œil. Un petit journal sur un élément de notre ville.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url}})
{% endfor %}