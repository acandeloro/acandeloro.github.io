---
layout: page
title: Gruppo Lettura su Husserl
description: Resoconti gruppo lettura su Husserl
permalink: /gruppo-lettura-husserl/
img: /assets/img/husserl.jpg
importance: 1
category: Filosofia
---

<div class="col-sm-6 col-md-6 col-xs-6">

              <div class="thumbnail" style="border:none; background:white;">

              <div class="col-sm-6 col-md-6 col-xs-12 image-container">
                <img src="assets/img/husserl.jpg" style="height:200px; margin-left:-15px;" />
              </div>

              <div class="col-sm-6 col-md-6 col-xs-12">  

                <h3>Hello World</h3>
                 <p style="font-size:10px; color:#03225C;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed hendrerit adipiscing blandit. Aliquam placerat, velit a fermentum fermentum, mi felis vehicula justo, a dapibus quam augue non massa.   </p>
              </div>
              </div>
 </div>


![husserl](assets/img/husserl.jpeg){: width="250" }

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
