---
layout: default
title: Creativitas
description : Welcome to my site creativitas web app in github.
---
<ul>
{% for post in site.posts %}
<li class="p-1">
<h3><strong><a href="{{ post.url }}">{{ post.title }}</a></strong></h3>
<p>{{post.description}}</p>
</li>
  {% endfor %}
</ul>