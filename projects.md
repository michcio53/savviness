---
title: Projects
permalink: /projects/
layout: page
comments: false
---

One of the reasons for starting this blog was to implement my ideas for projects. I would like to report on the process of adding functionality in new projects and what I learned during development. 

Below you will find my projects and what I am currently working on

<hr>



{%- for project in site.projects -%}

<article class="project-item">
    <h2 class="project-item-date">
        <a href="{{ project.url }}">{{ project.title | escape }}</a>
    </h2>
  <h4 class="project-item-title">
    <a href="{{ project.url }}">{{ project.description | escape }}</a>
  </h4>
</article>
{%- endfor -%}
