---
layout: commercial
title: The Harvest
year: 2018-2019
client: Flor Maesen
client_url: https://www.flormaesen.com/
description: video projection, HD animation
img: /img/commercial/theharvest/190115_tded_42611.png
offsetx: -50%
offsety: -0%
---

In collaboration with the artist we created a looping animation of a floating golden figurine in Unreal Engine 4 as well as lending him general technical assistance.

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/commercial/theharvest' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
        <div class="col three caption"> Flor Maesen, The Harvest, 2019. Courtesy the artist </div>
    {% endif %}
{% endfor %}
</div>