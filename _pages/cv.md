---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Profile
======
* Name: Li Yixin
* Affiliation: Peking University
* Position: Senior Undergraduate Student
* Next Position: Incoming Ph.D. Student at Peking University
* Research Area: AI4SE

Research Interests
======
* AI for Software Engineering
* Large Language Models for Software Engineering
* Coding Agent

Education
======
* Senior Undergraduate Student, Peking University
* Incoming Ph.D. Student, Peking University

Publications
======
{% assign visible_publications = site.publications | where_exp: "item", "item.published != false" %}
{% if visible_publications.size > 0 %}
  <ul>{% for post in visible_publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% else %}
No publications listed yet.
{% endif %}

Notes
======
More detailed CV entries, publications, and project information will be added here over time.
