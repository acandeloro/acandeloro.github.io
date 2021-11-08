---
layout: page
title: Gruppo Lettura su Husserl
description: Resoconti gruppo lettura su Husserl
permalink: /gruppo-lettura-husserl/
img: /assets/img/husserl.jpg
importance: 1
category: Filosofia
---

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/husserl.jpg" alt=" ciao " width="500" height="600>
  </div>
  <div>
    <h2>Some title text</h2>
    <p>Some more text that will appear to the left of the image.</p>
  </div>
</div>

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
