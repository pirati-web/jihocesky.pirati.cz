---
layout: page
title: Regionální týmy
shortdesc:
rbar:
  - kodo
  - calendar
keywords: tým regiony
description: Regionální týmy
regiony:
- nazev: Českobudějovicko
  popis: Místní sdružení pro okresy České Budějovice a Týn nad Vltavou
  url: https://cb.pirati.cz/
  fotka: /assets/img/teams/ceske-budejovice.jpg
- nazev: Piráti Tábor
  popis: Místní sdružení pro celý okres Tábor
  url: https://tabor.pirati.cz/
  fotka: /assets/img/teams/tabor.jpg
- nazev: Český Krumlov
  popis:
  url: https://www.facebook.com/PiratiKrumlov
  fotka: /assets/img/teams/cesky-krumlov.jpg
- nazev: Jindřichův Hradec
  popis:
  url: https://www.facebook.com/otevrenyhradec
  fotka: /assets/img/teams/jindrichuv-hradec.jpg
- nazev: Písecko
  popis:
  url: http://www.piratipisecko.cz/
  fotka: /assets/img/teams/pisek.jpg
- nazev: Prachatice
  popis:
  url: https://www.facebook.com/Pir%C3%A1ti-Prachaticko-187338495157758
  fotka: /assets/img/teams/prachatice.jpg
- nazev: Strakonicko
  popis:
  url: https://www.facebook.com/PiratiStrakonice
  fotka: /assets/img/teams/strakonice.jpg
- nazev: Soběslav
  popis:
  url: http://pirati.sobeslav.cz/
  fotka: /assets/img/teams/sobeslav.jpg
- nazev: Týn nad Vltavou
  popis:
  url: https://tyn.pirati.cz/
  fotka: /assets/img/teams/tyn-nad-vltavou.jpg
---


<div>
{% for r in page.regiony %}
  <div>
    <h3>{{r.nazev}}</h3>
    <img src="{{r.fotka}}" />
  </div>
{% endfor %}
</div>
