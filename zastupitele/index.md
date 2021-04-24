---
layout: page
img:
title: Krajští zastupitelé
shortdesc:
rbar:
  - kodo
  - calendar
keywords: zastupitelé kraj
description: Krajští zastupitelé
clenove:
- jmeno: Josef Soumar
  foto:
---

## Jak fungujeme?

<div>
{% for person in page.clenove %}
  {% include people/profile-badge.html
    item=person imgSize='big' imgStyle='round'
    class='c-profile-badge--centered' %}
{% endfor %}
</div>
