---
layout: page
title: Gruppo Lettura su Husserl
description: Resoconti gruppo lettura su Husserl
permalink: /gruppo-lettura-husserl/
img: /assets/img/husserl.jpg
importance: 1
category: Filosofia
---


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/husserl.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

<div class="container-fluid">
  <div class="row">
    <div class="col-xl-6 col-lg-6 col-md-6">
      <img src="{{ '/assets/img/husserl.jpg' | relative_url }}" class="img-fluid" width="500">
    </div>
    <div class="col-xl-6 col-lg-6 col-md-6">
        In questa sezione potete trovare i resoconti del gruppo di lettura.

        ## Raccolta Husserl:

        Qui sono raccolti gli incontri tenuti sino ad ora su _La crisi delle scienze europee e la fenomenologia trascendentale_, edizione il saggiatore <a href="https://www.ilsaggiatore.com/libro/la-crisi-delle-scienze-europee-e-la-fenomenologia-trascendentale-2/">(link edizione)</a>.

        All'interno di ogni post vi si trovano le riflessioni sui capitoli letti prima dell'incontro. Vi è riportato anche un riassunto della discussione che è stata corretta e sistemata per essere leggibile. Potrebbero essere state apportate delle modifiche che non rispecchiano i pensieri di coloro che le hanno dette.
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
