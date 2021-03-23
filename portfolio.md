---
layout: page
title: Portfolio
permalink: /portfolio/

layout: default
images:
  - image_path: /images/firstCardHolder/cardholder.jpg
    title: Card Holder
  - image_path: /images/firstCardWallet/cardwallet.jpg
    title: Card Wallet
  - image_path: /images/firstFacSgcWallet/fac5.jpg
    title: FAC / SGC Wallet 5
  - image_path: /images/firstPenCase/pencase1.jpg
    title: Pen Case 1
  - image_path: /images/puebloCardWallet/pcw1.jpg
    title: Pueblo Card Wallet 1
---

<ul class="portfolio">
  {% for image in page.images %}
    <li>
        <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
      
    </li>
  {% endfor %}
</ul>