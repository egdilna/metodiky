---
title: Index
layout: home
nav_order: 1
---

Vítejte na webu EG metodiky. Tento web je projektem uskupení [EGdílna](https://www.egdilna.cz) a najdete jej na adrese [metodiky.egdilna.cz](https://metodiky.egdilna.cz)

V sekci Metodiky najdete buď přímo samotné dokumenty, nebo alespoň odkazy na dokumenty a návody dle jednotlivých oblastí.

V sekci Postupy pak najdete většinou námi zpracované konkrétnější návodné postupy jak na co použitelné pro konkrétní práci.

A nezapomeňte také na to, že existuje web [archi.gov.cz](https://archi.gov.cz) což je wiki web národní architektury EG také se spoustou užitečných a hlavně často i závazných informací.


### Co je tady nového

<ul>
{% for novinka in site.data.novinky %}
<li>{{ novinka.datum }}: {{ novinka.text }}</li>
{% endfor %}
</ul>