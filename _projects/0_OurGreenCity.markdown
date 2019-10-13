---
layout: project
title: Our Green City
year: 2011
description: 
img: /img/projects/ourgreencity/ourgreencity-8.jpg
offsetx: -50%
offsety: -25%
---

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/projects/ourgreencity' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>