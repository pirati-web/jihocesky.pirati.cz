---
layout: page
img:
title: Krajský zastupitelský klub
shortdesc:
rbar:
  - kodo
  - calendar
keywords: zastupitelé kraj
description: Krajští zastupitelé
clenove:
- uid: kovarova-veronika
  name: Ing. arch. Veronika Kovářová
  img: people/veronika.kovarova.2020.jpg
  description: předsedkyně klubu
  mail: veronika.kovarova@pirati.cz
  mob: +420603397164
- uid: soumar-josef
  name: Josef Soumar
  img: people/josef-soumar-3.jpg
  mail: josef.soumar@pirati.cz
  mob: 737 838 263
---

## Jak fungujeme?

Pár slov o fungování klubu. Redmine, program a jejich vztah .. plneni atd.

### Členové

<div>
{% for person in page.clenove %}
  {% include people/profile-badge.html
    item=person imgSize='big' imgStyle='round'
    class='c-profile-badge--centered' %}
{% endfor %}
</div>
