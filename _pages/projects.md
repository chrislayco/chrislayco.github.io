---
layout: single
title: projects
permalink: /projects/
author_profile: true
---

this is where a more detailed list of all my projects will go

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}

