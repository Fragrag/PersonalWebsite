---
layout: project
title: My Mirror is a Pitiful Thing
year: 2014-2017
description: 
img: /img/projects/mymirror/koblen7-edit.jpg
offsetx: -66%
offsety: -5%
---

In *My Mirror is a Pitiful Thing*, I handle the fragmented narrative of the 1965 Indonesian Communist Purge. I confront the concealment of survivors's experiences and their refusal to speak about it and I question its place in history, as well as my own position while dealing with it.

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/mymirror/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>