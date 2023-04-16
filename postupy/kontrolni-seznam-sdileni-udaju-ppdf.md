---
layout: default
title: Kontrolní seznam postupu k realizaci výměny údajů v propojeném datovém fondu
description: "Tento postup se týká toho, jak postupovat pro technickou realizaci splnění povinnosti poskytování údajů v propojeném datovém fondu a tedy výměny údajů mezi agendami a agendovými systémy. Určuje kroky ohlašovatelům a správcům daných informační systémů."
last_modified_date: 2023-04-16
nav_order: 5
parent: Kontrolní seznamy postupů
grand_parent: Postupy
---


# Kontrolní seznam postupu k realizaci výměny údajů v propojeném datovém fondu

Verze 1.0

Zpracováno jako výstup projektu egdilna.cz a partnerů v rámci EG konkrétních postupů

## Úvod

Toto je kontrolní seznam a postup zejména využitelný pro architekty a odborníky pro ICT v úřadech. Udává podrobnosti a návody, jak postupovat v jednotlivé oblasti.

Tento postup se týká toho, jak postupovat pro technickou realizaci splnění povinnosti poskytování údajů v propojeném datovém fondu a tedy výměny údajů mezi agendami a agendovými systémy. Určuje kroky ohlašovatelům a správcům daných informační systémů.

Postup najdete vždy v rámci [sekce Postupy na webu metodiky.egdilna.cz](https://metodiky.egdilna.cz/postupy/eg-postupy)

Aktuální verze je na adrese

[https://metodiky.egdilna.cz/postupy/kontrolni-seznam-sdileni-udaju-ppdf](https://metodiky.egdilna.cz/postupy/kontrolni-seznam-sdileni-udaju-ppdf)

## Sdílení a výměna údajů mezi agendami

podle zákonných povinností musí docházet ke sdílení údajů a to formou výměny údajů mezi jednotlivými agendami a jednotlivými agendovými informačními systémy. Cílem je vyměňovat si plně automatizovaným způsobem údaje, kterými veřejná správa již disponuje a nezatěžovat jejich dokládáním klienta služeb. Tomu se říká propojený datový fond a vychází to z ohlášených agend a údajů v agendách. Technicky se údaje poskytují a využívají službami čerpanými prostřednictvím EGSB/ISSS.

Další informace lze najít na stránkách národní architektury EG [stránka Agendový model veřejné správy z NAP](https://archi.gov.cz/nap:agendovy_model_verejne_spravy), [stránka Evidence údajů agend do RPP](https://archi.gov.cz/znalostni_baze:evidence_udaju), [stránka Globální architektura propojeného datového fondu](https://archi.gov.cz/znalostni_baze:ga_ppdf), [stránka Integrace informačních systémů veřejné správy z NAP](https://archi.gov.cz/nap:integrace_informacnich_systemu), [stránka Kontexty EGSB/ISSS](https://archi.gov.cz/nap:kontext), [stránka Propojený datový fond veřejné správy z NAP](https://archi.gov.cz/nap:propojeny_datovy_fond), [stránka Sdílení údajů veřejné správy z NAP](https://archi.gov.cz/nap:sdileni_udaju), 

## Rámcový postup pro technickou realizaci výměny

1. Ohlašovatel publikující agendy zpracuje datovou architekturu: Pro každou agendu musí ohlašovatel zpracovat především konceptuální datový model vycházející z konceptuálního modelu agendy a označit jej jako Konceptuální datový model agendy. K tomu využije příslušnou metodiku pro evidenci údajů a tvorbu konceptuálních modelů. KDM agendy publikuje a předává DIA. Součástí konceptuálního modelu bude také seznam pojmů ve formě sémantického slovníku a seznam subjektů a objektů, kterých se agenda týká a o nichž se vedou údaje v dané agendě a to včetně vlastností, které se o nich vedou. To je pak základ datové architektury datového kmenu agendy a z něj se odvozuje následné ohlášení údajů v agendě v Registru práv a povinností. 
1. Ohlašovatel publikující agendy ohlásí údaje do RPP: Údaje jsou povinnou součástí ohlášení agendy a stejně jako u dalších informací o agendě je povinností ohlašovatele, aby ohlásil veškeré a pravdivé a aktuální skutečnosti týkající se agendy. Ohlašovatel tedy správně ohlásí veškeré údaje vedené v agendě. Vymezí přitom subjekty a objekty práva a k nim evidované jednotlivé údaje jako jejich vlastnosti v souladu se zpracovaným konceptuálním datovým modelem agendy.
1. Uzavření kontraktu o přístupu k údajům: Ohlašovatel agendy dle svého konceptuálního modelu (dle konkrétního zmocnění z agendového zákona a nebo dle obecných zmocnění a povinností ze Zákona o základních registrech a Zákona o právu na digitální služby) vyhledá údaje ohlášené jinými správci a eviduje žádost o přístup k těmto údajům. Stejně tak zpracovává žádosti o přístup k údajům své agendy od správců jiných agned. Postupem popsaným v zákoně je dosaženo vytvoření a zaevidování kontraktu o přístupu a využívání údajů agend. Technická dostupnost údajů není nutnou podmínkou pro vytvoření kontraktu. Nedojde-li k dobrovolné dohodě, obrátí se ohlašovatel čtenářské agendy na DIA a na vládu, která zajistí rozhodnutím nápravu a uloží ohlašovateli publikující agendy poskytovat součinnost a plnit související povinnosti. 
1. Příprava  na technické sdílení: Ohlašovatel agendy doplní technickou strukturu údajů agendy.
    1. Ohlašovatel publikující agendy zpracuje a ohlásí kontexty a oprávnění do RPP: Podle ohlášených údajů v agendě v Registru práv a povinností ohlásí ohlašovatel jednotlivé publikační kontexty. Ty připraví na základě údajů v agendě jež poskytuje a technických údajů o údajích.. Kontexty si podrobně a plánované způsoby jejich použití dohodne s DIA konkrétně s OHA. Publikační kontext může obsahovat údaje z jednoho či více datových objektů evidovaných pro agendu v RPP v bodě 2.1
    1. Ohlašovatel publikující agendy a správce AIS publikujícího zpracuje XSD schémata pro ISSS pro jednotlivé kontexty: Pro jednotlivé kontexty musí být zpracováno kontrolní a přenosové schéma XML pro výměnu údajů s využitím služeb ISSS. ISSS přenese a dovolí komuniakci pouze podle schválených schémat XSD. Čtenáři tedy musejí dodržovat schéma publikované poskytovatelem údajů v katalogu ISSS. O tento úkol se dělí ohlašovatel údajů (musí být v souladu s údaji ohlášenými v agendě podle jejich identifikátoru údajů) a správce daného agendového informačního systému, což může být jiné OVM (systém pak bude poskytovat údaje ve struktuře dle tohoto schématu). 
    1. Správce AIS publikujícího vybuduje služby AIS napojené na ISSS pro publikaci, čtení, notifikace, reklamace, probe apod. dle dohodnutých případů použití: Klíčové jsou technické úpravy publikujícího agendového informačního systému tak, aby dokázal zodpovídat dotazy ze služeb ISSS. Doporučeným postupem je impleemntace publikační brány, která zajišťuje na straně AIS příjem a zpracování služeb ISSS. Správce AIS musí vytvořit minimálně služby v rozsahu typizovaných služeb ve skupině Výměna a sdílení údajů a PPDF. 
1. Realizace technického sdílení na ISSS: Služby publikujícího systému jsou v souladu s požadavky EGSB/ISSS, to zajistí správce publikujícího AIS. Údaje poskytované službami jsou řádně ohlášené v agendě a jejich technické podrobnosti a struktura odpovídají kontextům a XSD schématům.
    1. Správce publikujícího AIS provede ověření a zkušební provoz služeb v testovacím rozhraní ISSS: Před povolením produkčního provozu služeb publikujícího AIS provede správce tohoto systému oověření v testovacím ISSS. Zkušební provoz řídí a dohlíží na něj DIA. 
    1. Otestování s uživateli: Doporučeným postupem je zapojení typizovaného čtenáře do testovacího prostředí ISSS před spuštěním propojení v produkčním prostředí a otestování napojení a správnost výměny údajů. Testování řídí a dohlíží na něj DIA a teprve na základě takového testu lze přistoupit k poskytování služeb publikujícího AIS v produkčním prostředí. 
    1. DIA umožní publikovat služby publikujícího AIS v produkčním ISSS: Až správce publikujícího AIS splní požadavky a nároky z provozní dokumentace ISSS a úspěšné projde zkušebním provozem v testovgací instanci ISSS, DIA jako správce ISSS umožní spuštění služeb AISu přes produkční ISSS a dle matice oprávnění z Registru práv a povinností a rozsahu agend a OVM (komtrakty uzavřené v bodě 2.2)  umožní jejich volání. 

