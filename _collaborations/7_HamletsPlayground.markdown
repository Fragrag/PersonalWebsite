---
layout: collaborations
title: Hamlet's Playground
year: 2021
partner: CREW
partner_url: https://crew.brussels/en
description: Web, virtual theatre
img: /img/collaborations/hamletsplayground/hamletsplayground.jpg
offsetx: -72%
offsety: -0%
---

_The futuristic production Hamlet’s Lunacy by Eric Joris and Mesut Arslan was transformed by CREW in collaboration with Monty Kultuurfaktorij into Hamlet’s Playground, a corona-proof interactive theatrical experience happening simultaneously live and online._

_For this new theatre experience, CREW puts their own spin on the [Gather platform](https://www.gather.town/). No more boring streaming and passive watching. As an avatar — a digital persona — the audience plays an active part. Live actors guide the audience in a console game-like environment through various rooms, where historical documents and technology provide new insight in Hamlet’s conflict._

As a member of the technical team behind this performance, I took on the responsibility of the technical aspects relating to the [Gather platform](https://www.gather.town/). I developed a wrapper for the platform's HTTP API in Python, allowing for mid-performance interventions such as dynamic map and lighting changes. This Python wrapper was released on [Github as an open-source project](https://github.com/Crew-VZW/PyGather) and still serves as a reference for developers in the Gather Community.

To serve as costume changes, I developed several AR Filters to be used by the actors, allowing them to change their appearances and let them switch roles. I also created an short animation film in 8-bit style that was used as an introduction to the story of Hamlet.

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/collaborations/hamletsplayground' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>