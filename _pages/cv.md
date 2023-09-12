---
layout: archive
title: "CV [pdf version](https://www.example.com)"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
Ph.D. in Economics, University of Toronto, 2024 (Expected)
     - Committee: Kory Kroft (co-supervisor), David J. Price (co-supervisor), Marl&#232;ne Koffi  
* M.A in Economics, Universit‌&#233; de Montr&#233;al, 2017
* B.A in Economics, Universit‌&#233; de Montr&#233;al, 2015

<div class="custom-list">
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
</div>

/* Your CSS styles */
.custom-list {
  margin-left: 20px; /* Adjust the indentation as needed */
}

.custom-list ul {
  list-style-type: disc; /* Add bullet points */
}

Research
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
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
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
