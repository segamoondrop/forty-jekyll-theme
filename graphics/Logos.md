---
layout: landing
title: Logos
description: Logos created within Adobe Photoshop & Illustrator.
show_tile: false
link: https://www.youtube.com/embed/dbb-ndFlCkA
logos:
  name: logos
  images:
    - 
      src: /assets/images/logos/nakorurucomparison.png
      alt: Nakoruru JP to ENG Comparison
    - 
      src: /assets/images/logos/JPNakoruru.png
      alt: JP Nakoruru Title Screen
    - 
      src: /assets/images/logos/ENGNakoruru.png
      alt: ENG Nakoruru Title Screen
    - 
      src: /assets/images/logos/nakoruruglow.png
      alt: ENG Nakoruru Logo
    - 
      src: /assets/images/logos/wth2022logo.png
      alt: Logo for an event called Winner Takes Halal 2022 for the game club known as Halal Gaming
---
{% assign videos = site.data.logos %}
{%include videos.html %}

<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>Logos</h1>
        </header>
        {% assign gallery = page.logos %}
        {% include gallery.html %}
    </div>
</section>
