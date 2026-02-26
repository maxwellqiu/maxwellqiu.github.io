---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

A selection of projects spanning **Data Science** and **QA Automation**. Each project reflects a real problem I've worked on — building things that are reliable, measurable, and maintainable.

<div class="projects-grid">

{% assign sorted_projects = site.projects | sort: "order" %}
{% for project in sorted_projects %}
<div class="project-card">
  <div class="project-card__header">
    <div class="project-card__title">{{ project.title }}</div>
    {% if project.category == "Data Science" %}
      <span class="project-card__tag tag--ds">Data Science</span>
    {% elsif project.category == "QA Automation" %}
      <span class="project-card__tag tag--qa">QA</span>
    {% endif %}
  </div>

  <div class="project-card__description">{{ project.description }}</div>

  <div class="project-card__stack">
    {% for tech in project.stack %}
      <span class="stack-pill">{{ tech }}</span>
    {% endfor %}
  </div>

  <div class="project-card__links">
    {% if project.github %}
      <a href="{{ project.github }}" target="_blank" rel="noopener">
        <i class="fab fa-github"></i> GitHub
      </a>
    {% endif %}
    {% if project.demo %}
      <a href="{{ project.demo }}" target="_blank" rel="noopener">
        <i class="fas fa-external-link-alt"></i> Live Demo
      </a>
    {% endif %}
    <a href="{{ project.url }}">
      <i class="fas fa-arrow-right"></i> Read More
    </a>
  </div>
</div>
{% endfor %}

</div>
