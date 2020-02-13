---
layout: archive
title: "Projects"
collection: projects
permalink: /projects/
author_profile: false
---

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
