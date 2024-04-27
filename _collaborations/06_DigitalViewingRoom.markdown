---
layout: collaborations
title: Digital Viewing Room
year: 2019
partner: Galerie Micheline Szwajcer
partner_url: https://www.gms.be/
description: Web, virtual environment
img: /img/collaborations/digitalviewingroom/dvr_still.jpg
offsetx: -66%
offsety: -10%
---

For Galerie Micheline Szwajcer I developed a digital viewing room featuring David Claerbout's artwork _"the 'confetti' piece"_.

This viewing room is a 3D environment in which the artwork is projected onto the walls. The viewer is provided with a set of controls with which they can approach the artwork or turn their view towards a projection.

The environment was developed with the [three.js library](https://threejs.org/) in TypeScript. It is hosted on an HTTP server while the video has been offloaded to a DigitalOcean VM to accomodate the high traffic that was encountered after publishing.

The viewing room is available for viewing until July 17, 2020 and can be accessed via [Galerie Micheline Szwajcer's website](https://www.gms.be/index.php?content=exhib_detail&id_image=7881&id_exhibition=347&is_onlineviewingroom=1).

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/collaborations/digitalviewingroom' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
        <div class="col three caption"> David Claerbout, the "confetti" piece, 2015-2018. </div>
    {% endif %}
{% endfor %}
</div>