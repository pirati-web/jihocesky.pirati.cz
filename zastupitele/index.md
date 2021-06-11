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
  img: people/volby2021/verkov.jpg
  description: předsedkyně klubu
  mail: veronika.kovarova@pirati.cz
  mob: +420603397164
- uid: soumar-josef
  name: Josef Soumar
  img: people/volby2021/pepasou.jpg
  mail: josef.soumar@pirati.cz
  mob: 737 838 263
- uid: martin.kakona
  name: Martin Kákona
  img: people/volby2021/martinka.jpg
  mail: martin.kakona@pirati.cz
- uid: lukas.mares
  name: Lukáš Mareš
  img: people/volby2021/lukasm.jpg
  mail: lukas.mares@pirati.cz
- uid: lucie.korytarova
  name: Lucie Korytářová
  img: people/volby2021/luckak.jpg
  mail: lucie.korytarova@pirati.cz
- uid: jan.hosek
  name: Jan Hošek
  img: people/volby2021/honzaho.jpg
  mail: jan.hosek@pirati.cz
- uid: jiri.roubicek
  name: Jan Hošek
  img: people/volby2021/jirkar.jpg
  mail: jiri.roubicek@pirati.cz
---

## Kdo jsme

Zastupitelský klub je tvořen úspěšnými kandidáty krajských voleb v roce 2020.
Hájí [politický program](/program/), který komunikovali v kampani.
Přestože jsou v opoziční roli, již nyní mají za sebou [cenné úspěchy](/tags/#zastupitelstvo).

### Členové

<div>
{% for person in page.clenove %}
  {% include people/profile-badge.html
    item=person imgSize='big' imgStyle='round'
    class='c-profile-badge--centered' %}
{% endfor %}
</div>
