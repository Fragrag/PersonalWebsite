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

Together with the artist we set up the scene and lighting in 3ds max and Arnold.

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/commercial/fogofwar' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
        <div class="col three caption"> Xavier Mary, Fog of War (Aer), 2019. Courtesy the artist </div>
    {% endif %}
{% endfor %}
</div>