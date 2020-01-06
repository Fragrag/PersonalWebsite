---
layout: project
title: Appropriated Spaces
year: 2013
description: 
img: /img/projects/appropriatedspaces/appropriatedspaces-4.jpg
offsetx: -65%
offsety: -50%
type: photography
---

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/projects/appropriatedspaces' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>