---
layout: page
title: Pueblo Card Wallet
permalink: /pueblocardwallet/

layout: default
images:
  - image_path: /images/puebloCardWallet/pcw1.jpg
    title: Pueblo Card Wallet 1
---

<ul class="pueblocardwallet">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>