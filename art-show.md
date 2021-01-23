---
title: Art Show
menus: exhibits
layout: default
category: gallery
public: false
order: 7

---
{% include jump_to.html content=site.data.artists %}
<p class="jump">
  <a href="#art-show-chat">Art Show Discord Chat</a>
</p>

# Art Show

Welcome to the Capricon Virtual Art Show! For a closer look at the art, click on gallery images below:

{% for artist in site.data.artists %}{% include artist_listing.html %}{% endfor %}
<iframe
  frameborder="0"
  id="art-show-chat"
  class="convention-chat"
  width="100%"
  height="600px"
  src = "https://titanembeds.com/embed/788593711851896852?defaultchannel=802221524466794536?css=204"
>
</iframe>