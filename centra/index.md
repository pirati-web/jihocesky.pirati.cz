---
layout: page
img:
title: Pirátská centra
shortdesc:
rbar:
  - kodo
  - calendar
keywords: centrum regiony
description: Pirátská centra
centra:
- jmeno: ČePiCe
  foto:
  url: cepice/
  adresa:
- jmeno: VoPiCe
  foto:
  url: vopice/
  adresa:
---

## Jak fungujeme?

<div>
{% for c in page.centra %}
  <div>{{c.jmeno}}</div>
{% endfor %}
</div>
