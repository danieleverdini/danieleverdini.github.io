---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
classes: teaching-page
---

{% assign items = site.teaching | sort: 'date' | reverse %}
{% assign lecturers = items | where: "role", "Lecturer" %}
{% assign tas = items | where: "role", "Teaching Assistant" %}

## Lecturer
<ul class="teaching-list">
{% for post in lecturers %}
  <li>
    {% if post.term %}{{ post.term }}{% elsif post.years %}{{ post.years }}{% elsif post.date %}{{ post.date | date: "%Y" }}{% endif %}
    - {{ post.title }}{% if post.venue or post.type %} ({{ post.venue }}{% if post.type %}, {{ post.type | downcase }}{% endif %}){% endif %}
  </li>
{% endfor %}
</ul>

## Teaching Assistant
<ul class="teaching-list">
{% for post in tas %}
  <li>
    {% if post.years %}{{ post.years }}{% elsif post.term %}{{ post.term }}{% elsif post.date %}{{ post.date | date: "%Y" }}{% endif %}
    - {{ post.title }}{% if post.venue or post.type %} ({{ post.venue }}{% if post.type %}, {{ post.type | downcase }}{% endif %}){% endif %}
  </li>
{% endfor %}
</ul>
