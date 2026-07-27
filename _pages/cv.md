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
---

* **B.Sc. in Electrical Engineering, University of Chile, 2028** (expected)
* **B.Sc. in Matematical Engineering, University of Chile, 2028** (expected)
* **B.Sc. Engineering Sciences, University of Chile, 2022-2023**

* 2nd Winter School on Artificial Intelligence Applied to Health (2026), Science and Technology Building, San Joaquín Campus, Pontificia Universidad Católica de Chile. Organized by Millenium Institute for Intelligent Healthcare Engineering (iHealth).
* Basic Bioinformatics Workshop and its applications in the genome assembly of non-model species (2023), Faculty of Physical and Mathematical Sciences, University of Chile. Supported by the Chilean Society of Genetics (SOCHIGEN), the Pontifical Catholic University of Chile (PUC), and centers of the ANID Millennium Science Initiative (CRG, LiLi, BASE).

Work experience
======
* **Intern - Coordinador Eléctrico Nac
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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

Interviews, Press Mentions and Social Media Appearences
=====
{% for post in site.media reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
