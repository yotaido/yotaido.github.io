---
layout: default
title: Taidon alkeiskurssi — Taido Core
---

## Harjoittelu ##

Uusia harrastajia otetaan mukaan seuraavan kerran:
{% for item in site.data.training-schedule.course_starts -%}
- **{{ item.weekday }} {{ item.datetime | date: "%d.%m.%Y klo %H.%M" }}**
{% endfor %}

