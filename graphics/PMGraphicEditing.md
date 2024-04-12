---
layout: landing
title: Precise Museum Graphic Editing
description: <span>These graphics are recreated by eye for the unofficial translation patches of Puyo Puyo games. Some images show a work in-progress build, edits to dialogue/text have not been changed.<br/><br/>Precise Museum is a fan translation team for Puyo Puyo media; including manga, drama CD's, and the games themselves.<br/>Please support the official releases!<br \><br \><a target=_blank href='https://www.precisemuseum.com/'>https://www.precisemuseum.com/</a></span>
image: assets/images/games/gizmosgambit/gizmos_gambit.png
show_tile: false
link: https://www.youtube.com/embed/dbb-ndFlCkA
beforeafter:
  name: BeforeAndAfter
  images:
    - 
      src: /assets/images/pmgallery/1.png
      alt: Before and After 1
    - 
      src: /assets/images/pmgallery/2.png
      alt: Before and After 2
    - 
      src: /assets/images/pmgallery/3.png
      alt: Before and After 3
    - 
      src: /assets/images/pmgallery/4.png
      alt: Before and After 4
    - 
      src: /assets/images/pmgallery/5.png
      alt: Before and After 5
    - 
      src: /assets/images/pmgallery/6.png
      alt: Before and After 6
---
{% assign videos = site.data.pmGraphics %}
{%include videos.html %}

<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>Before and After</h1>
        </header>
        {% assign gallery = page.beforeafter %}
        {% include gallery.html %}
    </div>
</section>
