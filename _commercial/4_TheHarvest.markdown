---
layout: commercial
title: The Harvest
year: 2018-2019
client: Flor Maesen
client_url: https://www.flormaesen.com/
description: video projection, HD animation
img: /img/commercial/theharvest/190115_tded_42611.png
offsetx: -50%
offsety: -0%
---

_"De ijzersterke video van Flor Maesen verkent in slow motion het vergulde lichaam van een sculptuur. Afwisselend zoomt de camera langzaam in en uit, waardoor het lichaam tegen de zwarte achtergrond de vorm kan aannemen van een landschap, of een zonsondergang. Het goud en de verstilde cameravoering doen ons moeiteloos geloven dat het om een mythisch personage gaat. Wie lang genoeg kijkt, begrijpt geleidelijk aan zijn gebogen houding, als een ultieme expressie van zelfliefde."_

-Tamara Beheydt. ["Narcissus? bij Base-Alpha Gallery"](https://hart-magazine.be/expo/narcissus-bij-base-alpha-gallery), _HART_, 29 January 2020

In collaboration with the artist we created a looping animation of a floating golden figurine in Unreal Engine 4 as well as lending him general technical assistance.

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/commercial/theharvest' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
        <div class="col three caption"> Flor Maesen, The Harvest, 2019. Courtesy the artist </div>
    {% endif %}
{% endfor %}
</div>