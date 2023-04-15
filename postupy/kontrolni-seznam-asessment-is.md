---
layout: default
title: Kontrolní seznam asessmentu informačních systémů
description: "Tento postup se týká toho, jak postupovat při zhodnocení stavu a souladu svých informačních systémů s požadavky na ně kladenými (asessment informačních systémů)"
last_updated: 2022-03-21
nav_order: 3
parent: Kontrolní seznamy postupů
grand_parent: Postupy
---

# Kontrolní seznam asessmentu informačních systémů

Verze 1.0

Zpracováno jako výstup projektu egdilna.cz a partnerů v rámci EG konkrétních postupů

## Úvod

Toto je kontrolní seznam a postup zejména využitelný pro architekty a odborníky pro ICT v úřadech. Udává podrobnosti a návody, jak postupovat v jednotlivé oblasti.

Tento postup se týká toho, jak postupovat při zhodnocení stavu a souladu svých informačních systémů s požadavky na ně kladenými (asessment informačních systémů)

Postup najdete vždy v rámci repozitáře [GitHub - egdilna/eg-postupy](https://github.com/egdilna/eg-postupy)

Aktuální verze

- [https://github.com/egdilna/eg-postupy/blob/main/kontrolni-seznam-asessment-is.md](https://github.com/egdilna/eg-postupy/blob/main/kontrolni-seznam-asessment-is.md)





 ## Proč asessment IS zpracovávat?

Úřad by si měl zpracovat přehled svých informačních systémů a jejich souladu se všemi požadavky eGovernmentu a připravit si roadmapu, jak svoje systémy upravit tak, aby v souladu byly.

## Jak postupovat


Jednotlivé kroky jsou následující:

1. Zpracování Assessmentu informačních systémů : Úřad zpracuje Assessment informačních systémů a jejich souladu s EG a jeho výsledky využije pro zhodnocení souladu a pro soupis potřebných kroků pro uvedení do souladu.
1. Zakreslení svých informačních systémů do architektury : Úřad si na aplikační vrstvě architektury zakreslí všechny informační systémy, které sám spravuje. Tyto údaje pak slouží jako zdroj pro ohlášení do RPP.
1. Zakreslení cizích užívaných informačních systémů do architektury : Úřad si na aplikační vrstvě architektury zakreslí informační systémy, u kterých není správcem, ale užívá je. Využije k tomu údaje z Rejstříku informačních systémů v RPP.
1. Zakreslení aplikační dekompozice do architektury : Úřad si na aplikační vrstvě architektury zakreslí dekompozici jím spravovaných informačních systémů, a to minimálně v rozsahu, který ohlašuje k informačnímu systému v RPP. Tyto údaje pak slouží jako zdroj pro ohlášení do RPP.
1. Sebehodnocení souladu informačního systému s EG požadavky : Úřad u každého informačního systému  provede zhodnocení naplňování vyžadovaných EG požadavků.
1. Soupis služeb poskytovaných informačním systémem : Úřad pro každý IS vytvoří seznam služeb, které informační systém poskytuje.
1. Definovat připravenost nových povinných sdílených služeb informačního systému : Úřad si pro každý jím spravovaný informační systém veřejné správy či určený informační systém zhodnotí kroky, které je třeba udělat, aby tento informační systém poskytoval povinně definované služby prostřednictvím EGSB.
1. Zpracování datové architektury informačních systémů : Úřad si pro každý jím spravovaný informační systém musí zpracovat seznam informací a údajů, které v něm vede, ve kterém je využívá či které z něj poskytuje. Zpracovává to s ohledem na potřebu ohlášení údajů v agendách a s ohledem na pravidla strukturování dat informačních systémů veřejné správy. Datová architektura každého informačního systému je součástí datové architektury úřadu.
1. Určení údajů v informačních systémech podle jejich typu : Úřad v datové architektuře určí údaje podle jejich typu. Rozdělí si údaje na: referenční údaje, agendové údaje, poskytované agendové údaje, využívané agendové údaje, provozní údaje a údaje logování a auditu. Podle těchto typů pak postupuje při vytváření a úpravě služeb svých informačních systémů.
1. Zpracování cílové architektury informačních systémů : Úřad podle sebehodnocení souladu svých informačních systémů s EG požadavky zpracuje cílovou architekturu pro každý jím spravovaných informačních systémů. Tato cílová architektura již bude zahrnovat požadovaný to-be stav systému, který splňuje všechny požadavky a obsahuje všechny služby včetně povinných sdílených služeb. Při zpracování cílové architektury využije také výsledky dekompozice informačních systémů, a to zejména tam, kde existují společné komponenty využívané více informačními systémy.
1. Soupis změn pro splnění cílové architektury : Úřad si pro každý jím spravovaných informačních systémů zpracuje potřebné změny, aby informační systém splňoval veškeré požadavky. K tomu využije cílovou architekturu informačního systému.
1. Zanesení potřeb změn informačních systémů do svojí informační koncepce : Úřad při zpracování nové informační koncepce využije příležitosti a zapracuje do ní také cílové architektury informačních systémů a potřebné změny informačních systémů. To bude součástí zejména částí k rozvoji informačních systémů, které spravuje.