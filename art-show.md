---
title: Art Show
menus: exhibits
layout: default
category: room
public: true
order: 7

---
{% include jump_to.html content=site.data.artists %}

# Art Show

Welcome to the Capricon Virtual Art Show! For a closer look at the art, click on gallery images below:

{% for artist in site.data.artists %}{% include artist_listing.html %}{% endfor %}