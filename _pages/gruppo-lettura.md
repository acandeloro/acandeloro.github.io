---
layout: page
title: Gruppo lettura
permalink: /gruppo-lettura/
<!-- description: Qui ci sono gli articoli di Filosofia -->
<!-- nav: true -->
---


In questa sezione potete trovare i resoconti del gruppo di lettura.

## Raccolta Husserl:

Qui sono raccolti gli incontri tenuti sino ad ora su _La crisi delle scienze europee e la fenomenologia trascendentale_, edizione il saggiatore <a href="https://www.ilsaggiatore.com/libro/la-crisi-delle-scienze-europee-e-la-fenomenologia-trascendentale-2/">(link edizione)</a>.

All'interno di ogni post vi si trovano le riflessioni sui capitoli letti prima dell'incontro. Vi è riportato anche un riassunto della discussione che è stata corretta e sistemata per essere leggibile. Potrebbero essere state apportate delle modifiche che non rispecchiano i pensieri di coloro che le hanno dette.

<div class="post">

  
  <ul class="post-list">
    {% for post in site.posts %}
    {% for tag in post.tags %}
    {% if tag == "gruppolettura" %}
        <li>
        <h3><a class="post-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
        <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p>
        <p>{{ post.description }}</p>
        </li>
    {% endif %}
    {% endfor %}
    {% endfor %}
  </ul>

</div>
