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
        <h2><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></h2>
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
