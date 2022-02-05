---
layout: projectlist
permalink: /collaborations/
title: collaborations
description: collaborations and commercial work
---

{% for project in site.collaborations reversed %}
<div class="project">
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
            <p>Partner: {{ project.partner }}</p>
        </span>
        </a>
    </div>
</div>
{% endfor %}

