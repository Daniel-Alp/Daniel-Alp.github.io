---
layout: default
title: "Projects"
permalink: /projects
---
<div class="project-grid"> 
    {% for item in site.data.projects %}
        <a href="{{ item.url }}">
            <div class="project"> 
                <div class="image-card"><img src="{{ item.image | prepend: site.baseurl }}"/></div> 
                <div class="project-name">{{ item.name }}</div>
                <div class="project-description">{{ item.description }}</div>
            </div>
        </a >
    {% endfor %}
</div>