---
permalink: /projects/
title: "Projects"
excerpt: "Projects"
author_profile: true
redirect_from: 
  - /projects/
  
---
{% include base_path %}


{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}
