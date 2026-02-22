---
layout: archive
title: "Implementations"
permalink: /implementations/
---

{% for post in site.implementations reversed %}
  <p>
    <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%Y" }}
  </p>
{% endfor %}
