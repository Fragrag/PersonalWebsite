---
layout: collaborations
title: Syntax Error
year: 2024
partner: Thomas Hunter
partner_url: https://www.thmshntr.com/
description: Interactive media installation
img: /img/collaborations/syntaxerror/syntaxerror1.jpg
offsetx: -80%
offsety: 0%
---

Syntax Error is an interactive media installation and the result of a collaboration with photographer Thomas Hunter. 

In Syntax Error, viewers observe the decay of an image. As more and more viewers gather in front of, the decay strengthens, hastening the distortion of the image.

This installation was set up and displayed at the exhibition 'A butterfly was finding out yesterday how to make sense of misunderstandings' in The Hague.

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/collaborations/syntaxerror' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>
