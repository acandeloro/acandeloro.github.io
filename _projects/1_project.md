---
layout: page
title: Gruppo Lettura su Husserl
description: Resoconti gruppo lettura su Husserl
permalink: /gruppo-lettura-husserl/
img: /assets/img/husserl.jpg
importance: 1
category: Filosofia
---


<div class="container-fluid">
  <div class="row">
    <div class="col-xl-6 col-lg-6 col-md-6">
      <img src="{{ '/assets/img/husserl.jpg' | relative_url }}" class="img-fluid" width="300">
    </div>
    <div class="col-xl-6 col-lg-6 col-md-6">
        <p>
        In questa sezione potete trovare i resoconti del gruppo di lettura riguardanti la lettura de "La crisi delle scienze europee e la fenomenologia trascendentale", edizione il saggiatore <a href="https://www.ilsaggiatore.com/libro/la-crisi-delle-scienze-europee-e-la-fenomenologia-trascendentale-2/">(link edizione)</a>.
        </p>
        <p>
        All'interno di ogni post vi si trovano le riflessioni sui capitoli letti prima dell'incontro. Vi è riportato anche un riassunto della discussione che è stata corretta e sistemata per essere leggibile. Potrebbero essere state apportate delle modifiche che non rispecchiano i pensieri di coloro che le hanno dette.
        </p>
    </div>
  </div>
</div>



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
