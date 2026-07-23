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
  <div class="software-list">
    {% for post in site.softwares %}
      <article class="software-item">
        <h2>{{ post.title }}</h2>
        {% if post.website %}
          <p class="software-url">Website: <a href="{{ post.website }}">{{ post.website }}</a></p>
        {% endif %}
        {% if post.excerpt %}
          <p>{{ post.excerpt }}</p>
        {% endif %}
      </article>
    {% endfor %}
  </div>
{% else %}
Software projects will be updated separately.

Current focus areas include planning, control, observation, and formal synthesis software for robotic and discrete-event systems.
{% endif %}
