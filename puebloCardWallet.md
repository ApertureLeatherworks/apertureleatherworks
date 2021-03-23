---
layout: page
title: Pueblo Card Wallet
permalink: /puebloCardWallet/

layout: default
images:
	- image_path: /images/puebloCardWallet/pcw1.jpg
    title: Pueblo Card Wallet 1
	- image_path: /images/puebloCardWallet/pcw2.jpg
    title: Pueblo Card Wallet 2
	- image_path: /images/puebloCardWallet/pcw3.jpg
    title: Pueblo Card Wallet 3
	- image_path: /images/puebloCardWallet/pcw4.jpg
    title: Pueblo Card Wallet 4
	- image_path: /images/puebloCardWallet/pcw5.jpg
    title: Pueblo Card Wallet 5
---

<ul class="puebloCardWallet">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>