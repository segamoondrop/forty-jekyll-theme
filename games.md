---
layout: page
title: Games
description: 'Featuring games'
image: 'assets/images/games/DJUsachi/DJBunnyTitleScreenCentered.png'
nav-menu: true
show_tile: true
---
<div class="tiles">
  {% for video in site.data.games %}
    <article style="background-image:url({{video.thumbnail}})">
      <span class='image' style='display:none;'>
        <img src="{{video.thumbnail}}">
      </span>
      <header class="major">
        <h3>
          <a href="{{video.link}}">
              {{video.title}}
          </a>
        </h3>
        <p>{{video.description}}</p>
      </header>
        <a href="{{video.link}}" class="link primary">
        </a>
    </article>
  {% endfor %}
</div>