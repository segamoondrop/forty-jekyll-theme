---
layout: landing
title: Gizmos Gambit
description: <span>Credits&#58; UI Design/QA Tester<br /><br />A shoot-em-up featuring a cat named Gizmo with 9 lives. Use your past lives as shields and make it to the end!<br />This game served as the 2022 GameDev.tv submission with the theme "Death is only the beginning."<br /><br /><a target=_blank href='https://somedumbfox.itch.io/gizmos-gambit'>https://somedumbfox.itch.io/gizmos-gambit</a></span>
image: assets/images/games/gizmosgambit/gizmos_gambit.png
show_tile: false
link: https://www.youtube.com/embed/46lLV84CdXY
screenshots:
    name: gizmoScreens
    images:
        -
            src: /assets/images/games/gizmosgambit/gizmo_1.png
            alt: Gizmos Gambit Screenshot 1
        -
            src: /assets/images/games/gizmosgambit/gizmo_2.png
            alt: Gizmos Gambit Screenshot 2
        -
            src: /assets/images/games/gizmosgambit/gizmo_3.png
            alt: Gizmos Gambit Screenshot 3
        -
            src: /assets/images/games/gizmosgambit/gizmo_4.png
            alt: Gizmos Gambit Screenshot 4
---
{% assign videos = site.data.gizmosGambit %}
{%include videos.html %}

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
            <h1>Screenshots</h1>
        </header>
		    {% assign gallery = page.screenshots %}
            {% include gallery.html %}
    </div>
</section>

{% assign videos = site.data.gizmosGambitEnd %}
{%include videos.html %}

