---
title: Dealers Room
menus: exhibits
layout: default
category: gallery
public: false
order: 6

---
{% include jump_to.html content=site.data.dealers %}

# Online Dealers at Capricon

- possibly "Welcome to the Capricon Virtual Dealer Room!" or something of that nature

- consider whether to say "Here you will find pictures and links to online purchasing our dealers have provided for your perusal."

- discuss remote orders? Yes no? Such as: "Every dealer listed is happy to accept orders remotely and is prepared to ship any new goodies you would like to acquire."

- Then something like "We hope you enjoy your browsing!" or so forth.

- Will there be a live aspect through Discord? "We’re actually online, at the Con, in a virtual server, waiting to chat with you! Text and voice are available! Capricon is using Discord, and online virtual service, to let us talk to each other, just like we would if you were standing in a dealer booth." Then we would need a link to it.

For a closer look, click on gallery images below:

{% for dealer in site.data.dealers %}{% include dealer_listing.html %}{% endfor %}