---
layout: default
title: "Projects"
permalink: /projects
---
<div class="project-grid"> 
    {% for item in site.data.projects %}
        <div class="project"> 
            <img src="{{ item.image_path | prepend: site.baseurl }}" width="250" height="100"> 
            <h3>{{ item.name }}</h3>
            {{ item.description }}
        </div>
    {% endfor %}
</div>