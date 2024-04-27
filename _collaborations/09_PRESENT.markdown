---
layout: collaborations
title: PRESENT
year: 2020-2022
partner: CREW, PRESENT
partner_url: https://www.upf.edu/web/present
description: Research, XR
img: /img/collaborations/present/present1.jpg
offsetx: -50%
offsety: 12.5%
---

PRESENT was a three-year EU Research and Innovation project between 8 companies and research institutions to create virtual digital humans -sentient agents- that look entirely naturalistic, demonstrate emotional sensitivity, establish an engaging dialogue, add sense to the experience, and act as trustworthy guardians and guides in the interfaces for AR, VR, and more traditional forms of media.

CREW was a partner in this project, together with other companies and research institutions such as Framestore, Inria and Brainstorm.

In the course of this research project, CREW researched how users engaged virtual sentient agents in a live setting. They developed projects that implemented experimental technologies from their research partners. By deploying and presenting these projects to the general public, CREW was able to gather valuable data and feedback that tremendously assisted development. One of these projects, Delirious Departures, was performed at SIGGRAPH 2022 in Vancouver.

My tasks included the implementation of these experimental technologies in CREW's projects and performances, as well as delivering technical feedback to partners. 

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/collaborations/present' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>
