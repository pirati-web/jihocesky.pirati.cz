---
layout: contacts
# contentSize: big
contentSize: even
residences:
 - name: Pirátská strana | JIHOČESKÝ KRAJ
   url:
   address: |
     ČEPICE - Českobudějovické Pirátské centrum
     Hradební 13
     370 01 České Budějovice
     mobil: +420 727 853 151
     
     <strong>Kancelář je pro Vás otevřena:</strong>
     Každé pondělí 9:00 - 17:00 po telefonické domluvě s asistentkou.
   spravce: zuzana.kudlackova
   mapLink: "https://goo.gl/maps/BumUenmcVBiGZYN48"

contactPersons:
 - id: klara.bidarova
   position: Krajská koordinátorka<br><span style="font-size:60%">(kontakt pro dobrovolníky a zájemce o členství)</span>   
 - id: lubos.kudlacek
   position: Mediální odbor<br><span style="font-size:60%">(kontakt pro novináře)</span>
---


Zajímá vás co piráti dělají? [Naloďte se](https://nalodeni.pirati.cz/) a buďte v obraze, nebo kontaktujte našeho koordinátora (viz kontakt pro dobrovolníky).

Finanční dary můžete posílat na [zde](https://dary.pirati.cz).
Pokud chcete darovat přimo našemu kraji, poraďte se prosím s koordinátorem.

<div class="o-section-header o-section-header--indented">
  <h1 class="t-h2-alt">Poslanci</h1>
</div>

{% assign person = site.people | where_exp: "item","item.uid contains 'lukas.kolarik'" | first  %}
{% include people/profile-badge.html item=person imgSize='big' imgStyle='round' class='c-profile-badge--centered' %}

