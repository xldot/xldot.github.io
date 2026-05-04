---
layout: about
title: Home
nav: false
permalink: /
profile:
  align: right
  image: home_profile_aircraft.jpeg
  image_circular: false
  more_info: >
    <p>BCML Lab, Heriot-Watt University</p>
    <p>Supervised by Prof. Wei Pang</p>
social: false
---

<section class="home-overview">
  <p>{{ site.bio }}</p>
</section>

<section class="home-research">
  <h2>Research Interests</h2>

  <ul class="interest-grid">
{% for interest in site.research_interests %}
    <li class="interest-item">
      <span class="interest-index">{{ forloop.index | prepend: "0" }}</span>
      <span class="interest-label">{{ interest }}</span>
    </li>
{% endfor %}
  </ul>
</section>
