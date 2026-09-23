---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Student at Worcester Polytechnic Institute (WPI)

Work experience
======
* Autonomous vehicle researcher at WPI
  
Skills
======
* Python
* PyTorch
* Autonomous vehicle perception and control
* Procedural generation
* Neovim, zsh, and terminal tooling

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Maintainer of several open source projects
