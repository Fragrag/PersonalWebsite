---
layout: project
title: Bitrot
year: 2019
description: custom software, variable dimensions, portrait
img: /img/projects/bitrot/grandma_finalframe.png
offsetx: -90%
offsety: -85%
---

In BITROT, we see two screens. On each one is a photograph of the artist's grandparents on their wedding day. On the left we see his grandfather step out of a car, on the right is his grandmother being held by the hand by presumably his great-grandmother.

While the installation is active, a bit in each image will periodically be flipped, irrecoverably corrupting the image pixel by pixel. In time, these images will become random noise, with no semblance to what they originally represented.

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/bitrot/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>



