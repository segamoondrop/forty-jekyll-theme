---
layout: landing
title: DJ Usachi
description: <span>A PSX Styled 3D Platformer with a City Night aesthetic. Help Usachi try to collect all of her missing vinyls!<br /><br />DJ Usachi is a solo-developed gameplay demo made under 10 days for a Game Design class project. Music is not my own.<br /><br /><a target=_blank href='https://sega-moondrop.itch.io/dj-usachi'>https://sega-moondrop.itch.io/dj-usachi</a></span>
image: assets/images/games/djusachi/DJBunnyTitleScreen.png
show_tile: false
link: https://www.youtube.com/embed/bUGgRmr74hg?si=d0mkLMoMe-aajaKD
designs:
    name: usachiDesigns
    images:
        -
            src: /assets/images/games/djusachi/DJ_Bunny_1.png
            alt: DJ Bunny 1
        -
            src: /assets/images/games/djusachi/DJ_Bunny_2.png
            alt: DJ Bunny 2
        -
            src: /assets/images/games/djusachi/DJ_Bunny_3.png
            alt: DJ Bunny 3
        -
            src: /assets/images/games/djusachi/DJ_Usachi_Original_Drawing.png
            alt: DJ Usachi Original Drawing
coding:
    name: usachiUnity
    images:
        -
            src: /assets/images/games/djusachi/UnityUsachi.png
            alt: DJ Usachi Unity Screenshot 1
        -
            src: /assets/images/games/djusachi/UnityUsachi_2.png
            alt: DJ Usachi Unity Screenshot 2
---
{% assign videos = site.data.djUsachi %}
{%include videos.html %}
<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>The Journey</h1>
        </header>
        <h2 id="design">Design</h2>
        <p>From the start, I knew I had wanted to create a mascot platformer. So the first step was to design the main character. After brainstorming many ideas, I settled on a DJ Bunny and began drawing. Below you can find some of the alternate designs before settling on DJ Usachi herself!</p>
        {% assign gallery = page.designs %}
        {% include gallery.html %}
        <h2 id="modeling">Modeling & Animation</h2>
        <!-- Use the span image left or right classes to put a single image down. -->
        <p><span class="image left"><img src="{% link assets/images/games/djusachi/DJ_Usachi_Original_Blender_Model.png %}" alt="" /></span>Once the character was designed, it was time to make it a functional model. I began to quickly research Blender and found out how to animate and implement animations in-game within 3 days.</p>
        <!-- Add the "clear: left or right or both" style to force a new section to move below a floating image -->
        <h2 id="coding" style="clear: left">Unity & Coding</h2>
        <p>Unity itself was actually quite simple to learn! I had implemented particle effects, learned how to implement shaders and got familiar with Unity engine as a whole. Then came the difficult part for me: coding. I had used a YouTube tutorial for the games main physics and control to get a hang of Visual Code Studio. </p>
        {% assign gallery = page.coding %}
        {% include gallery.html %}
        <h2 id="results">Results</h2>
        <p>With all of that together, the short game demo was complete! You can check out a short gameplay demo below. Progress on the game has stopped for now, but I would love to pick it up in the future.</p>
    </div>
<section>

{% assign videos = site.data.djUsachiEnd %}
{%include videos.html %}

