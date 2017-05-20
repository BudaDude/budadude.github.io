---
layout: page
title: Projects
---

<div class="projects-view">

  {% for project in site.projects %}
        <a href="{{ site.baseurl }}{{ project.url }}">
    <div class="project-item">

      <img src="{{project.banner_image}}" alt="" />

      
          <div class="overlay">
           <h2>{{project.title}}</h2>
        </div>

</div>
      </a>
  {% endfor %}

</div>
