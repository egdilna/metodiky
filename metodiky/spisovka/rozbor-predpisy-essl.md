---
layout: default
title: Detailní rozbor změn legislativy ke spisové službě
description: "Ministerstvo vnitra zpracovalo rozbor a přehled změn legislativy ke spisové službě a to zejména novelizace vyhlášky o podrobnostech výkonu spisové služby a národního standardu pro elektronické systémy spisové služby."
parent: Oblast Spisová služba
nav_order: 1
grand_parent: Metodiky
---



# Úvod

Toto je dokument detailního rozboru změn v legislativních podzákonných předpisech týkajících se výkonu spisové služby.

Zdrojem pro tento detailní rozbor jsou dokumenty [Metodika ke změnám vyhlášky](https://www.mvcr.cz/soubor/zverejneni-metodickych-materialu-k-atestacim-essl-a-zmenam-legislativy-metodika-ke-zmenam-vyhlasky.aspx) a a [Popis změn v NSESSS](https://www.mvcr.cz/soubor/zverejneni-metodickych-materialu-k-atestacim-essl-a-zmenam-legislativy-popis-zmen-v-nsesss.aspx), které vydává Odbor archivnictví a spisové služby Ministerstva vnitea ČR.

ℹ️ TZpracovatelem zdrojových dokumentů je Ministerstvo vnitra, Odbor archivnictví a spisové služby. Dokumenty byly zpracovány s inspirací v našich rozborech změny právních předpisů.



# Popis zásadních změn v národním standardu pro elektronické systémy spisové služby 
 
Znění Národního standardu pro elektronické systémy spisové služby (dále jen „NSESSS“) předkládané v roce 2023 není novelou stávajícího standardu, ale zcela novým zněním, ačkoliv zachovává část původních ustanovení i schémat XML. 

V novém znění (Věstník Ministerstva vnitra čá. 42/2023) byly odstraněny odkazy na požadavky předchozího znění NSESSS i narativní úvody kapitol. 

## Terminologie

V oblasti terminologie dochází k narovnání mezi NSESSS a vyhláškou, zejména 

* je nově definována komponenta (pouze pro digitální dokumenty) a v souvislosti s ní kontejnerové datové formáty. 
* S ohledem na upřesněné znění požadavků jsou nově definovány kontejnerové datové formáty a jejich zpracování
* Je definována šablona typového spisu 
* Nově je definována také uživatelská role zpracovatele zahrnující všechny role, které mohou s entitou pracovat včetně podepisující osoby. 
* Z terminologie také zmizela „zásilka“ a „redakce“ a některé pojmy, jejichž význam není třeba vysvětlovat („verze“, „webová služba“). 
* Z důvodu kolize terminologie došlo ke změně pojmu „typ dokumentu“ na „druh dokumentu

## Obecné změny ve správě dokumentů


* Do NSESSS  jsou obecně promítnuty zásadní změny v koncepci zpracování dokumentů: 
	* povinné vyřizování ve spisu, 
	* převod datových formátů na výstupní co nejdříve je to možné a účelné, 
	* možnost hierarchicky uspořádaných součástí v typovém spisu a další. 

## Evidence dokumentů

* V oblasti příjmu a evidence dokumentu byl odstraněn „rozpracovaný dokument (koncept)“
* Na dokument, resp. komponenty v elektronickém systému spisové služby (dále jen „eSSL“) se nově pohlíží jednotným způsobem s tím, že komponenty dokumentu mohou být verzovány.
* povinnost při příjmu zjistit a zaznamenat datový formát, a to na základě vnitřní struktury komponenty, nikoli pouhé přípony, 
* povinnost přijmout entity podle XML schémat stanovených v příloze NSESSS, 
* může být odmítnuta a do eSSL neuložena komponenta, která trpí vadou, kvůli níž bude odesílatel vyzván k opravě (nepřijímaný formát, nadměrná velikost) a na místo komponenty se uloží ztvárnění metadat s popisem důvodu odmítnutí, 
* při příjmu e-mailu musí být zajištěn i příjem jinde než na podatelně a to „prostřednictvím funkčního rozšíření poštovního klienta nebo prostředky eSSL“, 
* byl zmenšen rozsah metadat automaticky vyjímaných z e-mailové zprávy, 
* u datových zpráv z ISDS musí eSSL nově identifikovat její datovou velikost, 
* v případě kontejnerových datových formátů (komponenty obsahující jinou komponentu nebo komponenty) jsou stanoveny případy, kdy je eSSL musí vždy zpracovat automaticky (dekomponovat): ASiC, FO/ZFO, EML, ISDOCX, ZIP, PDF/A a současně musí uchovat původní podobu komponenty nejméně do okamžiku uzavření spisu (to samé platí i pro e-maily a datové zprávy z Informačního systému datových schránek), 
* nově musí eSSL zajistit převod stanovených datových formátů DOC, DOCX, XLS, XLSX, PPT, PPTX, ODT, ODS, ODP, RTF, TXT, PDF, HTM, HTML, BMP do výstupního datového formátu postupem změny datového formátu podle §69a zákona č. 499/2004 Sb. ihned po ověření zajišťovacích prvků (uznávaný elektronický podpis, uznávaná elektronická značka a kvalifikované elektronické časové razítko), 
* údaje o ověření je možno zaznamenat nejen do metadat, ale i ztvárnit jako samostatnou komponentu dokumentu, jak praktikují některá řešení tzv. elektronických podatelen, 
* povinnost automaticky zpracovat XML v doručeném dokumentu/kontejneru PDF/A (evidenční údaje, údaje o osobách), 
* zcela byla vypuštěna ustanovení o šifrování a skenování, která nelze plně zajišťovat prostřednictvím eSSL, 
* upřesňuje se, které entity musí mít v rámci eSSL jednoznačný identifikátor, 
* je zavedena nová koncepce tvorby čísla jednacího: eSSL má vždy údaje, ze kterých lze poskládat číslo jednací dokumentu oběma dřívějšími způsoby (spojování/sběrný arch), které byly mylně uváděny jako způsob tvorby spisu. Dokument tedy obdrží pořadové číslo průběžné řady v rámci stanoveného časového období (roku) i pořadové číslo dokumentu ve spisu. Zkratky[2] používané v čísle jednacím musí být obsaženy v číselníku, který lze importovat/exportovat, 
* na konkrétní věcnou skupinu lze nastavit různý způsob přidělování čísla jednacího: podle pořadového čísla v rámci určeného časového období nebo dle spisové značky s pořadovým číslem dokumentu ve spisu. 


## Jmenný rejstřík a jeho vazby


* Nově jsou stanoveny požadavky na jmenný rejstřík
* povinnost vazby záznamu ve jmenném rejstříku na doručený nebo odesílaný dokument, 
* zpracování XML z doručeného dokumentu/kontejneru v PDF/A do jmenného rejstříku, 
* ztotožnění osoby v záznamu ve jmenném rejstříku v autoritativních zdrojích dat (základní registry a ISDS), 
* eSSL musí umět přijímat notifikace z informačního systému základních registrů i automatickou kontrolu oproti základním registrům při odesílání a příjmu dokumentu, - eSSL musí umožnit uživateli konsolidaci („čištění“) záznamů ve jmenném rejstříku, zejména spojování záznamů o téže osobě. 

## Samostatné evidence a evidování mimo ESSL

* V případě samostatných evidencí dokumentů, které zavádí vyhláška, jsou dvě možnosti (neatestovaného) řešení: 
	*propojení s eSSL pomocí rozhraní, nebo 
	* splnění vybraných ustanovení NSESSS. Kapitola 2.9 v tomto případě obsahuje především odkazy na ostatní kapitoly a požadavky NSESSS. 

## Spisy a třídění dokumentů


* Cílem změny u věcných skupin a spisového a skartačního plánu bylo odstranit každoroční úpravy věcných skupin v rámci spisového plánu, kdy reálně dochází ke změnám u zlomku věcných skupin. Proto je nyní spisový a skartační plán časovým řezem věcných skupin (těch platných v daném období) a dochází k odstranění nežádoucího nahrazování nadále platných věcných skupin. Také úprava pouze textového popisu věcné skupiny bez současné změny spisového znaku nebo skartačního režimu, nebude znamenat vznik nové věcné skupiny. Nově bude také možné, ovšem pouze pro posuzovatele skartační operace, přetřídit uzavřené spisy do jiné věcné skupiny, a to i do uzavřené[4]. 
* Spisy jsou zakládány ve věcné skupině nebo v dílu typového spisu[5] buď na základě dokumentu, nebo i bez dokumentu. Právě proto je ve spisu eSSL automaticky přiřazován spisový znak a další metadata – to už nelze řešit dodatečně, až při uzavření spisu. 
* Do spisu může vložit dokument jakákoli uživatelská role, která má k vložení právo (nikoli tedy pouze „držitel“ spisu). 
* Dokument přebírá spisový znak i skartační režim vždy ze spisu  (i po přetřídění z jiného spisu), skartační režim ale může být ovlivněn stanovením druhu dokumentu (vznikne konflikt skartačních režimů – viz dále). 
* Předpokládá se (umožňuje se) dále: 
	*možnost označit za vyřízené jednotlivé dokumenty ve spisu, 
	* možnost otevřít již uzavřený spis, 
	*povinnost přetřídit neuzavřené spisy z věcné skupiny, která se uzavírá[6]. 
* Typové spisy jsou zakládány na základě tzv. šablony typového spisu (struktury součástí) v příslušné věcné skupině obsahující typové spisy. Na rozdíl od předchozích úprav, součásti v typovém spisu mohou být uspořádány hierarchicky podobně, jako jsou hierarchické věcné skupiny; skartační režim má pouze nejnižší součást, v níž jsou teprve vytvářeny díly. 
* Nově je v souvislosti s případným importem řešeno přetřídění typového spisu a změna šablony typového spisu – mapování původní struktury na novou. 
* Již nelze používat maximální velikost obsahu jako parametr pro uzavření dílu, nadále se předpokládá pouze chronologické hledisko. 
* Radikálně byla omezena možnost vytvářet pevné křížové odkazy. Nyní je možné pevné křížové odkazy vytvořit pouze mezi spisy, přičemž při vložení takto spojených spisů do dílu typového spisu dojde k odstranění pevných křížových odkazů. 
* V případě druhů dokumentů byl doplněn skartační režim (jeho absence v předcházejících podobách standardu byla zjevnou chybou). Druh dokumentu tak může sloužit k vyvolání konfliktu skartačních režimů a jejich následnému řešení. Jestliže například označíme dokumenty, vztahující se k evropským strukturálním fondům, druhem „dokumenty operačního programu XY“ se spouštěcí událostí „po rozhodnutí Evropské komise“, zajistíme, že celý spis – bez ohledu na to, v jaké bude věcné skupině – nebude možné vyřadit, dokud neuplyne skartační lhůta, jejíž počátek běhu je zmíněná spouštěcí událost. Kapitoly týkající se vyhledávání, znázornění a ztvárnění byly formulovány srozumitelněji. Nadále již nebude možné opatřovat ztvárnění transakčního protokolu uznávaným elektronickým podpisem, ale pouze uznávanou elektronickou pečetí. 
* V souvislosti se zrušením skartačního znaku „V“ dochází k úpravám v ukládání a vyřazování dokumentů, ale tak, aby nebylo potřeba upravovat metadata již uzavřených a uložených spisů a vyřízených dokumentů. V těchto případech je možné ponechat i vyřízené dokumenty mimo spisy. 
* Nová je úprava spouštěcích událostí, kdy jsou některé v NSESSS přímo stanoveny navíc nad zákonem definovaného uzavření spisu. Jsou to 
	*rok vyřízení spisu, 
	*rok uzavření spisu, typového spisu, součásti typového spisu nebo dílu typového spisu, 
	*rok založení spisu totožný s rokem jeho evidence a 
	*rok narození nebo vzniku subjektu. 
* V případě těchto spouštěcích událostí lze celý skartační režim aplikovat automaticky. Pokud nelze okamžik vzniku spouštěcí události předem definovat (např. „po skončení platnosti smlouvy“), bude posuzovatel skartační operace[7] tázán po uplynutí počtu let stanovených jako skartační lhůta, zda už spouštěcí událost nastala nebo může zaznamenat rok, kdy nastane. Pokud spouštěcí událost nenastala a ani nebyl zaznamenán rok, kdy nastane, dotaz bude opakován po dalším uplynutí doby uvedené jako skartační lhůta. 
* Pokud jde o konflikty skartačních režimů, jejich řešení se předpokládá automatické, zejména aplikací nejzávažnějšího skartačního režimu: pokud je u některé entity skartační znak „A“, bude u všech dalších entit, které jsou se zmíněnou entitou v konfliktu skartačního režimu, také skartační znak A. Obdobné platí i o skartační lhůtě, která se aplikuje nejdelší. 
* Závažnější skartační režim se však neuplatní při přetřídění spisu mezi věcnými skupinami – v takovém případě převezme spis skartační režim věcné skupiny, do které byl přetříděn. 
* Samotné skartační řízení zůstává bez podstatných změn.  
* Je zcela zásadně přepracován přenos, export a také import, který v předchozí verzi NSESSS reálně neexistoval. Nové schéma XML zahrnuje daleko komplexnější metadata a NSESSS také vyžaduje exportovat současně všechny nadřazené, podřazené a pevným křížovým odkazem připojené entity. 

## Další zejména technické změny


* Požadavky na zálohu a obnovu nebo spolupráci s antivirovými programy byly vypuštěny, protože nejde o funkčnost samotného eSSL. Popis práce se správcovskými a uživatelskými rolemi byl pouze zpřesněn a jednoznačněji formulován, stejně jako požadavky na hlášení o stavu eSSL.  
* V případě změn, zničení a znepřístupnění dokumentů byl kladen důraz na situaci, kdy byl udělen trvalý skartační souhlas na konkrétní věcné skupiny. Fakticky poprvé je upraveno storno dokumentu, popř. spisu, tedy jeho znepřístupnění. Stornovat dokument nebo spis může pouze uživatel, který dokument vytvořil a nepředal držení tohoto dokumentu nebo spisu jinému uživateli. V případě dokumentů nezařazených do spisů nebo spisů neobsahující dokumenty může tyto stornovat správcovská role. Také je možné stornovat dokument, u kterého byla při příjmu vyhodnocena vadná komponenta. Zničení znepřístupněného dokumentu je delegováno na posuzovatele skartační operace (nikdo jiný ho nemůže provést) stejně jako v případě uděleného trvalého skartačního souhlasu. 
* V případě transakčního protokolu musí eSSL kromě požadavků na automatické ztvárnění jeho nejvýše denního obsahu umožnit správcovské roli export v XML ve stanoveném časovém rozsahu. Do transakčního protokolu musí být zapsány veškeré prováděné operace, z čehož vyplývá vypuštění některých starších požadavků. Naopak jsou na jedno místo soustředěny požadavky, které specifikují konkrétní metadata, jejichž změny se také musí do transakčního protokolu promítnout.  
* V případě rozhraní mezi informačními systémy došlo k dílčím úpravám zejména webových služeb – např. pro práci s typovým spisem. 
* Obecný popis požadavků na metadata a strukturu balíčků SIP se téměř nezměnil, ale z dokumentace životního cyklu eSSL zůstal pouze evidenční list s mírně upraveným obsahem, který se ale nově vztahuje nejen na eSSL, ale na všechny informační systémy spravující dokumenty. 
* Přílohy NSESSS byly rozšířeny za účelem exportu a importu dat, bylo doplněno schéma pro strukturovaný záznam evidenčních údajů v odesílaném dokumentu, který předjímá již vyhláška[8]. Nově byla doplněna příloha s přehledem metadat entit s informacemi, kdy, který údaj vzniká. Původní přílohy č. 2 a 3 byly sloučeny a nově tvoří jedinou přílohu č. 2. 

