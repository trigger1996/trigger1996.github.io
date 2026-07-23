---
layout: archive
title: "Softwares"
permalink: /softwares/
author_profile: true
redirect_from:
  - /talks/
---

{% include base_path %}

{% if site.softwares.size > 0 %}
  {% for post in site.softwares reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
Software projects will be updated separately.

Current focus areas include planning, control, observation, and formal synthesis software for robotic and discrete-event systems.
{% endif %}
