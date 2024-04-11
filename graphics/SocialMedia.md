---
layout: landing
title: Social Media
description: Various social media assets created within Adobe Photoshop & Illustrator.
show_tile: false
link: https://www.youtube.com/embed/dbb-ndFlCkA
banners:
  name: banners
  images:
    - 
      src: /assets/images/socialmediagallery/jomammisbanner.png
      alt: Jo_Mammis Banner for Twitter/X
    - 
      src: /assets/images/socialmediagallery/moondropbanner.png
      alt: Sega_Moondrop Banner for Twitter/X
    - 
      src: /assets/images/socialmediagallery/qabanner.png
      alt: My Personal LinkedIn Banner
twitchbuttons:
  name: twitch
  images:
    - 
      src: /assets/images/socialmediagallery/sonictwitchpanels.png
      alt: Sonic-Inspired Twitch Panels
    - 
      src: /assets/images/socialmediagallery/fallguyspanels.png
      alt: Fall Guys-Inspired Twitch Panels
---
{% assign videos = site.data.socialMedia %}
{%include videos.html %}

<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>Social Media Banners</h1>
        </header>
        {% assign gallery = page.banners %}
        {% include gallery.html %}
        <br/><hr/><br/>
        <header class="major">
            <h1>Twitch Buttons</h1>
        </header>
        {% assign gallery = page.twitchbuttons %}
        {% include gallery.html %}
    </div>
</section>
