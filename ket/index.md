---
layout: page
img:
title: Krajské expertní týmy
shortdesc:
rbar:
  - kodo
  - calendar
keywords: centrum regiony
description: Pirátská centra
kety:
- jmeno: Životní prostředí
  foto:
  url: cepice/
- jmeno: Doprava
  foto:
  url: vopice/
---

## Jak fungujeme?

<div>
{% for i in page.kety %}
  <div>{{i.jmeno}}</div>
{% endfor %}
</div>
