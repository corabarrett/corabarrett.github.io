---
layout: page
title: Reading
permalink: /reading/
---

## Reading

I have read the following series of books while learning to become a better programmer.

<div class="sourceReading">
  {% for source in site.data.reading %}
  <ul class="read">
    <li>Title: <a href="{{ source.url }}" target="-blank">{{ source.title }}</a></li>
    <li>Author: {{ source.author }}</li>
    <li>Published: {{ source.date }}</li>
    <li>Type: {{ source.type }}</li>
  </ul>
  {% endfor %}
</div>
