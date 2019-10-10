---
layout: article
title: My Mirror is a Pitiful Thing
description: Book
tech: (Photography, book)
date: 2019-03-18 18:00:00
---
Soft-cover, 148 x 210mm (A5), 104 pages, uncut 8-page french fold signatures

Photography by Haryo Sukmawanto. Design by Yeliz Secerli.

One copy (excl shipping costs):&nbsp;&euro;25,-. To order, please send an e-mail to haryo.sukmawanto [at] gmail.com

<div>
{% for image in site.static_files %}
  {% if image.path contains '/img/articles/mymirrorbook/' %}
    <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}">
  {% endif %}
{% endfor %}
</div>
