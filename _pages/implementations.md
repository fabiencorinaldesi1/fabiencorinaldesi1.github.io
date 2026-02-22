---
layout: archive
title: "Implementations"
permalink: /implementations/
---

{% for post in site.implementations reversed %}
  <p>
    {% if post.external_link %}
      <!-- Lien externe -->
      <a href="{{ post.external_link }}" target="_blank" rel="noopener">{{ post.title }}</a>
    {% else %}
      <!-- Lien interne -->
      <a href="{{ post.url }}">{{ post.title }}</a>
    {% endif %}
    <br>
    <small>{{ post.date | date: "%Y" }}</small>
  </p>
{% endfor %}
