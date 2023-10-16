---
layout: default
title: Návrh implementace § 4 ZoPDS Právo činit digitální úkon a souvisejících povinností
parent: Implementační doporučení ZoPDS
nav_order: 4
---
Toto je dokument Digitální a informační agentury zpracováný v rámci [Implementace povinností dle zákona o právu na digitální služby](https://archi.gov.cz/znalostni_baze:implementace_zopds?s[]=implementace%2A&s[]=z%C3%A1kona%2A&s[]=o%2A&s[]=pr%C3%A1vu%2A&s[]=na%2A&s[]=digit%C3%A1ln%C3%AD%2A)


(1) *Uživatel služby má právo činit digitální úkon vůči orgánu veřejné
    moci prostřednictvím*

    a.  *své datové schránky,*

    b.  *kontaktního místa veřejné správy v případě digitálního úkonu, o
        kterém tak stanoví prováděcí právní předpis,*

    c.  *sítě elektronických komunikací dokumentem podepsaným uznávaným
        elektronickým podpisem nebo opatřeným uznávanou elektronickou
        pečetí za podmínek stanovených jinými zákony,*

    d.  *informačního systému veřejné správy umožňujícího prokázání
        totožnosti uživatele služby s využitím elektronické
        identifikace, autorizaci digitálního úkonu uživatelem služby a
        zpětné prokázání projevu vůle uživatele služby učinit digitální
        úkon, nebo*

    e.  *jiného způsobu, pokud tak stanoví právní předpis.*

(2) *Nestanoví-li zákon výslovně závaznou podobu úkonu vůči orgánu
    veřejné moci, má uživatel služby právo činit úkon jako digitální
    úkon.*

(3) *Orgány veřejné moci zveřejňují prostřednictvím Agentury
    elektronické formuláře, které po prokázání totožnosti uživatele
    služby s využitím elektronické identifikace zajistí automatizované
    doplnění údajů nezbytných pro poskytnutí digitální služby vedených v
    základním registru nebo agendovém informačním systému, které jsou
    orgánu veřejné moci zpřístupněné pro výkon agendy, nebo využívaných
    orgánem veřejné moci na základě souhlasu uživatele služby. Formát,
    strukturu a obsah formuláře stanoví orgán veřejné moci zveřejněním.
    Nezveřejní-li orgán veřejné moci elektronický formulář, má uživatel
    služby právo učinit digitální úkon podle své volby v jakémkoli
    výstupním datovém formátu podle zákona upravujícího archivnictví a
    spisovou službu.*

# Předpoklady a souvislosti návrhu

Tento dokument vychází z následujících předpokladů:

1.  Digitální a informační agentura (dále jen „DIA") připravila tento
    dokument na základě vlastních zkušeností a diskuzí vedených v rámci
    meziresortní pracovní skupiny organizované DIA k výkladu zákona
    12/2020 Sb., o právu na digitální služby (dále jen „ZoPDS").

2.  DIA není orgánem příslušným k poskytnutí závazného výkladu ZoPDS.
    Dokument tak přináší výhradně návrh řešení.

3.  Dokument prezentuje návrh pro první etapu implementace ustanovení
    ZoPDS, který z pohledu některých orgánů veřejné moci (dále jen
    „OVM") nemusí zcela bez dalšího naplňovat znění ZoPDS. Jde však o
    návrh řešení, který se za současného stavu relevantních právních
    předpisů a technických řešení jeví jako nejpřívětivější pro
    uživatele a jako jednoduché, účelné, efektivní a hospodárné z
    pohledu technického řešení pro OVM.

4.  Je na odpovědnosti každého jednotlivému OVM, jaké řešení pro
    implementaci tohoto ustanovení zvolí, tedy zda bude v rámci první
    etapy implementace tohoto ustanovení následovat dále prezentovaný
    návrh řešení a následně hledat řešení, které bude z jeho pohledu
    vhodnější, anebo pro implementaci zvolí zcela jiné řešení.

5.  Pokud s některým z dále prezentovaným závěrem nesouhlasil některý
    z členů meziresortní pracovní skupiny k výkladu ZoPDS, byl mu dán
    prostor v tomto dokumentu svůj odlišný závěr uvést.

# Obslužné kanály pro podání -- učinění úkonu

Zákon definuje celkem 5 možných způsobů učinění úkonu. Jelikož jde o
právo subjektu, není možné jej splnit aplikováním pouze jednoho kanálu,
ale uživateli se musí dát možnost, aby ze všech těchto kanálů zvolil
ten, který mu nejvíce vyhovuje.

Výše zmíněné má následující omezující podmínky:

1)  Kanál kontaktního místa veřejné správy je umožněn pouze v případě,
    že tak stanoví prováděcí právní předpis, kterým má být dle § 14
    odst. 7 ZoPDS nařízení vlády. Zde je zásadní rozpor s § 8a odst. 1
    zákona č. 365/2000 Sb. o informačních systémech veřejné správy,
    který stanovuje, že podání prostřednictvím kontaktních míst veřejné
    správy lze činit pouze v rozsahu stanoveném jinými právními
    předpisy.

2)  Kanál informačního systému veřejné správy umožňující elektronické
    prokázání totožnosti (neboli portál) je povinným kanálem, avšak u
    těch úkonů, u kterých se prokáže daná investice z pohledu účelnosti,
    účinnosti a efektivnosti (3E) jako nehospodárná (srov. Příručka
    plánování digitalizace služeb veřejné správy ČR, dostupná z
    <https://archi.gov.cz/_media/dokumenty:prirucka_pro_planovani_digitalizace_-_final_v1.pdf>)
    je možné zvážit, zda tento kanál implementovat.

3)  Úkon nelze digitalizovat, pokud jiný právní předpis stanoví odlišné
    postupy, pravidla a povinnosti.

4)  Úkon ze své povahy a podstaty nelze digitalizovat (například žádost
    o identifikační doklad, kde je potřeba biometrika)

5)  Jiný způsob dle posledního písmene může v konkrétním zákoně stanovit
    i jiné procesy a postupy, proto je vždy nutné hledět na speciální
    právní úpravu. (Například daňový řád a daňová informační schránka §
    69 zákona č. 280/2009 Sb. daňový řád)

Bod 2 by neměl být pro orgány veřejné moci překvapivým, jde o požadavek
na péči řádného hospodáře a dbaní hospodaření se státním rozpočtem tím
nejhospodárnějším způsobem viz § 45 odst. 2 zákona č. 218/2000 Sb. o
rozpočtových pravidlech. Přesto se uvažování nesmí směřovat na to, zda
se bude samoobslužný portál budovat či nikoliv. Je nutné uvažovat vždy
nad souborem služeb a úkonů celého úřadu a ne nad jednou konkrétní
službou. Každý úřad by měl mít svůj samoobslužný portál a rozhodování je
tedy pouze o tom, zda se vyplatí digitalizovat konkrétní službu a na
portál ji umístit.

## Posuzování hospodárnosti při zpřístupnění ISVS pro digitální úkon

OVM mají obecnou povinnost nakládat se svěřenými prostředky hospodárně,
efektivně a účelně. Hospodárností je takové použití veřejných prostředků
k zajištění stanovených úkolů s co nejnižším vynaložením těchto
prostředků, a to při dodržení odpovídající kvality plněných úkolů. Při
dodržení zásady efektivnosti má být dosaženo co nejvyššího možného
rozsahu, kvality a přínosu plněných úkolů ve srovnání s objemem
prostředků vynaložených na jejich plnění. Účelností je takové použití
veřejných prostředků, které zajistí optimální míru dosažení cílů při
plnění stanovených úkolů.

ZoPDS v § 13 zakotvuje právo uživatele na technologickou neutralitu. V
souladu s ním má OVM zpřístupnit digitální službu uživateli služby bez
závislosti na konkrétní platformě či technologii, ledaže by takové
řešení bylo (mimo jiné) nepřiměřeně ekonomicky náročné.

Uvedené pravidlo by bylo možné analogicky aplikovat na zpřístupnění
všech kanálů pro přístup k digitální službě dle § 4 odst. 1 ZoPDS.
Zásada technologické neutrality se v tomto ustanovení projevuje mnohostí
platforem, které uživateli zprostředkují podání digitálního úkonu vůči
OVM. Touto platformou může být:

a)  datová schránka,

b)  kontaktní místo veřejné správy,

c)  e-mail, resp. dokument předaný prostřednictvím sítě elektronických
    komunikací a podepsaný uznávaným elektronickým podpisem nebo
    opatřeným uznávanou elektronickou pečetí,

d)  informační systém veřejné správy splňující podmínky dle § 4 odst. 1
    písm. d) ZoPDS,

e)  jiný způsob stanovený právním přepisem.

Povinnost přijímat podání přes datovou schránku, kontaktní místo veřejné
správy, elektronickou podatelnou či jiným zákonem stanoveným způsobem
vyplývá již z jiných právních předpisů a OVM jejich prostřednictvím
podání přijímaly a přijímají bez ohledu na ZoPDS. Pokud však OVM dosud
nepředepisoval jiný právní předpis povinnost zřídit pro určitá podání
speciální informační systém veřejné správy ve smyslu § 4 odst. 1 písm.
d) ZoPDS či OVM takový informační systém nezřídil dobrovolně, vyžaduje
vybudování takového informačního systému dodatečné náklady na straně
OVM. Lze si představit digitální služby, které uživatelé využijí v
jednotkách případů ročně a zároveň ani není jisté, zda by pro tento úkon
vůbec informační systém využili. V takovém případě se může ukázat
vybudování informační systému neefektivní, nehospodárné a neúčelné,
resp. nepřiměřeně ekonomicky náročné ve smyslu § 13 odst. 1 ZoPDS.

Ve výše naznačeném směru může směřovat úvaha OVM ohledně zpřístupnění
informačního systému dle § 4 odst. 1 písm. d) ZoPDS pro některé méně
využívané digitální služby. DIA nemůže za OVM učinit závěr ohledně
konkrétní digitální služby. Uvedené konstatování také neznamená, že by
DIA vůči OVM komunikovala závěr, že nemají povinnost tento informační
systém zpřístupnit. Stejně tak je nutné konstatovat, že soud či jiný
příslušný orgán může ve vztahu k porušení uživatelova práva činit
digitální úkon prostřednictvím informačního systému konstatovat odlišný
závěr.

Je možné se zaobírat také náklady vznikající na straně uživatele.
Uživatel, který je nucen využít jen konkrétní kanály může mít zvýšené
náklady na využití služby. Pokud je tedy například uživateli upřen kanál
samoobslužného portálu, může to u žadatele vyvolat potřebu vlastnit
uznávaný elektronický podpis či datovou schránku. Jelikož však jsou tyto
náklady velmi špatně vyčíslitelné, dáváme je spíše jako inspiraci,
kterou je také možné použít.

# Samoobslužný portál

Portál je vnímán jako celý funkční celek obsahující Front-end (logika
zobrazující chování směrem ke klientovi) i Back-end (logika realizující
chování systému a vnitřní i vnější integraci) realizující všechny typy
služeb dle [Informační koncepce ČR](https://archi.gov.cz/ikcr) -
Informační, Interaktivní a Transakční. Z tohoto mimo jiné vyplývá, že
portál je informačním systémem veřejné správy.

-   V oblasti informačních služeb poskytuje uživatelům přehled a veřejně
    dostupné informace z oblasti, kterou portál obsahuje včetně popisu
    životních situací.

    -   V informační části není potřeba řešit identifikaci, autentizaci
        a autorizaci uživatele.

-   V oblasti interakčních služeb poskytuje uživatelům personifikované
    údaje s využitím vícero informačních kanálů, zpětnou vazbu mezi jeho
    konáním, a to včetně historie.

    -   Interakční služby vyžadují identifikaci, autentizaci a
        autorizaci uživatele.

-   V oblasti transakčních služeb poskytuje uživatelům podání všech
    typů, včetně provedení platby nebo rezervace termínu pro prezenční
    jednání, získání potvrzení a doručení rozhodnutí úřadu.

    -   Transakční služby vyžadují identifikaci, autentizaci a
        autorizaci uživatele.

Portály tedy nemohou být samostatné a nepropojené aplikace, ale naopak
musí se jednat o prostředek, který je integrován s informačními systémy
v úřadu. Především s elektronickou spisovou službou (nebo samostatnou
evidencí dokumentů), s agendovými informačními systémy, ale třeba i s
ekonomickými systémy tam, kde se jejich prostřednictvím shromažďují
údaje o výplatách či o poplatcích podle jednotlivých klientů. V případě
poskytování všech 3 typů služeb se jedná o tzv. integrované on-line
služby veřejné správy dle [Informační koncepce
ČR](https://archi.gov.cz/ikcr).

Portál má sloužit klientovi k získání informací, jako prostředek pro
publikování otevřených dat, statistik a veřejných výstupů, pro činění
úkonů elektronickým formulářem a komunikaci klienta s úřadem.

Takový portál se vyznačuje vlastnostmi, z nichž některé jsou povinné a
některé doporučující. Mezi povinné patří:

-   Musí být registrovaný jako informační systém veřejné správy
    v [rejstříku informačních systémů veřejné
    správy](https://rpp-ais.egon.gov.cz/AISP/verejne)

-   Spravuje ho orgán veřejné správy, který vykonává jednu nebo více
    agend dle [seznamu agend veřejné
    správy](https://rpp-ais.egon.gov.cz/gen/agendy-detail/)

-   Musí být součástí federace národního identitního schématu, tedy
    využívat služby [Národní identitní
    autority](https://archi.gov.cz/nap:nia) a jeho správce musí
    být [ohlášen jako kvalifikovaný poskytovatel
    služeb](https://archi.gov.cz/nap:nia#pravidla_pro_narodni_identitni_autoritu)

-   Musí k identifikovanému a autentizovanému uživateli být schopen
    propojit údaje své agendy a údaje z [propojeného datového
    fondu](https://archi.gov.cz/nap:propojeny_datovy_fond) a [veřejného
    datového fondu](https://archi.gov.cz/nap:verejny_datovy_fond)

-   Musí využívat datovou základnu [katalogu služeb a životních
    situací](https://archi.gov.cz/nap:katalog_sluzeb), jaká je
    v [RPP](https://archi.gov.cz/nap:rpp)

-   Musí být v souladu s [grafickým
    manuálem](https://designsystem.gov.cz/)

-   Musí poskytovat autorizaci úkonu s [využitím služeb
    NIA](https://dev.azure.com/SpravaZakladnichRegistru/NIA%20pro%20v%C3%BDvoj%C3%A1%C5%99e/_wiki/wikis/NIA-pro-v%C3%BDvoj%C3%A1%C5%99e.wiki/67/Autorizace-digit%C3%A1ln%C3%ADho-%C3%BAkonu)
    pro zpětné prokázání vůle

-   Musí umožnit učinit podání (učinit úkon) ke službě z [katalogu
    služeb VS](https://archi.gov.cz/nap:katalog_sluzeb) pomocí
    následujících kanálů:

    -   [Informační systém datových
        schránek](https://archi.gov.cz/nap:elektronicke_ukony_a_dorucovani).
        Zde se jedná o umožnění podání pomocí ISDS na konci celého
        podacího procesu. Jde tedy o to klientovi umožnit využít i tento
        kanál. Správce portálu je zodpovědný za to, aby podání takovýmto
        způsobem nijak nenarušilo automatizovatelnost celého procesu,
        tedy aby výsledek, který bude uživatel pomocí ISDS posílat
        obsahoval jak vizuální podobu (PDF), tak i strojově čitelnou
        podobu (XML) v jenom neměnném kontejneru.

    -   Přímého podání na portále identifikovaným a autentizovaným
        uživatelem pomocí [NIA](https://archi.gov.cz/nap:nia)

    -   Elektronicky podepsaným dokumentem ve formě uznávaného podpisu

-   Musí umožňovat tzv. fikci podpisu u podání dle § 8 zákona č.
    365/2000 Sb.

-   Pokud portál přímo čerpá nebo poskytuje služby informačním systémům
    veřejné správy jiných správců, je toto propojení realizováno
    výhradně prostřednictvím
    služeb [KIVS/CMS](https://archi.gov.cz/nap:komunikacni_infrastruktura_verejne_spravy).

Mezi doporučující patří:

-   Být schopen poskytnout identifikovanému a autentizovanému uživateli
    možnost
    udělit [mandát/oprávnění](https://archi.gov.cz/nap:elektronicka_identifikace_pro_klienty_verejne_spravy) k zastupování
    pro jednotlivé služby, propsat do mandátního registru a nastavené
    mandáty zobrazovat, přijímat a rušit.

-   Být součástí federace portálů veřejné správy a poskytovat informace
    a služby do centrálních (federujících) portálů jako je
    např. [Portálu občana](https://archi.gov.cz/nap:portal_obcana)

-   Být schopen poskytnout náhled na jednotlivá podání vůči úkonům a
    služeb identifikovanému a autentizovanému uživateli a to jak tomu,
    který podání učinil, tak tomu, který je k tomu zmocněn

-   Být schopen poskytnout úhradu poplatku pomocí platební brány

-   Veškeré funkcionality, které se vyvinuly na míru, jsou poskytnuty
    jako otevřený zdrojový kód

-   Splňuje bezpečnostní požadavky dle [minimálního bezpečnostního
    standardu](https://nukib.cz/download/publikace/podpurne_materialy/minimalni-bezpecnostni-standard_v1.2.pdf)

-   Být připraven zvládnout provozní zátěž ve špičkách zájmu o využití
    jednotlivých služeb (např. pomocí asynchronní architektury,
    využitím [cloud
    computingu](https://archi.gov.cz/nap:egovernment_cloud), atd.)

Postup činností práce s klientem, jeho identifikací a výběrem služeb
(kompletní pravidla zde
<https://archi.gov.cz/znalostni_baze:prace_s_klientem>) se řídí celkem 5
scénáři:

1)  Klient je subjektem údajů v ROB, je na portálu nově, není v žádné
    agendové evidenci či systému

2)  Klient je subjektem údajů v ROB, je na portálu nově, je v agendové
    evidenci či systému

3)  Klient je subjektem údajů v ROB, je na portálu poněkolikáté

4)  Klient není subjektem údajů v ROB, je na portálu poprvé

5)  Klient není subjektem údajů v ROB, je na portálu poněkolikáté

# Elektronické formuláře

Pro digitalizaci služeb je třeba zajistit správný vstup strukturovaných
dat. K tomu slouží elektronické formuláře. Ovšem ne každý elektronický
dokument je elektronickým formulářem. Elektronický formulář je
strukturovaný dokument umožňující vkládání dat. Často používané PDF nebo
MS Word dokumenty toto neumožňují. Pro srovnání s ostatními zeměmi
Evropské unie a zejména podle zákona o právu na digitální službu by
elektronické formuláře měly umět automaticky předvyplňovat data na
základě přihlášení přes elektronickou identitu. Musí být schopné získat
alespoň základní údaje ze základních registrů a interních systémů úřadu.

## Elektronický dokument:

-   Elektronickým dokumentem se dle nařízení eIDAS a zákona o
    archivnictví a spisové službě myslí „jakýkoli obsah uchovávaný v
    elektronické podobě, zejména jako text nebo zvuková, vizuální nebo
    audiovizuální nahrávka" respektive „každá písemná, obrazová, zvuková
    nebo jiná zaznamenaná informace, ať již v podobě analogové či
    digitální, která byla vytvořena původcem nebo byla původci
    doručena". Jde tedy o širokou škálu možností a ztvárnění informací,
    ať už strukturovaných či nestrukturovaných. Může to být textový
    dokument, tabulka, prezentace, obrázek, PDF soubor, elektronická
    kniha atd. Elektronické dokumenty slouží k uchování a prezentaci
    informací a mohou být vytvářeny, upravovány a ukládány pomocí
    různých softwarových aplikací, například textových editorů,
    tabulkových procesorů, grafických programů apod.

## Elektronický formulář:

-   Elektronický formulář je interaktivní nástroj, který slouží k
    získání dat od uživatelů prostřednictvím webového rozhraní. Jedná se
    o strukturovaný dokument, který obsahuje různé prvky a políčka, jako
    jsou textová pole, checkbox, radio tlačítka, dropdown menu, tlačítka
    atd. Uživatelé vyplňují tento formulář s ohledem na požadované
    informace a po odeslání se data zpracovávají. Elektronické formuláře
    jsou často používány pro sběr dat, registrace, objednávky, zpětnou
    vazbu od uživatelů a další interakce. Odeslané údaje z formulářů
    mohou být uloženy do databáze, zpracovány systémem a použity k
    dalšímu zpracování.

Hlavní rozdíl mezi elektronickým dokumentem a elektronickým formulářem
spočívá v jejich účelu a povaze. Elektronický dokument slouží k uchování
a prezentaci informací, zatímco elektronický formulář slouží k interakci
s uživateli a získávání dat od nich. Elektronický formulář je specifický
typ elektronického dokumentu, který je navržený pro vyplňování a
odesílání dat, zatímco elektronický dokument může být jakýmkoliv typem
digitálního záznamu.

Splnění povinnosti zveřejnit elektronický formulář se zajistí uvedením
přesného odkazu ve formátu URL do detailního popisu služby v Katalogu
služeb veřejné správy. Pokud ohlašovatel uvede přesný odkaz, splní tím i
povinnost uvést strukturu, formát a obsah. Uvedení odkazu směřujícího
pouze na rozcestník není technicky chybné, ale není naplněním povinností
dle odst. 3.

Minimální požadavky na elektronický formulář jsou následující: 

-   Umožňuje vstup strukturovaných dat. 

-   Po přihlášení přes elektronickou identitu je schopný předvyplnit
    data ze základních registrů, interních systémů úřadu, a dalších
    relevantních systémů jiných úřadů. 

-   Obsahuje identifikátory agendy/služby/úkonu, informačního systému a
    rolí (resp. jakákoli jiná metadata) pro automatizované zpracování. 

    -   Výjimku mohou tvořit obecné formuláře sloužící pro více agend,
        typicky podací formuláře k podání stížnosti, která přiřazují
        agendu až následně.

-   Je nezávislý na platformě a lze ho používat v běžných webových
    prohlížečích. 

-   Je responzivní a vhodný pro použití na počítačích i mobilních
    zařízeních. 

-   Výsledkem je PDF s identifikátorem podle bodu 3 a strukturovanými
    daty ve strojově čitelné podobě vloženými jako kontejner do obálky
    PDF. 

-   Umožňuje odeslání dat přes datovou schránku, portál nebo dokumentem
    s uznávaným elektronickým podpisem přes email do elektronické
    podatelny (dle Nález ÚS spis. zn. IV.ÚS 1829/13 je možné také
    podepsat celý email). 

-   Formulář musí být přístupný i bez přihlášení pro fyzické osoby (§ 14
    odst (1) -  nepodnikající fyzické osoby nemohou být nuceny využívat
    digitální služby nebo činit digitální úkony podle tohoto zákona.)

    -   Pokud se klient nepřihlásí následně elektronickou identitou nebo
        nebude mít spárovaný svůj kvalifikovaný certifikát pro
        elektronický podpis s ROB, budou muset na straně OVM probíhat
        úkony vedoucí k jednoznačnému ztotožnění podatele.

## Přílohy podání

Vyžaduje-li úkon v rámci digitální služby přílohy, je nutné myslet
především na to, že veškeré údaje/informace, které by měly být obsahem
přílohy, a které jsou vedeny v jiném informačním systému veřejné správy,
si má úřad obstát sám v rámci agendového zmocnění nebo se souhlasem
uživatele dle § 9 zákona č. 12/2020 Sb. Správná cesta je vždy využívání
dat, tedy propojení systémů. Využívání dokumentů a výpisů je nežádoucí.

Pokud je potřeba příloha, která nemá své údaje v informačním systému
veřejné správy, je důležité také v rámci úkonu vědět, zda se vyžaduje
jako příloha originální dokument nebo kopie -- z čehož plyne požadavek
na uživatele například v rámci autorizované konverze.

# Poplatky

*Správní úřad sníží poplatek o 20 %, nejvýše však o 1000 Kč, pokud je
žádost nebo jiný návrh k provedení úkonu podán na elektronickém
formuláři zveřejněném podle zákona upravujícího právo na digitální
služby. To neplatí, pokud žádost nebo jiný návrh nelze podat jinak než
na tomto elektronickém formuláři. Sleva na poplatku se zaokrouhluje na
celé koruny nahoru.".*

Pokud lze podání učinit prostřednictvím zveřejněného elektronického
formuláře i jinou formou a uživatel služby si vybere podání pomocí
elektronického formuláře, je povinnost poskytnout slevu 20 % (nejvýše
však 1000Kč) ze správního poplatku. Sleva se poskytuje pouze ze
správního poplatku podle zákona o správních poplatcích. Tj. z poplatku
za úkon, nikoliv třeba z místního poplatku podle zák. o místních
poplatcích.

# Poměr správního řádu a ZoPDS

Podle ustanovení § 37 odst. 4 správního řádu je podání možno učinit
písemně nebo ústně do protokolu anebo v elektronické podobě, přičemž za
podmínky, že podání je do 5 dnů potvrzeno, popřípadě doplněno způsobem
uvedeným ve větě první, je možno je učinit pomocí jiných technických
prostředků, zejména prostřednictvím dálnopisu, telefaxu nebo veřejné
datové sítě bez použití podpisu.

Úprava obsažená v § 4 zákona o právu na digitální služby je specifikací
(upřesněním) uvedené obecné právní úpravy obsažené ve správním řádu (jde
tedy o speciální právní úpravu). S výčtem kanálů souvisí i další právní
předpisy, které v rámci elektronického právního jednání stanovují účinky
podpisu. Při podání datovou schránkou se uplatní veřejnoprávní fikce
podpisu podle zákona o elektronických úkonem, e-mailová podání musí být
podepsána uznávaným elektronickým podpisem podle zákona o službách
vytvářejících důvěru a úkon učiněný prostřednictvím ISVS se za podmínek
podle § 8 zák. o ISVS považuje také za podepsaný.

Vedlo toho však ještě § 37 odst. 4 SŘ umožňuje k zachování lhůty i
učinění nepodepsaného podání, a to za podmínek stanovených v tomto
ustanovení.

# Návrhy na novelizaci ZoPDS

Za účelem nalezení řešení, které zachová smysl a účel učinění
digitálního úkonu, přinese uživateli co nejvyšší komfort při zachování
jeho práv, a které bude pro OVM jednoduché, účelné, efektivní a
hospodárné, měla by být zvážena novelizace § 4 ZoPDS. Ta může spočívat
zejména v:

1.  Přehodnocení, zda mají být veškeré digitální úkony dostupné všemi
    vyjmenovanými kanály. Především s ohledem na využívanost některých
    úkonů by při implementaci všech kanálů docházelo k nehospodárným
    výdajům na straně veřejných financí. Zároveň je však nutné zachovat
    to, že každé OVM má povinnost mít veškeré kanály implementované a
    rozhodování by se mělo činit jen nad konkrétními úkony, nikoliv nad
    implementací kanálu jako celku.

2.  Upravit či dovysvětlit rozpor mezi § 14 odst. 7 ZoPDS, kdy nařízení
    vlády má stanovit seznam služeb dostupných na kontaktním místě
    veřejné správy a § 8a odst. 1 zákona č. 365/2000 Sb. o informačních
    systémech veřejné správy, který stanovuje, že podání prostřednictvím
    kontaktních míst veřejné správy lze činit pouze v rozsahu stanoveném
    jinými právními předpisy

3.  Vypuštění věty druhé z ustanovení § 4 odst. 3 ZoPDS, podle níž
    formát, strukturu a obsah formuláře stanoví orgán veřejné moci
    zveřejněním. Daná věta nemá žádný přínos, a to i ve světle pojednání
    obsaženého ve výkladovém podkladu (vizte odstavec třetí v kapitole
    4.2 (Elektronický formulář)), neboť pro adresáty (uživatele služby)
    je rozhodující, že bude umožněno učinit úkony prostřednictvím
    zveřejněných elektronických formulářů.

# Odlišné stanovisko členů meziresortní pracovní skupiny 

## Ministerstvo dopravy

Podle § 4 odst. 1 písm. d) zákona č. 12/2020 Sb., o právu na digitální
služby a o změně některých zákonů, ve znění pozdějších předpisů, (dále
jen „zákon o právu na digitální služby") má uživatel služby právo činit
digitální úkon vůči orgánu veřejné moci prostřednictvím informačního
systému veřejné správy umožňujícího prokázání totožnosti uživatele
služby s využitím elektronické identifikace, autorizaci digitálního
úkonu uživatelem služby a zpětné prokázání projevu vůle uživatele služby
učinit digitální úkon. Ve výkladovém podkladu zpracovaném Digitální
a informační agenturou (dále jen „agentura") je uvedeno, že „\[K\]anál
informačního systému veřejné správy umožňující elektronické prokázání
totožnosti (neboli portál) je vhodný pouze u těch úkonů, u kterých se dá
daná investice obhájit z pohledu účelnosti, účinnosti a efektivnosti
(3E)". Výkladový podklad v této souvislosti odkazuje též na Příručku
plánování digitalizace služeb veřejné správy České republiky. **Žádáme o
vysvětlení**, jaký je pro toto tvrzení dán **právní základ** (tedy
o jaké konkrétní ustanovení kterého právního předpisu se toto tvrzení
opírá). Ustanovení § 4 zákona o právu na digitální služby zakotvuje
právo uživatele služby činit digitální úkon vůči orgánu veřejné moci a
je nezbytné (a to i podle výkladového podkladu) umožnit mu **zvolit si
ze všech zde uvedených kanálů** ten, který mu nejvíc vyhovuje. Zakotvení
tohoto práva je základním cílem tohoto ustanovení. Zatímco v případě
některých z kanálů uvedených ve výčtu (vizte § 4 odst. 1 písm. a) až e)
zákona o právu na digitální služby) jsou stanoveny **limity jejich
využití** (vizte například písmeno b), podle něhož je právo učinit
digitálně úkon prostřednictvím kontaktního místa veřejné správy dáno
pouze tehdy, stanoví-li to o tomto úkonu prováděcí právní předpis, nebo
písmeno e), podle něhož lze činit digitální úkon jiným způsobem, ovšem
jen pokud tak stanoví právní předpis), **u písmene d)** **žádné
omezení** pro využití portálového způsobu učinění digitálního úkonu
**dáno není**. **Domníváme se, že takové omezení nelze dovozovat ani z §
13 zákona o právu na digitální služby**. Podle § 13 uvedeného zákona
orgán veřejné moci zpřístupní digitální službu uživateli služby bez
závislosti na konkrétní platformě či technologii, ledaže by takové
řešení bylo nepřiměřeně ekonomicky náročné, nesplňovalo požadavky na
bezpečnost informačního systému veřejné správy nebo mu bránil jiný
právním předpisem chráněný veřejný zájem. Dané ustanovení tedy zakotvuje
právo uživatele při jeho komunikaci s orgány státu na užívání různých
**platforem či technologií** a v žádném případě **nesměřuje ke zúžení**
jeho práva na činění digitálního úkonu vůči orgánu veřejné moci (dle své
volby) prostřednictvím jednoho ze **zákonem vymezených kanálů**.
Argument analogického použití pravidla obsaženého v § 13 zákona o právu
na digitální služby na úpravu zakotvující právo učinit úkon vůči orgánu
veřejné moci prostřednictvím jednoho ze zákonem vymezených kanálů podle
§ 4 téhož zákona obsažený v části 2 (Obslužné kanály pro podání --
učinění úkonu) kapitole 2.1 (Posuzování hospodárnosti při zpřístupnění
ISVS pro digitální úkon) výkladového podkladu **považujeme za
nepřesvědčivý**.

Výkladový podklad na tuto otázku odpověď nedává a není možné ji nalézt
ani v odkazované příručce. Tato otázka je podle našeho názoru **zcela
klíčová**, neboť vybudování informačního systému veřejné správy je
značně nákladné a správní orgány by (z důvodu nutnosti umožnit uživateli
každé služby zahrnuté v katalogu služeb učinit úkon i prostřednictvím
portálového řešení) byly nuceny vynakládat značné prostředky. Argument
obsažený ve výkladovém podkladu, podle něhož je právo učinit digitální
úkol prostřednictvím portálu vhodný pouze tehdy, kdy je danou investici
možné obhájit z hlediska principu 3E, **není-li podložen** dostatečným
právním základem (konkrétním normativním textem), by v případě, kdy by
se uživatel domáhající se tohoto práva obrátil na soud, zcela jistě
**neobstál**. Důsledkem by mohl být vznik odpovědnosti státu za škodu
způsobenou tím, že tomuto právu nebylo učiněno zadost. Nepodaří-li se
pro nastíněné omezení dané možnosti dostatečný právní základ nalézt,
**mělo by být předmětné ustanovení** zákona o právu na digitální služby
v tomto smyslu **doplněno**, a to co nejdříve.

Ministerstvo dopravy též upozorňuje na to, že tvrzení, podle něhož
ohlašovatel, který uvede přesný odkaz, tím splní i svoji povinnost uvést
strukturu, formát a obsah formuláře (jak je uvedeno v kapitole 4.2
výkladového podkladu), z příslušné normativní úpravy **dovozovat
nelze**.
