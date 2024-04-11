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
      alt: Nakoruru JP to ENG Comparison
    - 
      src: /assets/images/splatoon/Emote_Announcement.png
      alt: JP Nakoruru Title Screen
    - 
      src: /assets/images/splatoon/Emotes.png
      alt: ENG Nakoruru Title Screen
    - 
      src: /assets/images/splatoon/ACBVNIKKIBANNER.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/NIKKIVPFBANNER.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/PKVFFBANNER.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/ACBVNIKKIWIN.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/NIKKIVPKWIN.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/PKVFFWIN.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/SLVPGBANNER.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/PSVHCBANNER.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/PSVHCWIN.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/BKVBYBANNER.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/splatoon/BKVBYWIN.png
      alt: ENG Nakoruru Logo
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
