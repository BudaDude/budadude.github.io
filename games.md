---
layout: page
title: Games
---

<div class="projects-view">

  {% for game in site.games %}
        <a href="{{ site.baseurl }}{{ game.url }}">
    <div class="project-item">

      <img src="{{game.banner_image}}" alt="" />

      
          <div class="overlay">
           <h2>{{game.title}}</h2>
        </div>

</div>
      </a>
  {% endfor %}

</div>
