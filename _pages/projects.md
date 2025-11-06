---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

This page will feature your projects.

{% assign collection = site.portfolio %}
{% for item in collection %}
  {% include archive-single.html type="grid" %}
{% endfor %}