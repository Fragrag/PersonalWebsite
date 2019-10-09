---
layout: project
title: Monumen Diam
year: 2016-2017
description: dual channel video projection, HD animation
img: /img/projects/monumendiam/tugutani_still_099.jpg
highlighter: none
---
This video installation shows 3D scans of two statues in Indonesia coupled with the testimony of a former political prisoner on the prison island Buru. The viewer orbits the faulty and fragmented depictions of the statues while they listen to the interview where I discover aspects of their lives that had never been shared before.

By coupling these results with the interviews I conducted, these questions are applied parallel to the process of working with historical facts. 

Over the course of this project, I created a rough outline of the victims' life and story, but arguably it is just as fragmented as these statues. 

Several questions arise: how many more interviews do I need to conduct, how many more historical documents do I need to analyze, how many gaps do I need to fill in myself, before I get something that approximates what happened?

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/monumendiam/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>