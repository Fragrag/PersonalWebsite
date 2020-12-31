---
layout: project
title: Cyber Waves
year: 2020
description: site specific installation
img: /img/projects/cyberwaves/cyberwaves1.jpg
offsetx: -68%
offsety: -20%
type: programming 3d gamedev
---

Cyber Waves is a site specific installation created especially for [BULP2020](https://bulp.org/), an event organised by [Nerdlab](https://nerdlab.be/) to artists to project their works into the public space following the Covid19 lockdowns.

The site overlooks one of the main entrances by car into the city of Ghent and is regularily congested. Following the Covid19 measures and the transition to remote work for many workers, car traffic has declined significantly and the once busy road is now often deserted.

Cyber Waves is a work designed for the commuter, whose physical commutes have now been replaced by a digital one. It is a meditative work of digital rain drops falling into a puddle where the waves cascade and interact with each other. Using the CG concept of _normals_ which is a digital way of illustrating the orientation of a surface, the digital environment is evoked by this medley of cyber colours.

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/cyberwaves/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>
