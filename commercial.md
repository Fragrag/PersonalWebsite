---
layout: page
permalink: /commercial/
title: commercial
description: commercial work
---

{% for project in site.commercial reversed %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
            <img class="thumbnail" style="left:{{ project.offsetx }} !important; top:{{ project.offsety }} !important;" src="{{ project.img }}"/>
        {% else %}
            <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h2>{{ project.title }}</h2>
            <br/>
            <p>Client: {{ project.client }}</p>
        </span>
        </a>
    </div>
</div>

{% endfor %}
