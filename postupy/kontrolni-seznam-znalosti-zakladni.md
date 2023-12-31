---
layout: default
title: Návodné postupy pro evidenci základních znalostí
description: "Tento postup se týká toho, jak si může úřad zpracovat a vést své základní znalosti pro dobré řízení architektonických znalostí v rámci modelu i mimo něj a jaké takové znalosti bude potřebovat."
last_modified_date: 2023-12-28
nav_order: 11
parent: Kontrolní seznamy postupů
grand_parent: Postupy
---


# Kontrolní seznam postupy zpracování a vedení základních znalostí potřebných pro byznysovou architekturu úřadu

Verze 1.0.2

Zpracováno jako výstup projektu egdilna.cz a partnerů v rámci EG konkrétních postupů

## Úvod

Toto je kontrolní seznam a postup zejména využitelný pro architekty a odborníky pro ICT v úřadech. Udává podrobnosti a návody, jak postupovat v jednotlivé oblasti.

Tento postup se týká toho, jak si může úřad zpracovat a vést své základní znalosti pro dobré řízení architektonických znalostí v rámci modelu i mimo něj a jaké takové znalosti bude potřebovat


Postup najdete vždy v rámci [sekce Postupy na webu metodiky.egdilna.cz](https://metodiky.egdilna.cz/postupy/eg-postupy)

Aktuální verze je na adrese

[https://metodiky.egdilna.cz/postupy/kontrolni-seznam-znalosti-zakladni](https://metodiky.egdilna.cz/postupy/kontrolni-seznam-znalosti-zakladni)


## Udržování základních znalostí

Úřad musí disponovat nějakými základními znalostmi o své struktuře a svém fungování a o využívání informačních technologií. Bez toho by se úřad špatně řídil, dělal by se špatně jeho rozvoj a také by nešlo splnit strategické dlouhodobé řízení informačních technologií a informačních systémů.

Bavíme-li se  o informačních technologiích, nesmíme zapomenout na to, že tyto technologie musí sloužit nějakému účelu. Tento účel je součástí byznysové architektury, nikoli v aplikační architektury. Zatímco u struktury aplikací je celkem jasné, o co jde a jakým způsobem by se to mohlo či mělo řešit, stran základních znalostí byznysové  architektury zde panuje poměrně silná nevědomost, neboť jsme to na národní úrovni nedostatečně vysvětlovali.

Níže tedy najdete několik ryze praktických postupů a návodů, jak si efektivně a zároveň dostatečně vést základní znalosti o tom, co úřad má dělat a jakým způsobem řešit to nejzásadnější, co potřebuje znát právě z byznysové  architektury.

## Návodné postupy

####   Správné zpracování a vedení organizační struktury úřadu.
1.  Do architektonického modelu zaneseme organizační strukturu.
	*  Každý organizační útvar zavedeme do architektury. Organizační útvar zaneseme do architektury jako prvek typu BusinessActor se stereotypem Útvar atributu Určuje zapíšeme:
	*  Podřízenost útvarů v hierarchii zaneseme do architektury jako vazbu typu CompositionRelationship z nadřízeného do podřízeného útvaru. Výsledkem je tak diagtram s přehlednou organizační strukturou útvarů celého úřadu.
2. ❗Tento diagram a seznam útvarů využíváme v úřadu jako jediný autoritativní zdroj pravdy o organizační struktuře. Diagram přeberem do organizačního řádu i se seznamem útvarů a využijeme ho pro detailnější zpracování byznysové architektury úřadu.
3. Při jakékoliv změně struktury také nejprve aktualizujeme tento diagram.
4. ❗Diagram využíváme všude tam, kde je nutnost zobrazení struktury úřadu. Tedy kupříkladu na internetových stránkách, v příslušné části informační koncepce OVS, v organizačním řádu a mimo jiné jej umístíme tak, aby k němu měl přístup každý zaměstnanec úřadu a také ho zveřejníme jako organizační strukturu dle zákona 106/1999.
####   Zpracování přehledu zodpovědností za agendy a oblasti v úřadu.
1.  Prostřednictvím sestavy agend a činností v RPP si pro naše OVM provedeme export námi vykonávaných agend.
2. Připravíme si přehled věcně zodpovědných, tedy zodpovědností za agendy. Vždy pro jednu agendu uvedeme jeden útvar z organizačního řádu.
	*  V případě, že zpracováváme byznysovou architekturu úřadu, rovnou vytvoříme diagram zodpovědností. Na jedné straně diagramu máme organizační strukturu útvarů a na druhé seznam agend z RPP. Agendu veřejné správy zaneseme do architektury jako prvek typu BusinessFunction se stereotypem Agenda a identifikátorem A1234. Jako název prvku použijeme šablonu A123 název agendy v RPP. Do atributu Určuje zapíšeme: ohlášení v RPP Do architektury se zakreslí jako vazba typu AssignmentRelationship s názvem vykonává agendu,kde zdrojem vazby je Organizační útvar (BusinessActor se stereotypem Útvar) a cílem je Agenda veřejné správy (BusinessFunction se stereotypem Agenda), vazba samotná má stereotyp Agendový model.
	*  V ostatních případech si vedeme kupříkladu jako tabulku, kde jsou minimálně sloupce Agenda a Zodpovědný útvar. Pokud nevedeme v rámci architektury v ArchiMate modelu, dáváme si velký pozor na pojmenování útvarů přesně. Každou zodpovědnost dáváme na samostatný řádek, takže má-li jeden útvar více zodpovědností, budeme to v tabulce mít ve více řádcích.
3. Zodpovědnosti si v roli Věcný gestor (nikoliv věcný správce) promítneme do organizačního řádu. Pokud vedeme v architektuře, uděláme exporetem vazeb do textových konstatací a doplníme o diagram z architektury.
4. ❗Diagram se zodpovědnostmi a jejich přehled použijeme jako základní součást byznysové architektury a promítneme i do příslušné kapitoly svojí informační koncepce OVS.
5. Pro přípravu změny zodpovědností použijeme tento přehled, po jakékoliv změně organizačního schématu či zodpovědností poctivě aktualizujeme.
6. Tento přehled umístíme tak, aby k němu měl, byť třeba jen ve formě diagramu, přístup každý zaměstnanec úřadu.
####   Zpracování evidence obsazení klíčových rolí v úřadu.
1.  Vytvoříme si tabulku obsazení klíčových rolí, je jedno v jaké technologii si tabulková data povedeme, ale musí být jasné, kdo a kdy provedl změny a hlavně kdo je přiřazen k jaké roli.
2. V tabulce si vedeme řádky dle jednotlivých rolí, které získáme z příslušného architektonického katalogu vnitřních rolí. Kromě názvu role si vedeme sloupec Osoba a sloupec Poznámky a sloupec Datum od.
3. Ve sloupci Osoba vedeme nejlépe odkaz na konkrétního zaměstnance či více. V případě SharePointu třeba rovnou odkazem na osobu uživatele, v případě Excelu jednoznačné jméno zaměstnance. Můžeme doplnit i o sloupec E-mail pokud takový údaj využijeme.
4. Ve sloupci Poznámky si vedeme související poznámky a ve sloupci Datum od si zapíšeme od jakého data je daná osoba v dané roli.
5. U obsazení rolí postupujeme tak, že
	*  Pokud je role obsazena jednou či více konkrétních osob a je jedinečná v rámci celé organizace, uvedeme všechny osoby do sloupce Osoba.
	*  Pokud je role nejedinečná, třeba věcný správce pro každý informační systém, pak do sloupce Poznámky přesně zapíšeme, kde a jakým způsobem se obsazení rolí vede. Tedy kupříkladu, že věcný správce je veden v Evidenci informačních systémů.
6. ❗Tuto tabulku využíváme jako autoritativní zdroj dat o obsazení rolí.