---
layout: archive
title: "Proyects"
permalink: /proyects/
author_profile: true
---

{% include base_path %}

{% for post in site.proyects reversed %}
  {% include archive-single.html %}
{% endfor %}
