---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /portfolio/
---

{% include base_path %}

{% if site.projects.size > 0 %}
  {% for post in site.projects reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
Project details will be updated separately.
{% endif %}
