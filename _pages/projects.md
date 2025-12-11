---
layout: default
title: Frederick Wentzien - Portfolio
permalink: /projects/
---
[Torque Wrench]({{ "/assets/TorqueWrench.pdf" | relative_url}})  


[System Dynamics of a Heart]({{ "/assets/MAE3260Final.pdf" | relative_url}})

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>