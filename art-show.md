---
title: Art Show
layout: default
category: gallery
public: false
order: 7
menu:
  exhibits: {}

---
{% include jump_to.html content=site.data.artists %}
<p class="jump">
<a href="#art-show-chat">Art Show Discord Chat</a>
</p>

# Art Show

Welcome to the Capricon Virtual Art Show! 

We have a variety of art-related programming during the convention - [click here](https://guide.capricon.org/#prog/tag:Track%3AArt) to see a list of what's available.  To participate in our live Discord channel, click on the button above that says "Art Show Discord Chat" or scroll to the bottom of this page.

In the meantime, feel free to browse the artists participating in our virtual Art Show this year - you can click on any image to expand it.

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