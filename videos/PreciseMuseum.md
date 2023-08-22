---
layout: landing
title: Precise Museum Videos
description: Videos I created for Precise Museum & collaborated in
image: assets/images/carby.jpg
show_tile: false
link: https://youtu.be/9MP37nz8HZA
---

<section id="two" class="spotlights">
	{% for vid in site.data.preciseMuseum %}
	<section>
		{% if vid.image %}
		<span class="image">
			<img src="{{vid.image}}" alt="" data-position="center center" />
		</span>
		{% endif %}
		<div class="content">
			<div class="inner">
				{% if vid.title %}
				<header class="major">
					<h3>{{vid.title}}</h3>
				</header>
				{% endif %}
				{% if vid.youtubeEmbed %}
        <iframe class="youtubeEmbed" src="{{vid.youtubeEmbed}}" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
				{% endif %}
				{% if vid.caption %}
				<p>{{vid.caption}}</p>
				{% endif %}
				{% if vid.buttonText && vid.buttonLink %}
				<ul class="actions">
					<li><a href="{{vid.buttonLink}}" target="{% if vid.target %}{{vid.target}}{% else %}_blank{% endif %}" class="button">{{vid.buttonText}}</a></li>
				</ul>
				{% endif %}
			</div>
		</div>
	</section>
	{% endfor %}
</section>
