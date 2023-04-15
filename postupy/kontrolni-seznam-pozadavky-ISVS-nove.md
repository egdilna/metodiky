---
layout: default
title: Kontrolní seznam požadavků na soulad ISVS se základními požadavky legislativy
description: "Tento postup se týká toho, s jakými základními legislativními požadavky musejí být nově v souladu informační systémy veřejné správy a na co se tedy připravit."
last_modified_date: 2023-04-06
nav_order: 4
parent: Kontrolní seznamy postupů
grand_parent: Postupy
---


# Kontrolní seznam požadavků na soulad ISVS se základními požadavky legislativy

Verze 1.0.1

Zpracováno jako výstup projektu egdilna.cz a partnerů v rámci EG konkrétních postupů

## Úvod

Toto je kontrolní seznam a postup zejména využitelný pro architekty a odborníky pro ICT v úřadech. Udává podrobnosti a návody, jak postupovat v jednotlivé oblasti.

Tento postup se týká toho, s jakými základními legislativními požadavky musejí být nově v souladu informační systémy veřejné správy a na co se tedy připravit.

Postup najdete vždy v rámci [sekce Postupy na webu metodiky.egdilna.cz](https://metodiky.egdilna.cz/postupy/eg-postupy)

Aktuální verze je na adrese

[https://metodiky.egdilna.cz/postupy/kontrolni-seznam-pozadavky-ISVS-nove](https://metodiky.egdilna.cz/postupy/kontrolni-seznam-pozadavky-ISVS-nove)

## Základní požadavky ISVS na soulad 

Tento kontrolní seznam slouží správcům informačních systémů veřejné správy, prostřednictvím zde uvedených bodů si mohou při asessmentu připravenosti svých ISVS přehledně a dostatečně podrobně zmapovat, v čem jsou již v souladu a co je v následujících úpravách čeká opravit.

### Pro Zákon 365/2000 o ISVS

- ISVS musí splňovat veškeré požadavky na ISVS, technické, architektonické, procesní i dokumentační

- ISVS a jeho architektura a technická realizace musí být v souladu s Národním architektonickým plánem

- K ISVS a všem jeho částem musí být vedena a aktualizována úplná dokumentace a to minimálně v rozsahu Vyhlášky o dlouhodobém řízení a Vyhlášky o kybernetické bezpečnosti

- ISVS musí poskytovat příslušné služby informačních činností a jejich řádné logování

- ISVS musí poskytovat vnitřní služby pro podporu výkonu agendy a vnější sdílené služby pro sdílení údajů a využívání a poskytování služeb jiných ISVS

- ISVS musí být provozován v infrastruktuře CMS a zajišťovat svoje služby pro OVM výhradně připojením přes CMS2

- ISVS musí uskutečňovat integrace s ostatními ISVS výhradně prostřednictvím Referenčního rozhraní

- ISVS musí umět poskytovat údaje subjektu údajů prostřednictvím ISVS nebo portálu s využitím zaručené elektronické identifikace

- ISVS musí poskytovat údaje formou služeb do Portálu občana

- Pokud ISVS zajišťuje příjem digitálních úkonů, nebo podání, nebo poskytování digitálních služeb, musí zajistit využití zaručené elektronické identifikace jako formu vlastnoručního podpisu a identity subjektu

- ISVS musí být řádně dekomponován do jednotlivých celků na úrovni komponent a rozhraní a musí být tato kompozice zpracována na úrovni architektury, bezpečnosti a technické realizace

- Pro spuštění služeb ISVS a každou změnu ISVS a nebo jeho služeb musí být souhlasné stanovisko OHA a NÚKIB

- ISVS a jeho technická realizace a rozvoj musí být v souladu s

	- Požadavky na ekonomickou výhodnost provozu ISVS

	- požadavky na řízení informačních systémů veřejné správy,

	- požadavky na kategorizaci informačních systémů veřejné správy podle bezpečnostních úrovní

	- Požadavky na dekomponování informačních systémů veřejné správy,

	- technické požadavky na informační systémy veřejné správy,

	- pravidla pro strukturování dat v informačních systémech veřejné správy

	- bezpečnostní požadavky na zajištění důvěrnosti, integrity a dostupnosti informací zpracovávaných v informačních systémech veřejné správy

- K ISVS musí být pro každou etapu jeho vývoje zpracována realizována architektura a to v rozsahu dle potřeb Národního architektonického plánu a s náležitostmi dle Národního architektonického rámce

- ISVS musí být řádně ohlášen v Rejstříku ISVS v Registru práv a povinností a správce musí udržovat ohlášené údaje o něm aktuální a pravidelně doplňovat údaje o jeho provozu a ekonomických ukazatelích a aplikační dekompozice

### Pro Zákon 111/2009 o základních registrech

- ISVS musí umožnit řádné plnění povinností souvisejících s využíváním údajů ze základních registrů

- ISVS musí umožňit řádně plnění povinností ke sdílení údajů v rámci agend s ostatními ISVS

- ISVS musí zajišťovat služby týkající se využívání referenčních údajů a identit subjektů

	- Evidování subjektu a jeho údajů v základním datovém kmenu

		- Ztotožnění fyzické osoby z Registru obyvatel

		- Ztotožnění právnického subjektu z Registru osob

		- Přihlášení k notifikaci změny údajů fyzické osoby z Registru obyvatel

		- Přihlášení k notifikaci změny údajů právnického subjektu z Registru osob

		- Zpracování notifikací o změnách údajů z Registru obyvatel

		- Zpracování notifikací o změnách údajů právnického subjektu z Registru osob

	- Aktualizace a udržování údajů o subjektu z referenční identity

		- Aktualizace údajů o fyzické osobě z Registru obyvatel podle notifikace o změně

		- Aktualizace údajů o fyzické osobě z Registru obyvatel pro aktuální potřebu

		- Aktualizace údajů z Registru osob

		- Aktualizace údajů z Registru osob a souvisejících údajů z Registru obyvatel

	- Reklamace vůči základním registrům a editorům

		- Reklamace údajů o subjektech a jejich identitách

		- Reklamace neexistující fyzické osoby v Registru obyvatel

		- Reklamace neexistujících údajů o fyzické osobě v Registru obyvatel

		- Reklamace údajů o fyzické osobě v Registru obyvatel

		- Reklamace údajů o právnickém subjektu z Registru osob

		- Získání výsledku vlastní reklamace

- ISVS musí zajišťovat služby týkající se sdílení údajů mezi agendami

	- Využívání práva na záznam skutečnosti v RPP

		- Záznam o odkazování klienta na Zápis o skutečnosti z RPP

		- Získání údajů Zápisu o skutečnosti z RPP

		- Reklamace údajů v zápisu o skutečnosti v RPP

	- Využívání agendových údajů jiných agend

		- Dotaz na existenci agendových údajů k subjektu v jiné agendě

		- Vyžádání agendového údaje z jiného AIS

		- Přihlášení notifikace o změně agendových údajů z jiné agendy

		- Získání agendového údaje z jiného AIS

		- Reklamace neexistujícího agendového údaje v jiné agendě

		- Reklamace agendového údaje v jiném AIS

		- Zpracování výsledku vlastní reklamace cizích agendových údajů

	- Poskytování agendových údajů jiným agendám

		- Poskytnutí informace, že agendový údaj neexistuje

		- Poskytnutí vlastních agendových údajů jinému AIS na vyžádání

		- Poskytnutí vlastních agendových údajů jinému AIS proaktivně

		- Poskytnutí vlastních agendových údajů jinému AIS při změně

		- Zpracování registrace notifikace ke změnám agendových údajů do jiných agend

- ISVS musí evidovat a spravovat údaje ohlášené pro danou agendu v rozsahu v němž jsou stanoveny jako údaje jež eviduje jako agendové

- ISVS musí zajišťovat služby logování využívání a sdílení údajů do centrálního řešení

### Pro Zákon 106/1999 o svobodném přístupu k informacím

- ISVS musí umět sestavit data pro jejich publikaci jako otevřená data

- ISVS musí umět připravit či zprostředkovat údaje publikované v rozhraní způsobem umožňujícím dálkový přístup

- ISVS musí zajišťovat publikaci dynamických dat pro publikační systém prostřednictvím API rozhraní

- ISVS musí zajišťovat podporu všem procesům stanoveným pro postupy úřadů a životní situace

### Pro Zákon 499/2004 o spisové službě

- ISVS musí splňovat povinnosti spisové služby a správy dokumentů a to jedním z těchto způsobů:

	- Musí sám splňovat veškeré procesní a technické požadavky stanovené Vyhláškou o podrobnostech výkonu spisové služby a Národním standardem pro elektronické systémy spisové služby

	- Musí splňovat procesní požadavky na správu dokumentů a tu technicky zajišťovat částečnou integrací na elektronický systém spisové služby

	- Musí být řádně integrován na elektronický systém spisové služby, který zajistí veškeré procesy a služby správy dokumentů

- ISVS musí umět přebírat doručené dokumenty z elektronického systému spisové služby a podatelny pro věcné zpracování dle agendy

- ISVS musí umět vytvářet digitální dokumenty alespoň jedním z těchto způsobů:

	- Pokud sám vytváří dokumenty, jím generované dokumenty musí splňovat veškeré technické požadavky a náležitosti

	- Pokud sám vytvářet dokumenty nebude, musí být schopen sestavit podklad a zavolat validní generátor dokumentů se všemi požadavky

- ISVS musí zajistit zápis každé události spojené s dokumentem a spisem do transakčního protokolu vedeného v elektronickém systému spisové služby

- Pokud ISVS zajišťuje příjem podání či digitálních úkonů jako ISVS či z jiného ISVS (třeba portálu), musí umět zjistit jeho validitu včetně identity odesílatele

### Pro Zákon 111/2019 o zpracování osobních údajů

- ISVS musí zpracovávat pouze ty údaje, které jsou buď agendovými údaji, nebo provozními údaji

- ISVS musí umožňovat přístup k údajům a funkcím pouze oprávněným uživatelům v jejich aktuální roli

- ISVS musí logovat veškerý přístup, využívání a zpracování osobních údajů a to včetně identity konkrétní fyzické osoby uživatele a důvodu

- ISVS musí obsahovat bezpečnostní funkce a mechanismy, aby bylo znemožněno jeho zneužití či neoprávněný přístup k údajům

- ISVS musí na požádání oprávněného uživatele poskytnout záznamy o zpracování údajů a přístupu k údajům

### Pro Zákon 181/2014 o kybernetické bezpečnosti

- Pro ISVS musí být vedena úplná bezpečnostní dokumentace a dokumentace testů a dokumentace pro analýzu rizik

- ISVS musí být architektonicky vyřešen tak, aby splňoval principy kybernetické bezpečnosti

