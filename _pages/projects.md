---
layout: splash
permalink: /projects/
title: "Projects"
header:
  header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/images/AI-TEAM.png"
---

{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}