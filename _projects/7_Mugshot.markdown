---
layout: project
title: Mugshot.py
year: 2019
description: web application
img: /img/projects/mugshot/thumbnail_cropped.png
offsetx: -66%
offsety: -45%
---

Facial recognition systems are starting to become commonplace in our modern day society. Many major cities have implemented such systems in their CCTV systems and are being ostensibly used to combat crime.

Mugshot.py simulates such a facial recognition system using dlib face recognition, which boasts an accuracy of 99.38%. Its facial encoding library was created with publicly accessible mugshot imagery and the charges associated with each image. The user submits an image that contains one or multiple faces. Mugshot.py will then return the closest match, the accuracy percentage and the charges associated with the match.

[Try it out on Mugshot.py](https://www.mugshotpy.com/){: style="text-decoration:underline"}
[Source code](https://github.com/Fragrag/Mugshot){: style="text-decoration:underline"}

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/mugshot/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>



