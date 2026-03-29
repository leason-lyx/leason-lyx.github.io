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
* **Name:** Li Yixin
* **Affiliation:** School of Electronics Engineering and Computer Science, Peking University
* **Current Position:** Senior Undergraduate Student
* **Incoming Position:** Ph.D. Student, Peking University, starting in Sep 2026
* **Advisor:** Wei Ye, Associate Researcher and Director of the Knowledge Computing Lab
* **Research Area:** AI for Software Engineering (AI4SE)

Research Interests
======
* AI for Software Engineering (AI4SE)
* Large Language Models for Software Engineering
* Coding Agents

Education
======
* **B.S. in Computer Science**, School of Electronics Engineering and Computer Science, Peking University  
  Sep 2022 - Jul 2026 (expected)
* **Ph.D. in Computer Science**, Peking University  
  Starting in Sep 2026

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