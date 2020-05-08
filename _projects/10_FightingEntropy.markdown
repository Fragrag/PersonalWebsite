---
layout: project
title: Fighting Entropy
year: 2020
description: interactive video game
img: /img/projects/fightingentropy/FightingEntropy.png
offsetx: -50%
offsety: -10%
type: programming 3d gamedev
---

For the 46th edition of the [Ludum Dare gamejam](https://ldjam.com/), I joined forces with fellow Nerdlab members to create a video game from scratch in 72 hours.

We designed a game where you play a farmer managing a farm that starts to digitally glitch. To halt the glitching, the player harvests glitch plants with which you can halt the glitching.

Links:
- [Ludum Dare page](https://ldjam.com/events/ludum-dare/46/fighting-entropy){: style="text-decoration:underline"}
- [Windows Portable version](http://share.haryosukmawanto.com/FightingEntropy/FightingEntropy.zip){: style="text-decoration:underline"}
- [Source](https://github.com/VerscheldeAlynne/ludumDare46){: style="text-decoration:underline"}

Credits:
- Flore Alynne Verschelde
- Nathan Van Esbroeck 
- Haryo Sukmawanto

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/fightingentropy/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>
