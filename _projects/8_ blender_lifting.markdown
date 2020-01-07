---
layout: project
title: blender_lifting
year: 2019
description: blender 2.8 plugin
img: /img/projects/blenderlifting/example.png
offsetx: -7%
offsety: -0%
type: programming 3d
---

blender_lifting is a Blender addon that implements the functionality from Denis Tome' research paper _Lifting from the Deep: Convolutional 3D Pose Estimation from a Single Image_, which uses machine learning to estimate a 3D pose from a 2D image. More information can be found about this can be found in its [GitHub repository](https://github.com/DenisTome/Lifting-from-the-Deep-release){: style="text-decoration:underline"} and [its associated research paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tome_Lifting_From_the_CVPR_2017_paper.pdf){: style="text-decoration:underline"}. 

This addon will take an image of a person, estimate its pose and create a rigged skeleton in Blender in that pose, as illustrated in the example below.

[Source code and addon available on GitHub](https://github.com/Fragrag/blender_lifting){: style="text-decoration:underline"}

<hr>

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/projects/blenderlifting/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>



