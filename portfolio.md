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
  - image_path: /images/firstFacSgcWallet/fac1.jpg
    title: FAC / SGC Wallet 1
  - image_path: /images/firstFacSgcWallet/fac2.jpg
    title: FAC / SGC Wallet 2
  - image_path: /images/firstFacSgcWallet/fac3.jpg
    title: FAC / SGC Wallet 3
  - image_path: /images/firstFacSgcWallet/fac4.jpg
    title: FAC / SGC Wallet 4
  - image_path: /images/firstFacSgcWallet/fac5.jpg
    title: FAC / SGC Wallet 5
  - image_path: /images/firstPenCase/pencase1.jpg
    title: Pen Case 1
  - image_path: /images/firstPenCase/pencase2.jpg
    title: Pen Case 2
  - image_path: /images/puebloCardWalet/pcw1.jpg
    title: Pueblo Card Wallet 1
  - image_path: /images/puebloCardWalet/pcw2.jpg
    title: Pueblo Card Wallet 2
  - image_path: /images/puebloCardWalet/pcw3.jpg
    title: Pueblo Card Wallet 3
  - image_path: /images/puebloCardWalet/pcw4.jpg
    title: Pueblo Card Wallet 4
  - image_path: /images/puebloCardWalet/pcw5.jpg
    title: Pueblo Card Wallet 5
---

<ul class="portfolio">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>