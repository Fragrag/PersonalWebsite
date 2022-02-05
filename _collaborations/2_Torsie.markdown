---
layout: collaborations
title: Torsie
year: 2018
partner: Renée Strikkeling
partner_url: https://graduation.schoolofarts.be/student/renee-strikkeling/
description: web application
img: /img/collaborations/torsie/Torsie.JPG
offsetx: -50%
offsety: -0%
---

In collaboration with the artist we looked for a way to display the versatility of the torsion of strings and the impact it has on a fabric as a whole.

Using Javascript and the p5.js library I created a website that displays a variety of fabric patterns and structures. The user can dynamically change the colors of the patterns, letting them see the impact it has on it and showing the infinite possibilities

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/collaborations/torsie' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>