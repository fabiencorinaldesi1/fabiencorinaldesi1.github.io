---
layout: archive
title: "Implementations"
permalink: /implementations/
---

{% for post in site.implementations reversed %}
  <p>
    <a href="{{ post.url }}" target="_blank" rel="noopener">{{ post.title }}</a><br>
    {{ post.date | date: "%Y" }}
  </p>
{% endfor %}
