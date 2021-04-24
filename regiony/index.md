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
  fotka: /img/teams/ceske-budejovice.jpg
- nazev: Piráti Tábor
  popis: Místní sdružení pro celý okres Tábor
  url: https://tabor.pirati.cz/
  fotka: /img/teams/tabor.jpg
- nazev: Český Krumlov
  popis:
  url: https://www.facebook.com/PiratiKrumlov
  fotka: /img/teams/cesky-krumlov.jpg
- nazev: Jindřichův Hradec
  popis:
  url: https://www.facebook.com/otevrenyhradec
  fotka: /img/teams/jindrichuv-hradec.jpg
- nazev: Písecko
  popis:
  url: http://www.piratipisecko.cz/
  fotka: /img/teams/pisek.jpg
- nazev: Prachatice
  popis:
  url: https://www.facebook.com/Pir%C3%A1ti-Prachaticko-187338495157758
  fotka: /img/teams/prachatice.jpg
- nazev: Strakonicko
  popis:
  url: https://www.facebook.com/PiratiStrakonice
  fotka: /img/teams/strakonice.jpg
- nazev: Soběslav
  popis:
  url: http://pirati.sobeslav.cz/
  fotka: /img/teams/sobeslav.jpg
- nazev: Týn nad Vltavou
  popis:
  url: https://tyn.pirati.cz/
  fotka: /img/teams/tyn-nad-vltavou.jpg
---


<div>
{% for r in page.regiony %}
  <div>
    <a href="{{r.url}}"><h3>{{r.nazev}}</h3></a>
    <img src="https://a.pirati.cz/resize/348x232/jihocesky/{{r.fotka}}" />
  </div>
{% endfor %}
</div>
