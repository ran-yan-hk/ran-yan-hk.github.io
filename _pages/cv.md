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
* Ph.D in Computer Science, The Hong Kong University of Science and Technology, 2027 (expected)
* B.S. in Biomedical Engineering & Economics(double major), Peking University, 2023

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work experience
======
* Intern at ZK Space (2023.05-2023.09) 
  * Research and design event driven trading strategy.

* Intern at ByteDance (2024.09-2025.07)
  * Research on adapting SOTA sparse attention NSA and designing distributed VAE for video generation.

* Intern at Ant Group (2025.07-Now)
  * Research on asynchronous RL training over heterogeneous GPUs and tree-attention-based RL training.
  
Skills
======
* Programming: Python, Shell, C++, Vim, Docker, etc.
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Hobbies
======
* In my spare time, I enjoy skiing, and I'm a snowboarder. Although I'm currently a beginner, I improve very fast.