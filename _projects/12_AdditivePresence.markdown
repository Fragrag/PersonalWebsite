---
layout: project
title: Additive Presence
year: 2023
description: led panel installation
img: /img/projects/additivepresence/additivepresence1.png
offsetx: -68%
offsety: -20%
type: programming art
---

Additive Presence is an experimental installation that looks into new possibilities of interaction between two remote parties. Using two LED panels and webcams that have been set up in separate locations, visitors are encouraged to move in front of these panels and discover new methods of interaction between local and remote parties.

Additive Presence was a project developed for [BYOB2023](https://nerdlab.be/byob), an event organised by [Nerdlab](https://nerdlab.be/).

[Source code available on GitHub](https://github.com/haryo-s/ripples){: style="text-decoration:underline"}

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/additivepresence/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>
