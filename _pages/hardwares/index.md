---
layout: archive
title: "Hardwares"
permalink: /hardwares/
author_profile: true
redirect_from:
  - /year-archive/
---

{% include base_path %}

Unmanned Systems Ability Diagram
======

<figure>
  <iframe class="pdf-figure" src="{{ base_path }}/images/hardware/Drone_usage.pdf#toolbar=0&navpanes=0&scrollbar=0&view=FitH" title="Unmanned systems ability diagram"></iframe>
  <figcaption>Overview of my abilities for designing, tuning, and operating unmanned systems.</figcaption>
</figure>

Hardware Gallery
======

<div class="hardware-gallery">
  <figure>
    <div class="figure-row">
      <img src="{{ base_path }}/images/hardware/UAV_in_Lab_2025_8_Wide.jpg" alt="">
      <img src="{{ base_path }}/images/hardware/IMG_20221206_002827.jpg" alt="">
    </div>
    <figcaption>Universal UAV platform designed and built during my study at Xiamen University.</figcaption>
  </figure>
  <figure>
    <img src="{{ base_path }}/images/hardware/IMG_20221206_012332.jpg" alt="Robotic hardware setup">
    <figcaption>UAV test flight in a QR code searching mission.</figcaption>
  </figure>
  <figure>
    <img src="{{ base_path }}/images/hardware/Group_Photo_2014_11.jpg" alt="Team photo">
    <figcaption>My support during the 19th national college students technology competition, photoed with the team and my supervisor, Prof. Xiao Yu.</figcaption>
  </figure>
</div>


{% if site.hardwares.size > 0 %}
  {% for post in site.hardwares reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
Hardware projects will be updated separately.

Current focus areas include wheeled robots, unmanned aerial vehicles, embedded systems, and experimental robotic platforms.
{% endif %}
