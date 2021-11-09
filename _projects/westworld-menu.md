---
layout: page
title: Westworld
description: 
permalink: /gruppo-lettura-husserl/
img: /assets/img/westworld.jpg
importance: 1
category: Cinema e Serie Tv
---


<div class="container-fluid">
  <div class="row">
    <div class="col-xl-6 col-lg-6 col-md-6">
      <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/westworld.jpg' | relative_url }}" class="img-fluid" width="300">
    </div>
  </div>
</div>

## Lista incontri

<div class="post">

  
  <ul class="post-list">
    {% for post in site.posts %}
    {% for tag in post.tags %}
    {% if tag == "westworld" %}
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
