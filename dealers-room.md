---
title: Dealers Room
layout: default
category: gallery
public: false

---
{% include jump_to.html content=site.data.dealers %}

# Online Dealers at Capricon

* Welcome to the Capricon Virtual Dealer Room!
* Our dealers have provided a selection of their goods for you to review. See something you like? Click the link to their store and and buy it! It's super easy.
* Many of our dealers accept custom orders. Look at those beautiful handmade creations. You know you want something made just for you.
* Browse away and enjoy all the goodies on offer! Sometimes a dealer has a coupon code for Capricon attendees. You deserve a treat in the middle of winter, don't you?
* Just click on one of these pictures to take a closer look:

{% for dealer in site.data.dealers %}{% include dealer_listing.html %}{% endfor %}