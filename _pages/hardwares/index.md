---
layout: archive
title: "Hardwares"
permalink: /hardwares/
author_profile: true
redirect_from:
  - /year-archive/
---

{% include base_path %}

Hardware Gallery
======

<div class="hardware-gallery">
  <figure>
    <img src="{{ base_path }}/images/hardware/UAV_in_Lab_2025_8_Wide.jpg" alt="UAV platform in laboratory">
    <figcaption>UAV platform in laboratory.</figcaption>
  </figure>
  <figure>
    <img src="{{ base_path }}/images/hardware/IMG_20221206_002827.jpg" alt="Hardware experiment platform">
    <figcaption>Hardware experiment platform.</figcaption>
  </figure>
  <figure>
    <img src="{{ base_path }}/images/hardware/IMG_20221206_012332.jpg" alt="Robotic hardware setup">
    <figcaption>Robotic hardware setup.</figcaption>
  </figure>
  <figure>
    <img src="{{ base_path }}/images/hardware/Group_Photo_2014_11.jpg" alt="Team photo">
    <figcaption>Team photo.</figcaption>
  </figure>
</div>

[Unmanned systems ability diagram]({{ base_path }}/images/hardware/Drone_usage.pdf)

{% if site.hardwares.size > 0 %}
  {% for post in site.hardwares reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
Hardware projects will be updated separately.

Current focus areas include wheeled robots, unmanned aerial vehicles, embedded systems, and experimental robotic platforms.
{% endif %}
