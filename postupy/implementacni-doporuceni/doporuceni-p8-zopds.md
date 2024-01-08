---
layout: default
title: Návrh implementace § 8 ZoPDS Právo na zápis práva nebo skutečnosti a souvisejících povinností 
parent: Implementační doporučení ZoPDS
nav_order: 8
last_modified_date: 2024-01-08
grand_parent: Postupy
---

Toto je dokument Digitální a informační agentury zpracováný v rámci [Implementace povinností dle zákona o právu na digitální služby](https://archi.gov.cz/znalostni_baze:implementace_zopds?s[]=implementace%2A&s[]=z%C3%A1kona%2A&s[]=o%2A&s[]=pr%C3%A1vu%2A&s[]=na%2A&s[]=digit%C3%A1ln%C3%AD%2A)


### Obecná východiska § 8

ZoPDS zde upravuje další projev zásady „once only“ a umožňuje uživateli zápis práva, povinnosti nebo právní skutečnosti (dále také jako „PPP“), která se tohoto uživatele týká a vyplývá z úkonu OVM uvedeného v katalogu služeb, do registru práv a povinností. Smyslem je, aby pak uživatel tato PPP nemusel OVM znovu prokazovat a dokládat. ZoPDS tímto ustanovením také navazuje na předchozí úpravu § 52 zákona o základních registrech upravující zápis údajů o právech o povinnostech osob do základních registrů.

#### Podmínky zápisu PPP

PPP nelze do registru práv a povinností zapsat bez dalšího, ale musí být splněny následující podmínky:

1.  PPP se týká uživatele služby.
2.  PPP vyplývá z úkonu OVM uvedeného v katalogu služeb.
3.  PPP dosud není zapsáno v základním registru nebo agendovém informačním systému.

Více § 8 ZoPDS zápis PPP neomezuje. Primárně tedy může být PPP zejména založeno rozhodnutím OVM v rámci řízení, jehož je uživatel služby účastníkem (i „vedlejším“ či „jiným“ účastníkem) či jiným úkonem OVM. Tento úkon se musí uživatele dotýkat, tedy jím jsou založena, měněna, rušena práva nebo povinnosti uživatele nebo konstatováno, že uživatel tato práva má či nemá. Podmínkou však je, aby PPP již nebylo zapsáno v základním registru nebo agendovém informačním systému, aby nedocházelo k duplicitním zápisům.

#### Příklady užití § 8

Důvodová zpráva ZoPDS přináší následující příklady užití § 8: *„Údajem zapisovaným do registru práv a povinností bude moci být například oprávnění k řízení motorového vozidla, oprávnění k držení zbraně, ale také dosažené vzdělání na základě vydaného vysvědčení či diplomu. Předmětné údaje pak budou moci sdílet všechny orgány veřejné moci a uživatel služby je nebude nucen prokazovat doklady, průkazy, osvědčeními nebo jinými veřejnými listinami.“*

### Práva, povinnost, právní skutečnosti

Veškerá práva, povinnosti a právní skutečnosti ve smyslu § 8 odst. 1 ZoPDS (dále také jako „PPP“) by měly být evidovány v informačních systému veřejné správy. Orgány veřejné moci by splněním evidence PPP jako jakékoliv jiného údaje o subjektech práva dle zákona č. 111/2009 Sb. eliminovaly potřebu zapisovat je specificky do registru práv a povinností.

Samotná evidence v informačním systému veřejné správy je však v cílovém stavu nedostatečná. Orgán veřejné moci musí následně zajistit opět dle povinností výše zákona č. 111/2009 Sb., aby údaje, které představují PPP, publikoval na referenčním rozhraní veřejné správy a umožnil jejich čerpání nejen subjektu práva, ale i jiným orgánům veřejné moci a soukromoprávním uživatelům údajů.

Při splnění výše zmíněných bodů se také automaticky předpokládá, že orgán veřejné moci dokáže PPP ztvárnit také ve formě výpisu z informačního systému veřejné správy a pracovat s ním jako s veřejnou listinou dle § 9 zákona č. 365/2000 Sb.

### Zápis PPP

V případě, že existuje PPP, které není vedené v informačním systému veřejné správy – a není k tomu důvod, má uživatel právo nechat si PPP zapsat prostřednictvím DIA do registru práv a povinností. V takovém případě nastává následujících sada kroků:

1.  Uživatel požaduje zápis PPP prostřednictvím formuláře zveřejněného na portále občana. Uživatel přitom uvede, kterého úkonu OVM uvedeného v katalogu služeb se PPP týká. Mělo by jít o údaje, na základě kterých bude DIA moci identifikovat tento úkon a přikročit k dalším krokům. Půjde tedy zejména o identifikaci OVM, který úkon učinil, a identifikaci tohoto úkonu (například číslem jednacím). Žadatel může uvést kontaktní údaj, na který mu bude sděleno, jak byl požadavek vyřízen.
2.  DIA odešle na základě požadavku uživatele datovou zprávu na správci agendy k ověření, že příslušné PPP skutečně existuje a neeviduje se v informačním systému veřejné správy.
3.  Pokud žadatel uvedl kontaktní údaje, nebo disponuje datovou schránkou, je mu ze strany DIA odpovězeno.
4.  Orgán veřejné moci vydávající PPP má následně povinnost zapsat PPP do registru práv a povinností, což provede prostřednictvím AIS Působnostní jako správce agendy
5.  **Orgán veřejné moci vydávající PPP je editorem tohoto referenčního údaje a je zodpovědný za platnost a po ukončení platnosti označí zápis v RPP za neplatný (nemaže)**

**Cílem je**, aby každý orgán veřejné moci vedl dané údaje v informačním systému veřejné správy a poskytoval je na referenčním rozhraní veřejné správy, a vyhnul se tedy povinnosti stát se editorem PPP se všemi zodpovědnostmi, které s tím souvisí.

#### Vstupy a výstupy procesů zápisu PPPs

Podoba žádosti, kterou bude uživatel služby žádat o zápis PPPs do RPP a informace vydávané z RPP o PPPs zapsaných v RPP jsou popsány

#### Žádost o zápis PPPs

Žádost o zápis PPPs do RPP bude obsahovat

-   ID uživatele služby (AIFO, IČO)
-   Datum a čas podání žádosti
-   Identifikace PPPS (výběr ze seznamu PPPs, které nejsou vedeny elektronicky a je je možné zapsat do RPP)
-   OVM které PPPs vydalo
-   Datum vydání PPPs
-   Identifikátor PPPs (jednací číslo, identifikátor dokladu,….)
-   Kopie dokumentu, kterým uživatel služby PPPs prokazuje. (sken dokumentu v PDF, nepovinný, jen pro potřeby ověření žádosti)
-   Rozsah oprávnění na využití PPPs

#### Informace o PPPs vydávané z RPP

O zapsaných PPPs budou z RPP vydávány tyto informace:

-   ID uživatele služby (AIFO, IČO)
-   Identifikace PPPS (výběr ze seznamu PPPs, které nejsou vedeny elektronicky a je je možné zapsat do RPP)
-   OVM, které PPPs vydalo
-   Datum vydání PPPs
-   Identifikátor PPPs (jednací číslo, identifikátor dokladu,….)
-   Platnost PPPs od
-   Platnost PPPs do
-   Datový obraz PPPs (strukturované údaje o PPPs v rozsahu, který bude definován u služby VS z které je PPPs výstupem)
-   Rozsah oprávnění na využití PPPs

#### Proces zápisu PPPs do RPP.

Základní proces pro zápis PPPs je znázorněn na následujícím diagramu.

![](media/e74065c3d4c7922d70426efdb3ebaf70.png)

### Funkcionality IS podílejících se na zápisu PPPs

Na zápisu PPPs do RPP se budou podílet AIS Působnostní (AISP), Portál veřejné správy (PVS), AIS správy zápisů do RPP(AISZ).

#### AISP

AISP bude rozšířen o:

-   Funkcionalitu pro definici PPPs, které lze zapsat do RPP. U služeb VS, kde je příznak, že výsledek služby není vedený v základních registrech či agendovém informačním systému, bude muset ohlašovatel agendy definovat seznam PPPs, které mohou být výstupem služby VS, a pro každé definované PPPs definovat strukturu datového obrazu daného PPPs (údaje, které bude muset OVM, které osvědčí existenci PPPs vyplnit).
-   Rozhraní pro načítání informací o PPPs, které lze zapsat do RPP pro potřeby podání žádosti o zápis PPPs uživatelem služby přes PVS. Komunikace mezi PVS a AISP bude probíhat přes ISSS (eGSB).

#### PVS

PVS bude rozšířen o:

-   Funkcionalitu pro podání žádosti o zápis PPPs uživatelem služby. Jedná se o ověření identity uživatele služby, nabídky formuláře pro vytvoření žádosti o zápis PPPs (s využitím seznamu PPPs, které lze zapsat do RPP).
-   Funkcionalita pro zápis žádosti o PPPs do AISZ. Jedná se o zápis žádosti do AISZ pro další zpracování a potvrzení o přijetí žádosti.
-   Funkcionalita pro zobrazení přehledu PPPs. Jedná se o zobrazení přehledu žádostí o zápis PPPs uživatele služby a stavu vyřízení žádostí a přehledu zapsaných PPPs včetně detailního zobrazení PPPs.
-   Funkcionalita pro reklamaci údajů o PPPs vedených v RPP uživatelem služby.
-   Funkcionalita pro zrušení zápisu PPPs v RPP. Jedná se o výmaz již zapsaného PPPs, nebo žádosti o zápis PPPs na základě požadavku uživatele služby.
-   Funkcionalita pro definici rozsahu oprávnění na využití PPPs.

Pozn.

Úprav funkcionality PVS není součásti projektu na úpravu RPP (řešený na základě DD5) je zde uvedena pro potřeby popisu celkového fungování zápisu PPPs do RPP.

#### AISZ

Bude vytvořen AISZ pro podporu procesu zápisu PPPs do RPP a jejich následnou správu, který bude poskytovat:

-   Rozhraní pro komunikaci PVS a AISZ. Komunikace mezi PVS a AISZ bude probíhat přes ISSS (eGSB). Jedná se o služby pro:
    -   zápis údajů o žádosti, které PVS zapíše do AISZ na základě podkladů poskytnutých uživatelem služby,
    -   poskytnutí informaci o stavu zpracování žádostí o zápis PPPs do RPP,
    -   poskytnutí přehledu PPPs zapsaných do RPP a jejich platností,
    -   poskytnutí detailních informací, které jsou o PPPs vedeny v RPP,
    -   reklamaci údajů o PPPs vedených v RPP,
    -   zrušení PPPs zapsaného v RPP,
    -   zrušení žádosti o zápis PPPs do RPP,
    -   zápis rozsahu oprávnění na využití PPPs.
-   Funkce pro zpracování zapsaných žádostí o zápis PPPs do RPP. Jedná se o kontrolu správnosti a úplnosti předaných žádostí a předání žádostí k dalšímu zpracování (Předání OVM, které učinilo podkladový úkon, předání správci RPP, pro rozhodnutí o dalším zpracování, odmítnutí)
-   Funkce pro osvědčí existenci PPPs. Funkcionalita pro jednotlivá OVM, která učinily podkladový úkon, pro potvrzení nebo odmítnutí existence PPPs a doplnění údajů o příslušném PPPs ( platnost od, platnost do, datový obraz PPPs) v případě jeho potvrzení.
-   Funkcionalita pro aktualizaci PPPs. Funkcionalita pro OVM, který učinil podkladový úkon, která umožní OVM aktualizovat informace o PPPs, které je zapsáno v RPP pokud došlo k jeho změně (úprava rozsahu PPPs, zrušení PPPs).
-   Funkcionalita pro zpracování reklamace PPPs. Funkcionalita pro OVM, která umožní zpracovat reklamaci údajů o PPPs podanou uživatelem služby, její vyhodnocení a úpravu údajů PPPs, v případě oprávněné reklamace nebo zamítnutí v případě neoprávněné reklamace a vyrozumění uživatele služby o vyřízení reklamace.
-   Funkcionalita pro zpracování sporných žádostí o zápis PPPs. Jedná se o funkcionalitu pro správce RPP, která podporu rozhodnutí o dalším zpracování žádosti, které nebylo možno automaticky předat na OVM, který učinil podkladový úkon.
-   Funkcionalita pro zápis PPPs do RPP. Funkcionalita, která umožní zápis PPPs a změn PPPs, které potvrdilo OVM, který vydal podkladový úkon a nastavení rozsahu oprávnění
-   Funkcionalita pro monitoring zápisu PPPs do RPP. Jedná se o funkcionalitu pro správce RPP, která umožní sledovat podané žádosti o zápis PPPs do RPP stav jejich zpracování a zobrazit přehledy zapsaných PPPs a jejich rozsahu oprávnění na využití.
-   Funkcionalita pro využití zapsaných PPPs. Jedná se o funkcionalitu pro OVM vykonávající agendy, která na základě definovaných oprávnění umožní zobrazit informace o PPPs zapsané v RPP.
-   Notifikační funkce. Funkcionalita pro podporu zasílání notifikaci o změně PPPs uživateli služby na základě změny údajů o PPPs v RPP.
-   Výpisové funkce. Funkcionalita pro tvorbu výpisu o využití údajů o PPPs na žádost, ročních výpisů o využití údajů a výpisu údajů vedených v RPP.
-   Rozhraní pro poskytování údajů o PPPs zapsaných do RPP pro potřeby OVM. Komunikace mezi AIS OVP a AISZ bude probíhat přes ISSS (eGSB) (Oprávnění pro výdej údajů bude řídit ISSS). Jedná se o služby pro:
    -   Výpis seznamu PPPs podle výběrových kritérii (uživatel služby, OVM který učinil podkladový úkon, identifikátor PPPs)
    -   Výpis detailu konkrétního PPPs

### Využití PPPs zapsaných v RPP.

OVM mohou údaje o PPPs zapsané v RPP využívat:

-   Pomocí AIS podporující výkon jejich agend. Využití výměny dat přes ISSS (eGSB). Pozn. Oprávnění na údaje řídí ISSS na základě platných oprávnění v RPP (rozsah oprávnění na využití definované uživatelem služby).
-   Pomocí GUI AISZ. Pro AISZ bude definována činnostní role, prostřednictvím které budou mít všechna OVM přístup ke GUI AISZ pro vyhledání a zobrazení PPPs. Zobrazení se bude řídit rozsah oprávnění na využití definované uživatelem služby a přístup k údajům PPPs bude logován (OVM využívající PPPs, agenda + činnost pod kterou bylo PPPs využito, důvod a účel využití PPPs).
