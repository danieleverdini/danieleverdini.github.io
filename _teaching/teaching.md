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

### Lecturer
- Spring 2026 - **Adv. International Trade** (UCLouvain, graduate)
- Spring 2025 - **International Economics** (UAntwerp, undergraduate)

### Teaching Assistant
- 2020-2022 - **Adv. Macroeconomics** (UCLouvain, graduate)
- 2021-2023 - **Trade Policy and International Cooperation** (UCLouvain, graduate)
