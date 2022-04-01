---
layout: post
title:  "Beca interactiva"
author: hernan
categories: [ Inspiración ]
tags: [beca,jovenesbicentenario3.0,MTPE]
image: assets/images/16.jpg
---
Hola, ¡bienvenido al Reto de la beca!

{% assign width = include.width | times: 1.0 %}
{% assign height = include.height | times: 1.0 %}
{% assign paddingBottom = height | divided_by: width | times: 100 %}
<div class="video-holder" style="padding-bottom: {{ paddingBottom }}%">
  <iframe width="{{ include.width }}" 
          height="{{ include.height }}" 
          src="{{ include.url }}" 
          frameborder="0" 
          allowfullscreen></iframe>
</div>

{% include helpers/video.html url="https://kanancho.github.io/beca/" width="560" height="315" %}
