---
layout: page
title: Filosofia della scienza
permalink: /filosofia-scienza/
description: Qui ci sono gli articoli di Filosofia
<!-- nav: true -->
---




<div class="post">

  

  <ul class="post-list">
    {% for post in site.posts %}
    {% for tag in post.tags %}
    {% if tag == "filosofia" %}
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
