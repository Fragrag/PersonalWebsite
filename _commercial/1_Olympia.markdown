---
layout: commercial
title: Olympia
year: 2016-20xx
client: David Claerbout
client_url: https://davidclaerbout.com/Olympia-The-real-time-disintegration-into-ruins-of-the-Berlin-Olympic
description: two channel real-time projection, color, silent, HD animation, 1000 years
img: /img/commercial/olympia/Olympia.jpg
offsetx: -50%
offsety: -0%
---

_“Olympia is a computer-generated replica of the Olympic Stadium in Berlin, which finds itself in a time-space devoid of human intervention and entrusted to the cycles of nature. Following the original building theory, in which the stadium’s own decay has been pre-incorporated, Olympia invokes a precise cycle of creation to dissolution to rebuilding.”_
Artist’s statement

One of my main tasks as a technical assistant for acclaimed visual artist David Claerbout is to help him guide and manage the Olympia project and its future evolution over the years. This work has been installed and exhibited in many locations, such as the MNAC in Barcelona and M HKA in Antwerp. For more viewing information, please follow the link above to view more information on the piece.

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/commercial/olympia' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>