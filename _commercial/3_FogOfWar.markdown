---
layout: commercial
title: Fog of War
year: 2019
client: Xavier Mary
client_url: https://www.xaviermary.com/
description: video projection, HD animation
img: /img/commercial/fogofwar/fogofwar.jpg
offsetx: -66%
offsety: -10%
---

I lent the artist technical assistance in setting up the scene and lighting.

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/commercial/fogofwar' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>