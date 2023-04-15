---
layout: default
title: Kontrolní seznam tvorby a údržby Katalogu služeb úřadulegislativy
description: "Tento postup se týká toho, proč a jak si má úřad vytvářet vlastní katalog služeb s vazbou na Katalog služeb veřejné správy a co s ním má dělat
"
last_modified_date: 2023-04-15
nav_order: 11
parent: Kontrolní seznamy postupů
grand_parent: Postupy
---


# Kontrolní seznam tvorby a údržby Katalogu služeb úřadu

Verze 0.3

Zpracováno jako výstup projektu egdilna.cz a partnerů v rámci EG konkrétních postupů

## Úvod

Toto je kontrolní seznam a postup zejména využitelný pro architekty a odborníky pro ICT v úřadech. Udává podrobnosti a návody, jak postupovat v jednotlivé oblasti.

Tento postup se týká toho, proč a jak si má úřad vytvářet vlastní katalog služeb s vazbou na Katalog služeb veřejné správy a co s ním má dělat


Postup najdete vždy v rámci [sekce Postupy na webu metodiky.egdilna.cz](https://metodiky.egdilna.cz/postupy/eg-postupy)

Aktuální verze je na adrese

[https://metodiky.egdilna.cz/postupy/kontrolni-seznam-pozadavky-ISVS-nove](https://metodiky.egdilna.cz/postupy/kontrolni-seznam-pozadavky-ISVS-nove)

## 🖋 Katalog služeb úřadu a Katalog služeb veřejné správy

Orgán veřejné správy si musí vytvořit vlastní vnitřní katalog služeb, kterému říkáme Katalog služeb OVS nebo Katalog služeb úřadu. Jde o datovou evidenci, v níž se vedou údaje o

- službách veřejné správy, jež orgán veřejné moci poskytuje
- službách veřejné správy, jež jsou poskytovány prostřednictvím orgánu veřejné správy
- Službách určených uživatelům, jež nejsou službami veřejné správy

Všechny tyto služby je vhodne (a někdy i nutné) si vést ve svém katalogu a to zejména pro tyto potřeby:

- U služeb, jež jsou poskytovány úřadem kde je zároveň ohlašovatelem jde o jeho prvotní evidenci, ze které ohlašuje služby a úkony v rámci agendy v Katalogu služeb (pokud si o službě vede sám další informace jež nejsou v Katalogu služeb)
- U všech služeb veřejné správy si sice základní údaje o službách a úkonech získá z Katalogu služeb, ale sám si u služeb musí vést údaje potřebné pro jeho fungování, jako je zodpovědný útvar, správce služby, správce informačního systému jež službu poskytuje či využívá, apod.
- U služeb jež poskytuje klientům a uživatelům, i když nejsou službami veřejné správy, si musí vést údaje o službé samotné, o správci služby a o zodpovědných osobách, o nástrojích jež k dané službě potřebuje a také podklady pro řízení a hodnocení kvality služby v rámci řízení kvality úřadu.

## 🖋 Jak základně postupovat při tvorbě Katalogu služeb úřadu a jeho prvotním naplnění


1. Úřad si projde Katalog služeb veřejné správy (třeba přes [nástroj Veřejná část Katalogu služeb veřejné správy](https://portal.gov.cz/sluzby-verejne-spravy/)) a zjistí si, jak katalog vypadá, co obsahuje, může využít také [nástroj Interní evidenční část Katalogu služeb VS](https://egov.shinyapps.io/katalog_sluzeb/)
2. Rozhodne o formě a nástroji, ve kterém povede vlastní Katalog služeb úřadů. Může jít o interaktivní seznam ve Sharepointu, model v ArchiMate a nebo třeba komplexní katalog v Enterprise Architectu, záleží na složitosti úřadu a na požadavcích na správnou evidenci služeb.
3. Vytvoří si evidenci Katalog služeb úřadu s využitím předpřipraveného vzorového datového modelu katalogu (vytváří se)
4. Pro služby veřejné správy zapsané v Katalogu služeb si převezme do svého katalogu služby, které se ho týkají a doplní si vlastní specifické podrobnosti. 
    - Pro přebírání služeb a údajů o jejich podrobných popisech může využít jeden ze způsobů jak je uvádí [stránka Katalog služeb veřejné správy z NAP](https://archi.gov.cz/nap:katalog_sluzeb) a nebo třeba data jež obsahuje [Datová sada Detailní popisy služeb veřejné správy](Detailní popisy služeb veřejné správy	https://data.gov.cz/datov%C3%A1-sada?iri=https%3A%2F%2Fdata.gov.cz%2Fzdroj%2Fdatov%C3%A9-sady%2F00007064%2F5c50c1bc5be82f78cb8157f5618933e2) 
5. Pro služby veřejné správy, které nejsou v katalogu služeb je identifikuje a zapíše si jejich podrobnosti, přitom postupuje podle [dokumentu Metodika pro evidenci služeb veřejné správy a stanovení postupu jejich digitalizace](https://archi.gov.cz/znalostni_baze:metodika_sluzeb_vs). Pokud je ohlašovatelem či OVM vykonávajícím působnost poskytnutím služby, zajistí zápis (či opravu) služeb v Katalogu služeb veřejné správy.