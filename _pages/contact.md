---
layout: page
title: Contact
permalink: /contact
comments: false
---
Conoce más sobre Hernán [aquí](http://www.hernangarciaval.com).
En dicha web recopila algunas experiencias y conocimientos adquiridos.
Puedes escribirle a *dm@hernangarciaval.com*


<h1>Título</h1>
<ul class="posts">
  {% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> » 
  <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>

En todo caso, puedes inscribir tu correo para recibir nueestras historias dejando tu e-mail acá abajo
