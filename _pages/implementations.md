---
layout: archive
title: "Implementations"
permalink: /implementations/
---

{% for post in site.implementations reversed %}
  <p>
    <a href="{{ post.url | default: post.external_link }}">{{ post.title }}</a><br>
    {{ post.date | date: "%Y" }}
  </p>
{% endfor %}
