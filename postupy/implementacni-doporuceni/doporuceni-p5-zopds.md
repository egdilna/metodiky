---
layout: default
title: Návrh implementace § 5 ZoPDS Právo na osvědčení o digitálním úkonu a souvisejících povinností
parent: Implementační doporučení ZoPDS
nav_order: 5
last_modified_date: 2023-10-16
grand_parent: Postupy
---
Toto je dokument Digitální a informační agentury zpracováný v rámci [Implementace povinností dle zákona o právu na digitální služby](https://archi.gov.cz/znalostni_baze:implementace_zopds?s[]=implementace%2A&s[]=z%C3%A1kona%2A&s[]=o%2A&s[]=pr%C3%A1vu%2A&s[]=na%2A&s[]=digit%C3%A1ln%C3%AD%2A)



### Obecná zákonná východiska

ZoPDS v případě osvědčení digitálního úkonů rozlišuje mezi dvěma
subjekty, které osvědčení vystavují:

1.  OVM, který je veřejnoprávním původcem. Ten je povinen osvědčení
    vystavit bezodkladně po učinění digitálního úkonu, tedy nikoliv na
    žádost.

2.  OVM, který není veřejnoprávním původcem. Ten vystavuje osvědčení až
    na základě žádosti, ale nic mu nebrání vystavit osvědčení
    bezodkladně.

Povinnost vystavit osvědčení bezodkladně po učinění digitální úkonu je
však třeba vykládat ve spojení s odstavcem 4 tohoto ustanovení, který
předpokládá uživatelovu volbu kanálu, kterým mu bude osvědčení
poskytnuto. Pokud bude OVM volbu uživatele znát, pak je situace
relativně snadná, a OVM poskytne osvědčení tímto kanálem. Nebude-li však
tato volba vůči OVM učiněna, pak lze k této situaci přistupovat dvěma
způsoby:

1.  OVM poskytne osvědčení bezodkladně prostřednictvím kanálu, kterým
    byl digitální úkon učiněn. Osvědčení prostřednictvím jiného kanálu
    OVM poskytne pouze v případě žádosti uživatele s uvedením kanálu v
    žádosti.

OVM neudělá chybu, pokud poskytne osvědčení vždy do datové schránky
klienta -- zde je potřeba vědět, v jaké roli klient vystupuje a podle
toho vybrat správnou datovou schránku[^1].

2.  Dokud nebude OVM znát uživatelovu volbu, nemůže osvědčení
    poskytnout. Povinnost poskytnout osvědčení bezodkladně bude OVM
    svědčit pouze v případě, že mu uživatel svou volbu kanálu sdělí,
    resp. od okamžiku, kdy uživatel OVM svou volbu sdělí.

V této souvislosti je nutné podotknout, že duplicitně k osvědčení dle
ZoPDS se vydávají další potvrzení, která osvědčení dle ZoPDS svou formou
připomínají a uživateli mohou sloužit k naplnění stejné funkce, tedy
zajištění potvrzení o doručení a důkazu o této skutečnosti. Jde o
potvrzení o doručení:

1)  v případě úkonu učiněného datovou schránkou jde o oznámení podle §
    20 odst. 1 zákona č. 300/2008 Sb.

2)  v případě úkonu emailem jde o potvrzení o doručení dokumentu na
    elektronickou adresu podatelny dle § 4 odst. 8 Vyhlášky č. 259/2012
    Sb., o podrobnostech výkonu spisové služby.

### Kanál doručení osvědčení

Volba doručovacího kanálu by měla náležet uživateli (v limitech
předchozího bodu). Základním smyslem a účelem osvědčení je poskytnout
uživateli dokument, který může sloužit jako důkaz o provedení úkonu, a
to ideálně bezodkladně po jeho provedení. Jako vhodné řešení se tedy
nabízí poskytnout uživateli osvědčení tím stejným kanálem, kterým učinil
úkon, protože uživatel si zvolil pro sebe nejvhodnější kanál komunikace,
a dá se očekávat, že chce tím stejným kanálem obdržet rovněž vyrozumění
o provedení úkonu -- tedy osvědčení.

Uživatel může dle § 4 ZoPDS provést digitální úkon až 5 různými kanály
(pomíjíme zde ve vazbě na výklad k § 4 možnost neimplementovat kanál
tzv. samoobslužného portálu, pokud tuto možnost pokládá orgán veřejné
moci za nehospodárnou):

1.  datovou schránkou,

2.  kontaktním místem veřejné správy,

3.  e-mailem, resp. dokumentem podepsaným uznávaným elektronickým
    podpisem,

4.  samoobslužným portálem,

5.  jiným způsobem stanovený právním přepisem.

Stejným způsobem, kterým uživatel učinil úkon, se uživateli doručí
osvědčení. Toto pravidlo má několik výjimek potvrzující pravidlo:

1.  Při učinění úkonu pomocí e-mailu se uživateli osvědčení doručí i do
    datové schránky (pokud ji uživatel má zpřístupněnou) pro zajištění
    nepopiratelnosti doručení.

2.  Při učinění úkonu na kontaktním místě veřejné správy se osvědčení
    vystavuje přímo na kontaktním místě.

![](media/image1.png){width="6.052083333333333in"
height="2.1753630796150483in"}

Máme za to, že při dodržení výše uvedeného schématu se dostojí účelu §
5. Je však třeba připustit určité limity navrhovaného řešení:

1.  Pro poskytnutí osvědčení tento návrh připouští také jako kanál
    doručení přímo samoobslužný portál. Tento kanál však v odst. 4. není
    výslovně zmíněn, jelikož v této souvislosti směřuje pouze na
    poskytnutí osvědčení prostřednictvím portálu veřejné správy.
    Domníváme se nicméně, že bude-li osvědčení vystaveno po učinění
    digitální úkonu přímo na konkrétním samoobslužném portálu OVM, bude
    tím naplněn smysl osvědčení.

2.  Stále by mělo být zachováno uživatelovo právo žádat o vystavení
    osvědčení na jiném kanále, než kterým byl učiněn úkon. Za současného
    stavu je však problematické zejména poskytnutí osvědčení
    prostřednictvím kontaktního místa veřejné správy.

Avšak i v rámci výkladu k § 4 opětovně odkazujeme na povinnost péče
řádného hospodáře, použití svěřených prostředků hospodárně, účelně a
efektivně či plnění určených úkolů tím nejhospodárnějším způsobem dle §
45 odst. 2 zákona č. 218/2000 Sb. o rozpočtových pravidlech. Námi
nastíněným postupem se podle našeho názoru dostojí smyslu vystavování
osvědčení za použití minimálních nákladů na straně veřejné správy.

### Zveřejnění formuláře ve vztahu k osvědčení

Ustanovení § 4 odst. 3 umožňuje zveřejnit prostřednictvím Agentury
elektronické formuláře. Formát, strukturu a obsah formuláře stanoví
orgán veřejné moci zveřejněním. Nezveřejní-li orgán veřejné moci
elektronický formulář, má uživatel služby právo učinit digitální úkon
podle své volby v jakémkoli výstupním datovém formátu podle zákona
upravujícího archivnictví a spisovou službu.

Vzhledem k možnosti, že některá současná podání a formuláře nemusí
dostatečně zajišťovat identifikaci uživatele, úkonu či dalších
náležitostí, které má následně obsahovat osvědčení, je nutné zveřejnit
formuláře, resp. upravit jejich obsah tak, aby mohlo být bezodkladně po
provedení úkonu tímto formulářem vystaveno osvědčení.

### Co osvědčení osvědčuje

Osvědčení potvrzuje neodmítnutí příjmu, neodmítnutí původu, integritu
dat a důvěryhodnost. Nejde tedy o důkaz, že úkon byl proveden řádně
s veškerými zákonnými náležitostmi, ale pouze to, že byl v nějaké formě
proveden.

Při absenci podání prostřednictvím elektronického formuláře může být
problematické vydávat osvědčení dle § 5 ZoPDS, protože nestrukturovanost
a povaha úkonu činěná v konkrétní službě nemusí na první pohled vypadat
jako úkon spadající pod ZoPDS. S odkazem na vysvětlení k § 4 pak
uvádíme, že veškeré kanály (včetně samoobslužného portálu s
elektronickým formulářem) dle tohoto paragrafu jsou povinné, pokud není
prokázána nehospodárnost.

OVM také nemůže rezignovat na povinnost vydávat osvědčení pro digitální
úkony, které nejsou obsaženy v katalogu služeb. Důvodem je, že přechodné
ustanovení § 14 odst. 5 ZoPDS stanoví, že existuje-li úkon, který není
obsažen v katalogu služeb a jehož povaha to nevylučuje, příslušný orgán
veřejné moci jej po uplynutí 5 let od účinnosti tohoto zákona (tedy
od 1. 2. 2025) poskytuje též jako digitální službu nebo jej umožňuje
provádět též jako digitální úkon, **nestanoví-li jiný zákon jinak**.

OVM se tedy nemůže zprostit povinnosti vydávat osvědčení ani u těch
úkonů, které nebudou poskytovány prostřednictvím elektronického
formuláře a bude možné u nich očekávat nestrukturované a před jejich
zpracování těchto zařaditelné žádosti. Tuto povinnost tak nebude OVM mít
pouze v případě, že agendový zákon nestanoví, že určitý úkon nebude
poskytovaný jako digitální služba (viz předchozí odstavec).

### Jaké má osvědčení náležitosti

Zákon podobu osvědčení nestanoví, ale stanovuje jeho náležitosti:

1.  Důvěryhodné zachycení obsahu digitálního úkonu nebo jinou
    identifikaci digitálního úkonu,

2.  Určení osoby, která digitální úkon učinila. Touto osobou je
    nejčastěji ta osoba, která digitální skutečně činí. Tedy
    zjednodušeně ta osoba, která podání podepsala či jí svědčí fikce
    podpisu. Mohou však nastat situace, kdy bude například činěno podání
    prostřednictvím elektronicky podepsaného dokumentu (či
    konvertovaného dokumentu) datovou schránkou osoby odlišné o té,
    která dokument podepsala a která digitální úkon skutečně činí (v
    tomto případě neplatí fikce podpisu a dokument tedy musí být
    podepsaný uznávaným elektronickým podpisem). **Jelikož by však
    kontrola každého dokumentu a zjišťování toho, kdo podání skutečně
    činí, vyžadovalo velké množství manuální práce, je akceptovatelné v
    osvědčení identifikovat tu osobu, jejíž datovou schránkou je podání
    činěno**, ačkoliv tato osoba nemusí být vždy shodná s účastníkem
    řízení. Jedná se o stejnou situaci jako v papírovém světě, kdy je
    například na podatelně razítkem a datem potvrzeno podání osobě,
    která jej pouze doručuje na podatelnu, ale není samotným podatelem
    podání.

3.  Adresát digitálního úkonu.

4.  Způsob, datum a čas provedení digitálního úkonu.

Dále je potřeba dodržet zákonné požadavky vztahující se k zacházení s
dokumentem, který vytváří OVM a slouží pro třetí stranu, v tomto případě
uživatel služby:

1.  Osvědčení musí být opatřeno kvalifikovanou elektronickou pečetí.

2.  Osvědčení musí být opatřeno kvalifikovaným elektronickým časovým
    razítkem.

Aby se s osvědčením dalo pracovat v jeho textově vizuální podobě, musí
mít formát typu PDF/A-3 a pro strojové zpracování obsahovat XML soubor.
Samozřejmě informace v obou formátech si musí odpovídat, za což je OVM
zodpovědný.

### Doba uložení/poskytování osvědčení

ZoPDS ve své konečné podobě dobu uložení ani zpětného poskytnutí nijak
neupravuje (v prvních návrzích legislativního procesu tuto dobu
upravoval). Pokud je tedy osvědčení vystaveno, ať už bezodkladně nebo
později (vytvoří se existující dokument), uplatní se na něj pravidla a
povinnosti dle spisového řádu dané organizace včetně navazujících
skartačních lhůt dle § 64 a § 66 zákona č. 499/2004 Sb. o archivnictví a
spisové službě.

Osvědčení tedy nelze ihned po vystavení „zapomenout".

### Příklady realizace osvědčení

Realizace osvědčení je jako příklad uvedena zde
<https://archi.gov.cz/znalostni_baze:osvedceni#priklad_osvedceni>

Konkrétní realizace z Magistrátu hl. města Prahy vypadá následovně:

![](media/image2.emf){width="6.3in" height="8.632639982502187in"}

