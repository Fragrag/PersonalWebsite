---
layout: project
title: Water World We Live In
description: 
img: /img/projects/waterworld/waterworld-1.jpg
---

<p>Bodies of water are common destinations of leisure where people come to sport or relax. They are augmented with significant infrastructure to support these activities. These environments have usually been distorted to accommodate the demands of these activities, becoming approximations of what they represent.</p>

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/projects/waterworld' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>