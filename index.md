---
title: Index
layout: home
nav_order: 1
---

Vítejte na webu EG metodiky. Tento web je projektem uskupení [EGdílna](https://www.egdilna.cz) a najdete jej na adrese [metodiky.egdilna.cz](https://metodiky.egdilna.cz)


### Co je tady nového

<ul>
{% for novinka in site.data.novinky %}
<li>{{ novinka.datum }}: {{ novinka.text }}</li>
{% endfor %}
</ul>