---
layout: default
title: ArchiMate v češtině - stručný průvodce
description: "Už před časem jsme pro vás připravili takovou stručnou miniučebnici jak poznat a číst výstupy v jazyce ArchiMate. Je určena zejména pro nearchitekty a i jim ukazuje, jak se v diagramech v ArchiMate mají vyznat."
parent: Oblast Služby
nav_order: 2
grand_parent: Metodiky
---


# ArchiMate v češtině: Stručný průvodce jazykem a jak ho číst

Stručný průvodce architektonickým jazykem ArchiMate pro nearchitekty a v češtině. Nenaučí vás v ArchiMate tvořit, ale naučíte se číst správně diagramy v tomto jazyce a pochopit co je co.


<!-- more -->

Verze 1.2 ze srpna 2022

(C) 2018-2022 EGdílna


OBSAH

- [ArchiMate v češtině: Stručný průvodce jazykem a jak ho číst](#archimate-vč-eštině-stručný-průvodce-jazykem-a-jak-hočí-st)
- [I. O jazyce Archimate](#i-o-jazyce-archimate)
  - [Co je vlastně Archimate?](#co-je-vlastně-archimate)
  - [Jak se poprat s jazykem Archimate?](#jak-se-poprat-s-jazykem-archimate)
  - [Základy archimate](#základy-archimate)
    - [Elementy](#elementy)
    - [Vazby](#vazby)
    - [Pohledy / Viewpointy](#pohledy-viewpointy)
  - [Popis a význam jednotlivých vrstev](#popis-a-význam-jednotlivých-vrstev)
    - [Strategická vrstva architektury](#strategická-vrstva-architektury)
    - [Byznysová vrstva architektury](#byznysová-vrstva-architektury)
    - [Aplikační vrstva architektury](#aplikační-vrstva-architektury)
    - [Technologická vrstva architektury](#technologická-vrstva-architektury)
    - [Motivační vrstva architektury](#motivační-vrstva-architektury)
    - [Implementační vrstva architektury](#implementační-vrstva-architektury)
- [II. Seznam a popis a zobrazení elementů jazyka Archimate](#ii-seznam-a-popis-a-zobrazení-elementů-jazyka-archimate)
  - [Přehled všech elementů podle vrstev](#přehled-všech-elementů-podle-vrstev)
  - [Popis a znázornění klíčových elementů jazyka Archimate](#popis-a-znázornění-klíčových-elementů-jazyka-archimate)
    - [Klíčové elementy Archimate na strategické vrstvě](#klíčové-elementy-archimate-na-strategické-vrstvě)
    - [Klíčové elementy Archimate na byznysové vrstvě](#klíčové-elementy-archimate-na-byznysové-vrstvě)
    - [Klíčové elementy Archimate na aplikační vrstvě](#klíčové-elementy-archimate-na-aplikační-vrstvě)
    - [Klíčové elementy Archimate na technologické vrstvě](#klíčové-elementy-archimate-na-technologické-vrstvě)
    - [Klíčové elementy Archimate na motivační vrstvě](#klíčové-elementy-archimate-na-motivační-vrstvě)
    - [Klíčové elementy Archimate na implementační vrstvě](#klíčové-elementy-archimate-na-implementační-vrstvě)
    - [Ostatní klíčové elementy Archimate mimo základní vrstvy](#ostatní-klíčové-elementy-archimate-mimo-základní-vrstvy)



# I. O jazyce Archimate

## Co je vlastně Archimate?

Archimate® je standardizovaný mezinárodní jazyk pro ICT architekturu. Používá se celosvětově jak

## Jak se poprat s jazykem Archimate?

Archimate® jako každý jiný jazyk má svoje pravidla a postupy, které je nutné dodržovat, abychom mu dobře rozuměli. Můžeme ho z části považovat za jazyk komunikační (čili takový, kterým se mluví či vyjadřuje), ale také za jazyk programátorský, (tedy, kterým se dá exaktně znázornit hierarchie a vazba jedné věci na druhou). 

Má svoji sémantiku a svoje pravidla pro zapisování jednotlivých elementů a vazeb a určité podmínky pro to, co lze s jeho pomocí vyjádřit. Má ale také jasně definované grafické znázornění, tedy diagramy zpracované v jazyce archimate je schopen číst každý, kdo ví, co jednotlivý obdélník či obrázek znamená.

Pro architekty je nepochybně nutné znát tento jazyk velice podrobně a být schopni v tomto jazyce také zpracovávat jednotlivé modely architektury. Pro běžného uživatele ale úplně postačí, když dostane do rukou seznam všech elementů s jejich popisy a to, jak dané elementy vypadají. Tím se dokáže kdokoliv naučit číst diagramy zpracovávané v tomto architektonickém jazyce, aniž by nutně musel ovládat veškeré jeho záludnosti.

## Základy archimate 

V jazyce jsou tři důležité věci:

* Prvky (elementy): To jsou jednotlivé architektonické objekty
* Vazby: To jsou vazby mezi elementy
* Vrstvy: To jsou jakési filozofické části architektury

Kromě toho se můžete ještě v Archimate setkat také s pohledy, ty si představte jako jakési standardizované náhledy na určité kusy architektury, ale pro běžného čtenáře jsou vlastně nezajímavé, protože je vytváří architekt a architektonický nástroj.

### Elementy

Elementy jsou základní stavební prvky jazyka. Vyjádřené jsou zpravidla pomocí „krabiček“ s ikonkami. Ty nejčastěji popisují něco, co existuje, činnosti, které někdo nebo něco vykonává, motivaci nebo další témata.

Archimate rozlišuje elementy na Aktivní, Behaviorální a Pasivní, čímž se dost blíží větnému pojetí jazyka. Aktivní element se chová (behaviorálně) vůči pasivnímu elementu.

> Příklad: Já právě píšu učební text o Archimate. Já je aktivní element (aktér Já), píšu je vykonávaná činnost chování (behaviorální) a výsledek je učební texty pro Archimate, což je tedy prvek pasivní.

Obyčejný člověk v roli čtenáře a prostého uživatele obrázků v Archimate se ale tímhle členěním nemusí moc trápit.


### Vazby

Vazby vyjadřují vztahy mezi elementy a jsou zpravidla znázorněné pomocí různých čar se značkami na koncích.

### Pohledy / Viewpointy

S elementy a vazbami to ale nekončí, na rozdíl od jiných jazyků definuje Archimate i hlediska, kterým se ale i u nás nejčastěji říká anglickým viewpoint.

Viewpoint představuje perspektivu, ze které se na něco dívám a to, co vidím je pohled (view). Nebudeme se zatím příliš trápit teorií, tak si pro zjednodušení můžeme představit viewpoint jako šablonu, která nám říká, jak máme vybrané téma zachytit. Viewpointy jsou jedna z nejdůležitějších věcí v Archimatu, přesto je hodně lidí ignoruje. Částečně je to dané nepochopením, hlavním důvodem je ale absence podpory viewpointů v nejvíce rozšířených nástrojích Sparx Systems Enterprise Architect a MS Visio.

> Zdroj: https://www.modelovaci-jazyky.cz/archimate-obsah/

## Popis a význam jednotlivých vrstev

Architektura se dělí do vrstev a stejně i jazyk Archimate. Každá vrstva má svoji barvu a svůj daný set elementů, kterými se vyjadřují objekty na dané vrstvě. To samo pro pochopení Archimate pro laiky není tak podstatné. Podstatné ale je, aby rozuměli tomu, co znamená která vrstva a co v ní tedy přibližně najdou.

### Strategická vrstva architektury

Od strategie se vše odvíjí. Strategie je základ pro jakékoliv konání, včetně popisu a změn v architektuře. Pro strategii jsou důležité schopnosti a zdroje, nicméně samotná strategie je základem pro další vrstvy. Proto je také vždy na prvním místě.


### Byznysová vrstva architektury

V této vrstvě se popisuje vše, co děláme, protože vše, co činíme, je součástí našeho byznysu. Ať už se opravdu jedná o byznys jako obchod, nebo o naplnění našeho poslání, na této vrstvě musíme vyjádřit, co vlastně děláme, kdo to dělá, jak to dělá a s kým, či pro koho to dělá. Byznys je uváděn hned pod strategií, protože je to prostě náš byznys.


### Aplikační vrstva architektury

Na této vrstvě popisujeme aplikace, programy, data, výměnu dat, a vše co zajistí, že byznys budeme schopni s pomocí ICT opravdu dělat. A to včetně technických dat a databází a systémů, které pro nás zajišťují fungování onoho byznysu v praxi.

### Technologická vrstva architektury

Někdy označovaná i jako infrastrukturní. Jedná se o vrstvu všech technologických prostředků a zařízení, které potřebujeme k tomu, aby nám fungovaly aplikace a systémy a data, a tedy, abychom s technickou pomocí mohli dělat byznys a plnit naši strategii. Místy je dost problematické odlišovat aplikační a technologickou vrstvu a jednotlivé elementy (zejména softwarové) se často zaměňují.

### Motivační vrstva architektury

Motivační vrstva ukazuje to, co motivuje či donucuje ke změnám v byznysu a v architektuře. Tedy motivací může být nějaký požadavek, externí vliv, zvýšení poptávky či cíl zvýšení kvality, nebo nějaké nové omezení způsobené změnou legislativy apod. V motivační vrstvě najdeme také trochu nelogicky reprezentaci požadavků, včetně požadavků na byznys a aplikace a technologie.

### Implementační vrstva architektury

Na této vrstvě se řeší změna určitého stavu ze současného (as-is) do budoucího chtěného (to-be) a to, co se musí pro tuto změnu udělat. Tedy implementace nového byznysu, implementace nových aplikací či jejich změn apod. 


# II. Seznam a popis a zobrazení elementů jazyka Archimate

{:toc}

V tomto dokumentu najdete nejen přehledný popis všech důležitých elementů jazyka Archimate®, ale především zobrazení těchto elementů. Abyste dokázali přečíst jakýkoliv diagram v Archimate, musíte vědě nejen to, co element znamená a jaký je jeho význam a použití v architektuře, ale také to, jak vypadá graficky. Grafická prezentace objektů je totiž v Archimate velice důležitá.

Na tomto místě získáte zcela ojedinělý přehled o tom, jak vypadá vše v Archimate.


## Přehled všech elementů podle vrstev

Níže je seznam všech elementů podle jednotlivých vrstev. Seznam je záměrně řazen dle anglického originálního názvu. U každého elementu je uveden jeho český popis.

1. Strategická vrstva
    - Schopnost (Capability) - Poskytuje pohled na vysoké úrovni o současných a požadovaných schopnostech organizace ve vztahu k její strategii a prostředí. Schopnost je ucelenou sadou dovedností, znalostí, potřeb, kontraktů, procesů, služeb a dalších objektů na všech úrovních, které dohromady dávají definovatelný celek.
    - Prováděcí postup (CourseOfAction) - Prováděcí postup je přístup nebo plán pro konfiguraci některých schopností a zdrojů podniku, prováděných za účelem dosažení cíle. Prováděcí postup představuje to, co se podnik rozhodl udělat. Lze je kategorizovat jako strategie (dlouhodobé) a taktiky (krátkodobé).
    - Zdroj (Resource) - Představuje definovatelný zdroj, který je za potřebí mít k dodažení strategie a který se využije pro realizaci strategií, byznysu a procesů.
    - Tok (ValueStream) - Tok hodnot představuje sled činností, které vytvářejí celkový výsledek pro zákazníka, zúčastněné strany nebo koncového uživatele. Hodnotový tok popisuje, jak podnik organizuje své činnosti tak, aby vytvářel hodnotu. Proudy hodnot jsou obvykle realizovány podnikovými procesy, a případně dalšími klíčovými prvky chování. Proudy hodnot mohou být definovány na různých úrovních organizace, např. na úrovni podniku, obchodní jednotky nebo oddělení. Proudy hodnot mohou být složením nebo agregací činností s přidanou hodnotou. Tyto jsou také modelovány s prvkem hodnotového toku a jsou známé jako hodnotové (proudové) fáze, z nichž každá vytváří a přidává inkrementální hodnotu z jedné fáze do další. Tyto fáze jsou obvykle spojeny pomocí tokových vztahů k modelování toku hodnoty mezi nimi.
2. Byznysová vrstva
    - Aktér, Účastník (BusinessActor) - Aktér/Účastník je definován jako organizační jednotka schopna vykonávat aktivitu přiřazenou k jedné nebo více byznys rolím. Aktér je subjekt, může to být jedna organizace, organizační jednotka, OVM, nebo samozřejmě i osoba.
    - Spolupráce (BusinessCollaboration) - Spojení dvou a více rolí pracující společně k vykonání určitého kolektivního chování. Nebo jiná spolupráce rolí.
    - Událost, procesní událost (BusinessEvent) - Něco, co se stává (interně nebo externě) a ovlivňuje chování.
    - Funkce (byznysově) (BusinessFunction) - Prvek chování, který seskupuje chování podle vybraná sady kritérií (typicky požadovaných dovedností, znalostí, zdrojů).
    - Interakce (BusinessInteraction) - Prvek chování, který popisuje chování spolupráce.
    - Rozhraní (BusinessInterface) - Přístupový bod, kde je procesní služba dostupná okolnímu prostředí. Tedy kupříkladu terminál, uživatelské rozhraní, rozhraní služby, ale může to de facto být i formulář.
    - Objekt (BusinessObject) - Pasivní element, který má relevanci z předmětného pohledu. Jedná se o fyzický či logický objekt, o němž se vykonává proces či služba. Dokument, doklad, žádost, dávka, rozhodnutí, prakticky cokoliv, co se dá fyzicky či logicky reprezentovat.
    - Proces (BusinessProcess) - Prvek chování, který sdružuje skupiny chování na základě pořadí činností. Je určen k produkování sady produktů nebo byznys služeb.
    - Role (BusinessRole) - Role je fakticky zodpovědnost za vykonávání specifického chování, ke které může být přiřazen účastník procesu.
    - Byznysová služba (BusinessService) - Byznys služba je definována jako služba, která naplňuje potřeby zákazníka (interního nebo externího vůči poskytující organizaci).
    - Kontrakt, předpis (Contract) - Formální nebo neformální specifikace dohody, která specifikuje práva a povinnosti spojené s produktem.
    - Produkt (Product) - Produkt je soubor služeb definovaných kontraktem (zákonem), které jsou společně poskytovány klientovi (pro jeho životní situaci).
    - Reprezentace (Representation) - Smyslově vnímatelná forma informací spojených s byznys objektem. Tedy kupříkladu fyzický dokument, plastová kartička občanského průkazu apod.
3. Aplikační vrstva
    - Aplikační spolupráce (ApplicationCollaboration) - Souhrn dvou nebo více komponent aplikací, které pracují společně za účelem vykonání kolektivního chování
    - Aplikace, Systém, Komponenta aplikace, Modul, Část aplikace (ApplicationComponent) - Modulární, nasaditelná a nahraditelná část softwarového systému, zapouzdřující své chování a data, která poskytuje skrz sadu rozhraní. Může se jednat o celý logický informační systém, o nějakou ucelenou komponentu nebo modul, nebo o část aplikace, jež se nasazuje a rozvíjí jako část celku.
    - Aplikační funkce (ApplicationFunction) - Aplikační funkce je definována jako interní chování jedné aplikační komponenty.
    - Interakce aplikace (ApplicationInteraction) - Prvek chování, který popisuje chování aplikací při jejich kooperaci.
    - Rozhraní aplikace, Aplikační rozhraní (ApplicationInterface) - Přístupový bod, ve kterém je služba aplikace dostupná pro využití uživatelem nebo jinou komponentou aplikace.
    - Aplikační služba (ApplicationService) - Služba, která poskytuje automatizované chování.
    - Datový objekt (DataObject) - Pasivní element, který je zpracováván za použití výpočetní techniky. Jedná se o data, soubor dat nebo údajů, které jsou zpracovávány většinou v rámci aplikační komponenty.
4. Technologická vrstva
    - Artefakt (Artifact) - Artefaktem se rozumí fyzická reprezentace dat, která je používána či vytvářena systémem.
    - Zařízení (Device) - Hardwarový zdroj, na kterém mohou být skladovány nebo dislokovány artefakty pro použití.
    - Síť (Network) - Komunikační medium mezi dvěma nebo více zařízeními.
    - Uzel (Node) - Výpočetní zdroj, na kterém mohou být skladovány, dislokovány nebo zpracovávány artefakty pro použití. Poskytuje především služby výpočetního výkonu a datových kapacit.
    - Cesta (CommunicationPath) - Spojení mezi dvěma nebo více uzly, skrze které si mohou tyto uzly vyměňovat data.
    - Systémový software (SystemSoftware) - Softwarové prostředí pro speciální typ komponentů a objektů, které jsou na něm rozmístěny ve formě artefaktů.
    - Rozhraní infrastruktury (TechnologyInterface) - Přístupový bod, kde služby infrastruktury nabízené uzlem mohou být využity jiným uzlem nebo komponentou aplikace.
    - Služby infrastruktury (TechnologyService) - Externě viditelná jednotka funkcionality poskytovaná jedním nebo více uzly, která je přístupná přes dobře definované rozhraní a má význam pro okolí.
5. Motivační vrstva
    - Zhodnocení (Assesment) - Výsledek analýzy motivátoru. Zhodnucuje dopad motivátoru na organizaci a zhodnocuje výsledek analýzy nasazení změn pro splnění daného motivátoru.
    - Omezení (Constraint) - Omezení na cestě k realizaci systému.
    - Motivátor (Driver) - Motivátor je definován jako okolnost, která vytváří, motivuje a podporuje změnu v organizaci.
    - Cíl (Goal) - Koncový stav, kterého chce zainteresovaný subjekt (stakeholder) dosáhnout.
    - Význam (Meaning) - Znalost nebo odbornost přítomná v byznys objektu nebo v jeho reprezentaci
    - Výstup (Outcome) - Reprezentuje jednoznačný výstup, zejména jako výsledek schopností organizace či výsledek obchodního snažení nebo realizace strategie. Výstup je buď hmatatelný na úrovni dovednosti vytvářet produkt, nebo se jedná o výstup jež se pozitivně odráží na podnikání či činnosti organizace. Jednou z motivací pro zlepšení organizace je tedy dovednost učinit výstup.
    - Princip (Principle) - Normovaná vlastnost všech systémů v daném kontextu, nebo způsob jejich realizace. Principy vycházejí ze strategických cílů a svými důsledky formují a formulují architektonické požadavky.
    - Požadavek (Requirement) - Stanovisko, formálně vyjádřená potřeba, která musí být v systému (resp. architekturou) realizována. Jedná se o architektonické nikoli byznysové požadavky.
    - Zainteresovaný subjekt (Stakeholder) - Zainteresovaný jedinec, tým nebo organizace, která má zájem na přínosu architektury.
    - Hodnota (Value) - Hodnota představuje přínos, užitek nebo důležitost produktu či služby
6. Implementační vrstva
    - Dodaný výstup (Deliverable) - Přesně definovaný výsledek pracovního bloku.
    - Rozdíl (Gap) - Rozdíl je napojený na dva stavy architektury (např. výchozí a cílovou nebo dvě přechodové), a tudíž představuje znázornění rozdílů mezi těmito dvěma stavy architektury.
    - Stav architektury (Plateau) - Relativně stabilní stav architektury, která existuje (existovala) během omezeného časového období.
    - Pracovní blok (WorkPackage) - Série akcí navržená tak, aby dosáhla vytyčeného cíle ve specifikovaném čase.
7. Ostatní elementy mimo vrstvy
    - Spojení (Junction) - Spojení slouží k vyjádření toho, že se na nějakém vztahu podílí více prvků. Může se jednat o více prvků na vstupu a jediný na výstupu, o jeden na vstupu a více na výstupu a nebo o více prvků na obou stranách. Slouží k vyjádření, že pro realizaci daného vztahu je nutno počítat se zapojením více elementů.
    - Lokalita, místo (Location) - Místo v prostoru, kde se nacházejí aktéři nebo kde je vykonáváno chování.

## Popis a znázornění klíčových elementů jazyka Archimate


Elementy jsou zobrazováni v pohledech, tedy obrázkových diagramech. Aby i neodborník dokázal snadno tyto diagramy číst, níže je grafické znázornění elementů pro jednotlivé vrstvy následováné vždy tabulkou pro danou vrstvu s vysvětlením významu elementu.

### Klíčové elementy Archimate na strategické vrstvě

Od strategie se vše odvíjí. Strategie je základ pro jakékoliv konání, včetně popisu a změn v architektuře. Pro strategii jsou důležité schopnosti a zdroje, nicméně samotná strategie je základem pro další vrstvy. Proto je také vždy na prvním místě.

![Přehled elementů ArchiMate v češtině: strategická vrstva, Zdroj: ArchiMate v češtině, EGOVedu](https://github.com/egdilna/archimate_cz/raw/master/docs/dokumenty/zobrazeni_archimate_elementu_strategicka_vrstva.png)

| Element | Popis |
|---|---|
| Prováděcí postup (CourseOfAction) | Prováděcí postup je přístup nebo plán pro konfiguraci některých schopností a zdrojů podniku, prováděných za účelem dosažení cíle. Prováděcí postup představuje to, co se podnik rozhodl udělat. Lze je kategorizovat jako strategie (dlouhodobé) a taktiky (krátkodobé).|
| Schopnost (Capability) | Poskytuje pohled na vysoké úrovni o současných a požadovaných schopnostech organizace ve vztahu k její strategii a prostředí. Schopnost je ucelenou sadou dovedností, znalostí, potřeb, kontraktů, procesů, služeb a dalších objektů na všech úrovních, které dohromady dávají definovatelný celek.|
| Tok (ValueStream) | Tok hodnot představuje sled činností, které vytvářejí celkový výsledek pro zákazníka, zúčastněné strany nebo koncového uživatele. Hodnotový tok popisuje, jak podnik organizuje své činnosti tak, aby vytvářel hodnotu. Proudy hodnot jsou obvykle realizovány podnikovými procesy, a případně dalšími klíčovými prvky chování. Proudy hodnot mohou být definovány na různých úrovních organizace, např. na úrovni podniku, obchodní jednotky nebo oddělení. Proudy hodnot mohou být složením nebo agregací činností s přidanou hodnotou. Tyto jsou také modelovány s prvkem hodnotového toku a jsou známé jako hodnotové (proudové) fáze, z nichž každá vytváří a přidává inkrementální hodnotu z jedné fáze do další. Tyto fáze jsou obvykle spojeny pomocí tokových vztahů k modelování toku hodnoty mezi nimi.|
| Zdroj (Resource) | Představuje definovatelný zdroj, který je za potřebí mít k dodažení strategie a který se využije pro realizaci strategií, byznysu a procesů.|


### Klíčové elementy Archimate na byznysové vrstvě

V této vrstvě se popisuje vše, co děláme, protože vše, co činíme, je součástí našeho byznysu. Ať už se opravdu jedná o byznys jako obchod, nebo o naplnění našeho poslání, na této vrstvě musíme vyjádřit, co vlastně děláme, kdo to dělá, jak to dělá a s kým či pro koho to dělá. Byznys je uváděn hned pod strategií, protože je to prostě náš byznys.

![Přehled elementů ArchiMate v češtině: byznysová vrstva, Zdroj: ArchiMate v češtině, EGOVedu](https://github.com/egdilna/archimate_cz/raw/master/docs/dokumenty/zobrazeni_archimate_elementu_byznysova_vrstva.png)

| Element | Popis |
|---|---|
| Aktér, Účastník (BusinessActor) | Aktér/Účastník je definován jako organizační jednotka schopna vykonávat aktivitu přiřazenou k jedné nebo více byznys rolím. Aktér je subjekt, může to být jedna organizace, organizační jednotka, OVM, nebo samozřejmě i osoba.|
| Byznysová služba (BusinessService) | Byznys služba je definována jako služba, která naplňuje potřeby zákazníka (interního nebo externího vůči poskytující organizaci).|
| Funkce (byznysově) (BusinessFunction) | Prvek chování, který seskupuje chování podle vybraná sady kritérií (typicky požadovaných dovedností, znalostí, zdrojů).|
| Interakce (BusinessInteraction) | Prvek chování, který popisuje chování spolupráce.|
| Kontrakt, předpis (Contract) | Formální nebo neformální specifikace dohody, která specifikuje práva a povinnosti spojené s produktem.|
| Objekt (BusinessObject) | Pasivní element, který má relevanci z předmětného pohledu. Jedná se o fyzický či logický objekt, o němž se vykonává proces či služba. Dokument, doklad, žádost, dávka, rozhodnutí, prakticky cokoliv, co se dá fyzicky či logicky reprezentovat.|
| Proces (BusinessProcess) | Prvek chování, který sdružuje skupiny chování na základě pořadí činností. Je určen k produkování sady produktů nebo byznys služeb.|
| Produkt (Product) | Produkt je soubor služeb definovaných kontraktem (zákonem), které jsou společně poskytovány klientovi (pro jeho životní situaci).|
| Reprezentace (Representation) | Smyslově vnímatelná forma informací spojených s byznys objektem. Tedy kupříkladu fyzický dokument, plastová kartička občanského průkazu apod.|
| Role (BusinessRole) | Role je fakticky zodpovědnost za vykonávání specifického chování, ke které může být přiřazen účastník procesu.|
| Rozhraní (BusinessInterface) | Přístupový bod, kde je procesní služba dostupná okolnímu prostředí. Tedy kupříkladu terminál, uživatelské rozhraní, rozhraní služby, ale může to de facto být i formulář.|
| Spolupráce (BusinessCollaboration) | Spojení dvou a více rolí pracující společně k vykonání určitého kolektivního chování. Nebo jiná spolupráce rolí.|
| Událost, procesní událost (BusinessEvent) | Něco, co se stává (interně nebo externě) a ovlivňuje chování.|



### Klíčové elementy Archimate na aplikační vrstvě

Na této vrstvě popisujeme aplikace, programy, data, výměnu dat, a vše co zajistí, že byznys budeme schopni s pomocí ICT opravdu dělat. A to včetně technických dat a databází a systémů, které pro nás zajišťují fungování onoho byznysu v praxi.

![Přehled elementů ArchiMate v češtině: aplikační vrstva, Zdroj: ArchiMate v češtině, EGOVedu](https://github.com/egdilna/archimate_cz/raw/master/docs/dokumenty/zobrazeni_archimate_elementu_aplikacni_vrstva.png)

| Element | Popis |
|---|---|
| Aplikace, Systém, Komponenta aplikace, Modul, Část aplikace (ApplicationComponent) | Modulární, nasaditelná a nahraditelná část softwarového systému, zapouzdřující své chování a data, která poskytuje skrz sadu rozhraní. Může se jednat o celý logický informační systém, o nějakou ucelenou komponentu nebo modul, nebo o část aplikace, jež se nasazuje a rozvíjí jako část celku.|
| Aplikační funkce (ApplicationFunction) | Aplikační funkce je definována jako interní chování jedné aplikační komponenty.|
| Aplikační služba (ApplicationService) | Služba, která poskytuje automatizované chování.|
| Aplikační spolupráce (ApplicationCollaboration) | Souhrn dvou nebo více komponent aplikací, které pracují společně za účelem vykonání kolektivního chování|
| Datový objekt (DataObject) | Pasivní element, který je zpracováván za použití výpočetní techniky. Jedná se o data, soubor dat nebo údajů, které jsou zpracovávány většinou v rámci aplikační komponenty.|
| Interakce aplikace (ApplicationInteraction) | Prvek chování, který popisuje chování aplikací při jejich kooperaci.|
| Rozhraní aplikace, Aplikační rozhraní (ApplicationInterface) | Přístupový bod, ve kterém je služba aplikace dostupná pro využití uživatelem nebo jinou komponentou aplikace.|



### Klíčové elementy Archimate na technologické vrstvě

Někdy označovaná i jako infrastrukturní. Jedná se o vrstvu všech technologických prostředků a zařízení, které potřebujeme k tomu, aby nám fungovaly aplikace a systémy a data, a tedy abychom s technickou pomocí mohli dělat byznys a plnit naši strategii. Místy je dost problematické odlišovat aplikační a technologickou vrstvu a jednotlivé elementy (zejména softwarové) se často zaměňují.

![Přehled elementů ArchiMate v češtině: technologická vrstva, Zdroj: ArchiMate v češtině, EGOVedu](https://github.com/egdilna/archimate_cz/raw/master/docs/dokumenty/zobrazeni_archimate_elementu_technologicka_vrstva.png)

| Element | Popis |
|---|---|
| Artefakt (Artifact) | Artefaktem se rozumí fyzická reprezentace dat, která je používána či vytvářena systémem.|
| Cesta (CommunicationPath) | Spojení mezi dvěma nebo více uzly, skrze které si mohou tyto uzly vyměňovat data.|
| Rozhraní infrastruktury (TechnologyInterface) | Přístupový bod, kde služby infrastruktury nabízené uzlem mohou být využity jiným uzlem nebo komponentou aplikace.|
| Služby infrastruktury (TechnologyService) | Externě viditelná jednotka funkcionality poskytovaná jedním nebo více uzly, která je přístupná přes dobře definované rozhraní a má význam pro okolí.|
| Systémový software (SystemSoftware) | Softwarové prostředí pro speciální typ komponentů a objektů, které jsou na něm rozmístěny ve formě artefaktů.|
| Síť (Network) | Komunikační medium mezi dvěma nebo více zařízeními.|
| Uzel (Node) | Výpočetní zdroj, na kterém mohou být skladovány, dislokovány nebo zpracovávány artefakty pro použití. Poskytuje především služby výpočetního výkonu a datových kapacit.|
| Zařízení (Device) | Hardwarový zdroj, na kterém mohou být skladovány nebo dislokovány artefakty pro použití.|



### Klíčové elementy Archimate na motivační vrstvě

Motivační vrstva ukazuje to, co motivuje či donucuje ke změnám v byznysu a v architektuře. Tedy motivací může být nějaký požadavek, externí vliv, zvýšení poptávky či cíl zvýšení kvality, nebo nějaké nové omezení způsobené změnou legislativy apod. V motivační vrstvě najdeme také trochu nelogicky reprezentaci požadavků, včetně požadavků na byznys a aplikace a technologie.

![Přehled elementů ArchiMate v češtině: motivační vrstva, Zdroj: ArchiMate v češtině, EGOVedu](https://github

| Element | Popis |
|---|---|
| Cíl (Goal) | Koncový stav, kterého chce zainteresovaný subjekt (stakeholder) dosáhnout.|
| Hodnota (Value) | Hodnota představuje přínos, užitek nebo důležitost produktu či služby|
| Motivátor (Driver) | Motivátor je definován jako okolnost, která vytváří, motivuje a podporuje změnu v organizaci.|
| Omezení (Constraint) | Omezení na cestě k realizaci systému.|
| Požadavek (Requirement) | Stanovisko, formálně vyjádřená potřeba, která musí být v systému (resp. architekturou) realizována. Jedná se o architektonické nikoli byznysové požadavky.|
| Princip (Principle) | Normovaná vlastnost všech systémů v daném kontextu, nebo způsob jejich realizace. Principy vycházejí ze strategických cílů a svými důsledky formují a formulují architektonické požadavky.|
| Výstup (Outcome) | Reprezentuje jednoznačný výstup, zejména jako výsledek schopností organizace či výsledek obchodního snažení nebo realizace strategie. Výstup je buď hmatatelný na úrovni dovednosti vytvářet produkt, nebo se jedná o výstup jež se pozitivně odráží na podnikání či činnosti organizace. Jednou z motivací pro zlepšení organizace je tedy dovednost učinit výstup.|
| Význam (Meaning) | Znalost nebo odbornost přítomná v byznys objektu nebo v jeho reprezentaci|
| Zainteresovaný subjekt (Stakeholder) | Zainteresovaný jedinec, tým nebo organizace, která má zájem na přínosu architektury.|
| Zhodnocení (Assesment) | Výsledek analýzy motivátoru. Zhodnucuje dopad motivátoru na organizaci a zhodnocuje výsledek analýzy nasazení změn pro splnění daného motivátoru.|





### Klíčové elementy Archimate na implementační vrstvě

Na této vrstvě se řeší změna určitého stavu ze současného (as-is) do budoucího chtěného (to-be) a to, co se musí pro tuto změnu udělat. Tedy implementace nového byznysu, implementace nových aplikací či jejich změn apod. 

![Přehled elementů ArchiMate v češtině: implementační vrstva, Zdroj: ArchiMate v češtině, EGOVedu](https://github.com/egdilna/archimate_cz/raw/master/docs/dokumenty/zobrazeni_archimate_elementu_implementacni_vrstva.png)

| Element | Popis |
|---|---|
| Dodaný výstup (Deliverable) | Přesně definovaný výsledek pracovního bloku.|
| Pracovní blok (WorkPackage) | Série akcí navržená tak, aby dosáhla vytyčeného cíle ve specifikovaném čase.|
| Rozdíl (Gap) | Rozdíl je napojený na dva stavy architektury (např. výchozí a cílovou nebo dvě přechodové), a tudíž představuje znázornění rozdílů mezi těmito dvěma stavy architektury.|
| Stav architektury (Plateau) | Relativně stabilní stav architektury, která existuje (existovala) během omezeného časového období.|



### Ostatní klíčové elementy Archimate mimo základní vrstvy


![Přehled elementů ArchiMate v češtině: ostatní prvky, Zdroj: ArchiMate v češtině, EGOVedu](https://github.com/egdilna/archimate_cz/raw/master/docs/dokumenty/zobrazeni_archimate_elementu_ostatni.png)

| Element | Popis |
|---|---|
| Lokalita, místo (Location) | Místo v prostoru, kde se nacházejí aktéři nebo kde je vykonáváno chování.|
| Spojení (Junction) | Spojení slouží k vyjádření toho, že se na nějakém vztahu podílí více prvků. Může se jednat o více prvků na vstupu a jediný na výstupu, o jeden na vstupu a více na výstupu a nebo o více prvků na obou stranách. Slouží k vyjádření, že pro realizaci daného vztahu je nutno počítat se zapojením více elementů.|

