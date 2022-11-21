---
layout: page
permalink: /teaching/
title: Teaching
description: A record of my teaching activities.
nav: true
nav_order: 6
---

<div class="projects">
    {%- assign sorted_projects = site.taughts | sort: "importance" %}
    <div class="container">
        <div class="row">
            {%- for taught in sorted_projects -%}
              {% include taught_horizontal.html %}
            {%- endfor %}
        </div>
    </div>
</div>
