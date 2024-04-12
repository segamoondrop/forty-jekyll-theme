---
layout: landing
title: Promotional Splatoon Mockups
description: Mockup promotional images for the game Splatoon. Showing various "Splatfest" contests and results. All created within Adobe Illustrator.<br/><br/>All handdrawn images are not my own and belong to their respective owners.
show_tile: false
link: https://www.youtube.com/embed/dbb-ndFlCkA
splatoon:
  name: splatoon
  images:
    - 
      src: /assets/images/splatoon/ACBVNIKKIVPKVFF.png
      alt: Nintendo 3DS Icon Splatfest Banner
    - 
      src: /assets/images/splatoon/Emote_Announcement.png
      alt: A promotional announcement image used to show off new Splatoon Squid emotes based on the 3DS Icons
    - 
      src: /assets/images/splatoon/Emotes.png
      alt: A collage of reference images and emotes to show the progress made in Adobe Illustrator
    - 
      src: /assets/images/splatoon/ACBVNIKKIBANNER.png
      alt: Arcade Bunny VS Nikki Splatfest Banner
    - 
      src: /assets/images/splatoon/NIKKIVPFBANNER.png
      alt: Nikki VS Parakeet Splatfest Banner
    - 
      src: /assets/images/splatoon/PKVFFBANNER.png
      alt: Parakeet VS Flipnote Frog Splatfest Banner
    - 
      src: /assets/images/splatoon/ACBVNIKKIWIN.png
      alt: Arcade Bunny VS Nikki Splatfest Results
    - 
      src: /assets/images/splatoon/NIKKIVPKWIN.png
      alt: Nikki VS Parakeet Splatfest Results
    - 
      src: /assets/images/splatoon/PKVFFWIN.png
      alt: Parakeet VS Flipnote Frog Splatfest Results
    - 
      src: /assets/images/splatoon/SLVPGBANNER.png
      alt: Slenderman VS Purple Guy Splatfest Banner
    - 
      src: /assets/images/splatoon/PSVHCBANNER.png
      alt: Pumpkin Spice VS Hot Chocolate Splatfest Banner
    - 
      src: /assets/images/splatoon/PSVHCWIN.png
      alt: Pumpkin Spice VS Hot Chocolate Splatfest Results
    - 
      src: /assets/images/splatoon/BKVBYBANNER.png
      alt: Bakugan VS Beyblade Splatfest Banner
    - 
      src: /assets/images/splatoon/BKVBYWIN.png
      alt: Bakugan VS Beyblade Splatfest Results
---
{% assign videos = site.data.splatoon %}
{%include videos.html %}

<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>Mockup Splatfest Images</h1>
        </header>
        {% assign gallery = page.splatoon %}
        {% include gallery.html %}
    </div>
</section>
