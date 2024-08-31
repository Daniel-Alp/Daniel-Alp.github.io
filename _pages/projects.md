---
layout: default
title: "Projects"
permalink: /projects
---
<div class="project-grid"> 
    {% for item in site.data.projects %}
        <div class="project"> 
            <div class="image-card"><img src="{{ item.image_path | prepend: site.baseurl }}"/></div> 
            <div class="project-name">{{ item.name }}</div>
            <div class="project-description">{{ item.description }}</div>
        </div>
    {% endfor %}
</div>