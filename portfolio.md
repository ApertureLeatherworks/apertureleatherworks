---
layout: page
title: Portfolio
permalink: /portfolio/

layout: default
images:
  - image_path: /images/firstCardHolder/cardholder.jpg
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>