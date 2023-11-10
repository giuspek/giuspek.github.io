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
* B.S. in Computer Science, University of Trento, 2015-2018
* M.S. in Computer Science (Software Engineering), University of Trento, 2018-2020
* Period abroad (Erasmus), Aalto University, 2019
* Ph.D in Formal Verirification, University of Trento, 2020-2024 (expected)

Work experience
======
* Research Collaborator @ KU Leuven
  * Joint work with Paolo Morettin (post-doc @ KU Leuven) focused on exploiting Weighted Model Integration for probabilistic formal verification

* Research Assistant @ University of Freiburg
  * Research on model counting and model enumeration
  * Supervisor: Armin Biere
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  