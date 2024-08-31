---
layout: default
title: "Projects"
permalink: /projects
---
<div class="project-grid"> 
    {% for item in site.data.projects %}
        <div class="project"> 
            <h3>{{ item.name }}</h3>
            {{ item.description }}
        </div>
    {% endfor %}
</div>