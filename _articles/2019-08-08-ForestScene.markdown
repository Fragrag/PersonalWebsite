---
layout: article
title: Forest Cinematic
description: Short UE4 cinematic made during a weekend jam
tech: (Unreal Engine 4)
date: 2019-08-08 18:00:00
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/6pmkjdvZw7A" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/articles/forestscene/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>