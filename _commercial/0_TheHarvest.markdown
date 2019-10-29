---
layout: commercial
title: The Harvest
year: 2018-2019
client: Flor Maesen
description: 
img: /img/commercial/theharvest/190115_tded_42611.png
offsetx: -50%
offsety: -25%
---

HD Animation created in Unreal Engine 4 for visual artist <a style="text-decoration:underline" href="https://www.flormaesen.com/">Flor Maesen</a>

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/commercial/theharvest' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>