---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---
{% include base_path %}

<div class="grid">
  <div class="wrapper">
    {% for post in site.software %}
      {% include archive-single-proj.html type="grid" %}
    {% endfor %}
  </div>
</div>
