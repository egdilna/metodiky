---
layout: default
title: "WCAG 2: Principy a pravidla standardu Web content accessibility guidelines"
description: Český překlad základních součástí mezinárodní normy WCAG - principy a pravidla přístupnosti
nav_order: 7
parent: Oblast Přístupnost informací
grand_parent: Metodiky
last_updated_date: 2019-08-05
---



> Přeneseno z archivu webového portálu Přístupnost informací

Tento dokument je součástí české dokumentace k provádění mezinárodního standardu Web content accessibility guidelines (WCAG2) a je určen zejména pro technickou realizaci přístupnosti internetových stránek pro osoby se zdravotním postižením. 

OBSAH

- TOC
{:toc}



Úvod
====

Tento dokument obsahuje souhrn principů a pravidel pro technickou přístupnost
stanovených v mezinárodním standardu Web content accessibility guidelines
(WCAG). Jedná se o neoficiální překlad do českého jazyka, oficiální překlad
příslušné mezinárodní ISO normy WCAG do češtiny nebyl dosud realizován. Dokument
je doplněn o praktické souvislosti, jako je souhrn základních poznatků k
naplnění principů v praxi.

Použití tohoto dokumentu
------------------------

Tento dokument obsahuje popisy principů a pravidel stanovených ve standardu WCAG
2. Je primárně určen pro vývojáře internetových stránek a aplikací, ale také pro
zodpovědné manažery u všech organizací, které se věnují správné přístupnosti
svých internetových stránek také pro osoby se zdravotním postižením.

Popis mezinárodního standardu WCAG
==================================

Standard Web content accessibility guidelines (WCAG 2)
------------------------------------------------------

Pro stanovení a sjednocení konkrétních technických principů a pravidel pro
přístupnost informací pro osoby se zdravotním postižením zejména u obsahu
internetových stránek a aplikací byl vytvořen mezinárodní Standard Web content
accessibility guidelines (WCAG). Standard WCAG je rozdělen do 4 principů – obsah
musí být vnímatelný, ovladatelný, srozumitelný a robustní. Každý princip je dále
členěn na několik pravidel (celkem je jich 12). Každé pravidlo má
několik kritérií úspěšnosti, které mají přiřazeny úrovně (A, AA, AAA) a jejich
(ne)splnění lze ověřit. Počet kritérií u jednotlivých pravidel se liší, stejně
tak se liší jejich úrovně. U některých pravidel jsou zastoupena kritéria
úspěšnosti všech úrovní, u některých může jedna či dvě úrovně chybět. Úrovně A,
AA a AAA vystihují význam jednotlivých kritérií úspěšnosti – například u
předtočených audiostop má požadavek na přepis do znakového jazyka prioritu AAA,
ale požadavek na vytvoření alternativy úroveň A.

Oficiální webová stránka standardu WCAG (v angličtině) je na adrese
<https://www.w3.org/WAI/standards-guidelines/wcag/>

Českou dokumentaci a další související materiály ke standardu WCAG najdete pak
na adrese [www.pristupnost-informaci.cz](http://www.pristupnost-informaci.cz)

Použití standardu v praxi
-------------------------

WCAG je mezinárodní standard konkrétních principů, pravidel, kritérií a postupů
shody. To znamená, že jde od nejvyšší úrovně (principy), až po velice detailní
techniky pro jejich naplnění. K dispozici je několik technických návodných
dokumentů v angličtině obsahujících mnoho set stran podrobných metod, jak
dosáhnout souladu s pravidly přístupnosti a jak se k pravidlům postavit
prakticky a jak si je i následně ověřit.

Základní možnosti použití WCAG pro přístupnost obsahu jsou:

1.  Využití při definici cíle projektu, třeba u internetových stránek,

2.  využití pro specifikaci technických požadavků na přístupnost pro zadávací
    dokumentaci projektu a zadání veřejné zakázky,

3.  využití jako povinných principů technické publikace webového obsahu,

4.  využití pro sebekontrolu a ověření souladu obsahu webových stránek s
    potřebami osob se zdravotním postižením.

Principy a pravidla přístupnosti podle standardu WCAG
=====================================================

Níže jsou uvedeny jednotlivé principy a pravidla pro technickou přístupnost
informací pro osoby se zdravotním postižením a jejich součásti.

Celý standard je rozdělen do čtyř základních principů, které je nutno při tvorbě
obsahu a jeho prezentaci dodržet. Níže jsou pak pravidla a ty rozpracovávají
jednotlivé požadavky, které jsou označeny mírou důležitosti.

Jednotlivá pravidla standardu přístupnosti
===========================

Princip 1: Vnímatelnost — Informace a součásti uživatelských rozhraní musí býtprezentovány tak, aby je uživatelé byli schopni vnímat.
----------------------------------

### Pravidlo 1.1 Textové alternativy: Opatřete každý netextový obsah textovými alternativami, které je možné podle potřeby převést do jiných formátů jako například zvětšené písmo, bodové písmo, fonetický přepis či zjednodušený jazyk.

#### 1.1.1 Non-text Content: Každý netextový obsah, který je uživateli prezentován, má svou textovou alternativu, sloužící stejnému účelu. Výjimku tvoří případy uvedené níže. (Úroveň A)

1.  Ovládací prvky a prvky reagující na vstup uživatele: Jestliže netextovým
    obsahem je ovládací prvek či prvek reagující na vstup uživatele, pak má
    tento prvek název popisující jeho účel. (Další požadavky týkající se
    ovládacích prvků a prvků reagujících na vstup uživatele viz pravidlo 4.1.)

2.  Multimediální prvek závisející na čase: Jestliže je netextový obsah
    multimediální prvek závisející na čase, pak jeho textová alternativa alespoň
    popisuje jeho účel a charakter. (viz pravidlo 1.2.)

3.  Test: Jestliže je netextový obsah test nebo cvičení, které nelze převést do
    textové podoby tak, aby zůstala zachována jeho funkčnost, pak textová
    alternativa alespoň popisuje jeho charakter a účel.

4.  Vjem: Jestliže primárním účelem netextového obsahu je zprostředkování
    určitého smyslového zážitku, pak textová alternativa netextového obsahu
    alespoň popisuje jeho charakter a účel.

5.  CAPTCHA: Jestliže účelem netextového obsahu je ověření, že s obsahem pracuje
    skutečný uživatel a nikoli robot, pak textová alternativa tohoto netextového
    obsahu alespoň popisuje jeho účel a charakter. Poskytněte rovněž jiné
    alternativy kódu CAPTCHA, které využívají různé smysly, abyste pokryli různá
    postižení.

6.  Dekorace, formátování, neviditelnost: Jestliže má netextový obsah pouze
    dekorativní účel nebo je použit jako vizuální formátovací prvek, případně
    není uživateli prezentován vůbec, je použit tak, aby asistivní technologie
    mohly tento obsah bez potíží ignorovat.

### Pravidlo 1.2 Multimediální prvky závisející na čase: Opatřete multimediální prvky závisející na čase alternativami.

#### 1.2.1 Pouze audio a pouze video (předtočené): Pro případ, že multimediální prvek je tvořen pouze předtočeným audiem či pouze předtočeným videem, platí následující (výjimku tvoří případ, kdy je audio či video multimediální alternativou textu a jako takové je řádně označeno: (Úroveň A)

-   Pouze předtočené audio: Obsah prezentovaný pouze prostřednictvím
    předtočeného audia je opatřen alternativou pro multimediální prvek
    závisející na čase, která poskytuje ekvivalentní informaci pro obsah pouze v
    předtočeném audiu.

-   Pouze předtočené video: Obsah prezentovaný pouze prostřednictvím
    předtočeného videa je opatřen buď alternativou pro multimediální prvek
    závisející na čase nebo zvukovou stopou poskytující ekvivalentní informaci
    pro obsah pouze v předtočeném videu.

#### 1.2.2 Titulky (předtočené): Každý předtočený audio obsah, který je součástí synchronizovaného multimediálního prvku, je opatřen titulky. Výjimku tvoří případ, kdy je tento multimediální prvek multimediální alternativou textu a jako takový je také řádně označen. (Úroveň A)

#### 1.2.3 Audiopopis či alternativa pro multimediální prvek (předtočené): Synchronizovaný multimediální prvek je opatřen alternativou pro multimediální prvek závisející na čase nebo audiopopisem obsahu prezentovaného pomocí předtočeného videa. Výjimku tvoří případ, kdy je tento multimediální prvek multimediální alternativou textu a jako takový je také řádně označen. (Úroveň A)

#### 1.2.4 Titulky (živě): Každé živě přenášené audio, které je součástí synchronizovaného multimediálního prvku, je opatřeno titulky. (Úroveň AA)

#### 1.2.5 Audiopopis (předtočený): Každé předtočené video, které je součástí synchronizovaného multimediálního prvku, je opatřeno audiopopisem. (Úroveň AA)

#### 1.2.6 Znakový jazyk (předtočený): Každý předtočený audio záznam, který je součástí synchronizovaného multimediálního prvku, je opatřen překladem do znakového jazyka. (Úroveň AAA)

#### 1.2.7 Rozšířený audiopopis (předtočený): Tam, kde nejsou pauzy na původní zvukové stopě videa dostatečné, aby bylo možné pomocí audiopopisu video náležitě okomentovat, používá se rozšířený audiopopis. V takovém případě se rozšířeným audiopopisem opatřuje každý předtočený video obsah, který je součástí synchronizovaného multimediálního prvku. (Úroveň AAA)

#### 1.2.8 Alternativa pro multimediální prvky (předtočené): Všechny předtočené synchronizované multimediální prvky a všechna předtočená videa jsou opatřena alternativou pro multimediální prvek závisející na čase. (Úroveň AAA)

#### 1.2.9 Pouze audio (živě): Každé živě přenášené audio je opatřeno alternativou pro multimediální prvek závisející na čase, která poskytne ekvivalentní informaci pro živě přenášené audio. (Úroveň AAA)

### Pravidlo 1.3 Přizpůsobitelné: Vytvořte obsah, který lze prezentovat více způsoby (např. zjednodušený vzhled), aniž by přitom došlo ke ztrátě informací či narušení struktury.

#### 1.3.1 Informace a vzájemné vztahy: Informace, strukturu a vzájemné vztahy obsažené v prezentaci lze programově určit nebo jsou dostupné ve formě textu. (Úroveň A)

#### 1.3.2 Srozumitelné pořadí: Jestliže má pořadí informací, v němž jsou prezentovány, vliv na jejich srozumitelnost, může být správné pořadí, v němž mají být informace čteny, programově určeno. (Úroveň A)

#### 1.3.3 Vlastnosti na základě smyslového vjemu: Pokyny, jak správně vnímat obsah a jak s ním správně zacházet nezávisí výhradně na vlastnostech založených na smyslovém vnímání, které jednotlivé komponenty mají jako např. tvar, velikost, optické umístění orientace či zvuk. (Úroveň A)

Poznámka: Pro informace o kritériích týkajících se barev viz pravidlo 1.4..

### Pravidlo 1.4 Rozlišitelné: Usnadněte uživatelům slyšet a vidět obsah a odlište popředí od pozadí.

#### 1.4.1 Používání barev: Barva není používána jako jediný vizuální prostředek, sloužící k poskytnutí určité informace, k indikování určité akce, k vyjádření požadavku na odezvu či k odlišení určitého vizuálního prvku. (Úroveň A)

Poznámka: Toto kritérium přístupnosti se týká speciálně vnímání barev. Ostatními
formami vnímání se zabývá Pravidlo 1.3 včetně programového přístupu k barvám a
ostatním vizuálním formám prezentace.

#### 1.4.2 Ovládání zvuku: Jestliže se na webové stránce automaticky spustí přehrávání audia na delší dobu než tři sekundy, je k dispozici mechanismus, který umožní audio pozastavit či zastavit zcela nebo je k dispozici mechanismus, který umožní ovládat hlasitost nezávisle na globálním ovládání hlasitosti systému. (Úroveň A)

Poznámka: Jelikož jakýkoliv obsah, který nesplňuje toto kritérium přístupnosti,
může narušit schopnost uživatele pracovat s celou webovou stránkou, musí toto
kritérium splňovat každý obsah, nehledě na to, zda je zároveň používán pro
splnění nějakého jiného kritéria přístupnosti. Více informací v části
“Vyhovující obsah”, bod 5 “Soulad v interakci prvků”.

#### 1.4.3 Minimální kontrast: Vizuální podoba textu či textu ve formě obrázku má vůči svému pozadí kontrast minimálně 4,5:1. Výjimku tvoří následující případy: (Úroveň AA)

1.  Texty psané velkým fontem: Texty psané velkým fontem či texty tohoto typu
    prezentované ve formě obrázku mají kontrast minimálně 3:1.

2.  Texty, které se náhodou staly součástí prezentace a nejsou pro ni
    relevantní: text nebo text v obrázku, které jsou součástí neaktivního prvku
    uživatelského rozhraní, texty mající pouze dekorativní účel, texty, které
    nejsou viditelné žádnému uživateli nebo texty, které jsou součástí obrázku s
    nímž významově nesouvisí, nemusí splňovat žádné požadavky týkající se
    kontrastu.

3.  Logotypy: Text, který je součástí loga nebo názvu firmy či produktu,
    nepodléhá žádným požadavkům na minimální kontrast.

#### 1.4.4 Změna velikosti textu: S výjimkou titulků a textů ve formě obrázků může být text zvětšen až o 200% bez pomoci asistivních technologií, aniž dojde ke ztrátě obsahu či porušení funkčnosti. (Úroveň AA)

#### 1.4.5 Text ve formě obrázku: Jestliže technologie, která byla použita, umožňuje vizuální znázornění, doporučuje se raději použít textový formát než text ve formátu obrázku. Výjimku tvoří následující případy: (Úroveň AA)

1.  Přizpůsobitelné: Jestliže si uživatel může text v obrázkovém formátu
    vizuálně přizpůsobit svým potřebám;

2.  Zásadní: Jestliže způsob, jakým je určitý text prezentován, má zásadní vliv
    na sdělovanou informaci.

Poznámka: Logotypy — u textů, které jsou součástí loga nebo názvu firmy či
produktu, se způsob prezentace považuje za zásadní.

#### 1.4.6 Zvýšený kontrast: Graficky znázorněný text či text prezentovaný ve formě obrázku má vůči svému pozadí kontrast minimálně 7:1. Výjimku tvoří následující případy: (Úroveň AAA)

1.  Texty psané velkým fontem: Texty psané velkým fontem či texty tohoto typu
    prezentované ve formě obrázku mají kontrast minimálně 4,5:1;

2.  Texty, které se náhodou staly součástí prezentace a nejsou pro ni
    relevantní: text nebo text v obrázku, které jsou součástí neaktivního prvku
    uživatelského rozhraní, texty mající pouze dekorativní účel, texty, které
    nejsou viditelné žádnému uživateli nebo texty, které jsou součástí obrázku s
    nímž významově nesouvisí, nemusí splňovat žádné požadavky týkající se
    kontrastu..

3.  Logotypy: Text, který je součástí loga nebo názvu firmy či produktu,
    nepodléhá žádným požadavkům na minimální kontrast.

#### 1.4.7 Tlumený nebo žádný podkresový zvuk: Pro případ, že obsah tvoří pouze předtočené audio, které (1) obsahuje mluvené slovo jako hlavní složku, (2) není zvukovou variantou kódu CAPTCHA či zvukovým logem, (3) není hlasovou složkou hudebního projevu jako například zpěv nebo rap, platí alespoň jeden bod z následujícího: (Úroveň AAA)

-   Bez podkresu: Audio neobsahuje žádné podkresové zvuky.

-   Možnost vypnutí: Podkresové zvuky mohou být vypnuty.

-   20 dB: Podkresové zvuky jsou alespoň o 20 decibelů tišší než mluvená
    informace v popředí. Výjimku tvoří občasné zvuky netrvající déle než dvě
    sekundy.

Poznámka: Z definice jednoho decibelu vyplývá, že podkresový zvuk bude zhruba
čtyřikrát tišší než mluvená informace v popředí.

#### 1.4.8 Vizuální znázornění: Pro vizuální znázornění textových bloků je dostupný mechanismus, který umožňuje následující: (Úroveň AAA)

1.  Barvu popředí a barvu pozadí si může zvolit uživatel.

2.  Řádek není delší než 80 znaků, v případě obrázkového písma (čínština,
    japonština, korejština) neobsahuje víc než 40 glyfů.

3.  Text není zarovnaný do bloku.

4.  Řádkování uvnitř odstavců je alespoň 1,5, mezery mezi odstavci jsou pak
    alespoň 1,5krát větší než použité řádkování uvnitř odstavců.

5.  Velikost textu může být změněna bez pomoci asistivních technologií až o 200
    % tak, aby uživatel nemusel posouvat text do stran, chce-li přečíst celý
    řádek v maximalizovaném okně.

#### 1.4.9 Text ve formě obrázku (bez výjimek): Text ve formě obrázku se používá jen v případě, že slouží k čistě dekorativním účelům nebo tehdy, jestliže způsob, jakým je určitý text prezentován, má zásadní vliv na sdělovanou informaci. (Úroveň AAA)

Poznámka: Logotypy – u textů, které jsou součástí loga nebo názvu firmy či
produktu, se způsob prezentace považuje za zásadní.

Princip 2: Ovladatelnost: Všechny součásti uživatelského rozhraní a všechny navigační prvky musí být ovladatelné.
-----------------------------------------------------------------------------------------------------------------

### Pravidlo 2.1 Přístupnost z klávesnice: Zajistěte, aby všechny funkce byly dostupné z klávesnice.

#### 2.1.1 Klávesnice: Všechny funkce obsahu lze obsluhovat přes rozhraní klávesnice, aniž by bylo nutné jednotlivé úhozy zvláště časovat, výjimku tvoří případ, kdy vstup dané funkce reaguje na způsob pohybu při zadávání a jeho průběh. (Úroveň A)

Poznámka 1: Tato výjimka se vztahuje na danou funkci, nikoli na techniku
zadávání. Například jestliže je pro vkládání textu použito písma psaného rukou,
pak způsob zadávání “psaní rukou” reaguje na pohyb při zadávání, ale samotná
funkce vkládání textu ne.

Poznámka 2: Toto doporučení nezakazuje a nemá odrazovat od poskytování možnosti
používání myši jako vstupního zařízení či jiných způsobů vstupu, je-li zachována
možnost obsluhy z klávesnice.

#### 2.1.2 Žádná past na klávesy: Jestliže je možné přesunout fokus na určitý prvek na stránce prostřednictvím klávesnice, pak je také možné pouze prostřednictvím klávesnice fokus opět z prvku přesunout pryč. Je-li k tomu zapotřebí použít jiných kláves než šipek, tabulátoru s nezměněnou funkcí či jiných kláves standardně používaných pro návrat, je uživatel poučen o způsobu, jímž lze fokus z prvku odstranit. (Úroveň A)

Poznámka: Jelikož jakýkoliv obsah, který nesplňuje toto kritérium přístupnosti,
může narušit schopnost uživatele pracovat s celou webovou stránkou, musí toto
kritérium splňovat každý obsah, nehledě na to, zda je zároveň používán pro
splnění nějakého jiného kritéria přístupnosti. Více informací v části
“Vyhovující obsah”, bod 5 “Soulad v interakci prvků”.

#### 2.1.3 Klávesnice (bez výjimek): Všechny funkce obsahu lze obsluhovat přes rozhraní klávesnice, aniž by bylo nutné jednotlivé úhozy zvláště časovat. (Úroveň AAA)

### Pravidlo 2.2 Dostatek času: Poskytněte uživateli dostatek času k přečtení a k práci s obsahem.

#### 2.2.1 Nastavitelné časování: Pro každý časový limit, který je nastaven obsahem, platí alespoň jeden z následujících bodů: (Úroveň A)

-   Možnost vypnutí: Uživatel má možnost vypnout časové omezení dříve, než s ním
    přijde do styku; nebo

-   Možnost nastavení: Uživatel má možnost časový limit nastavit dříve, než s
    ním přijde do styku, v rozmezí alespoň desetkrát větším než je standardní
    nastavení limitu; nebo

-   Možnost prodloužení: Uživatel obdrží varování dříve, než časový limit
    vyprší, a dostane alespoň 20 sekund na prodloužení časového limitu
    jednoduchým úkonem (např. stisknutím mezerníku). Uživateli je dána možnost
    prodloužit časový limit alespoň desetkrát; nebo

Lze uplatnit následující výjimky:

-   Výjimka pro reálný čas: Časové omezení je nutnou součástí události
    probíhající v reálném čase (např. aukce) a není možné poskytnout jinou
    alternativu pro časové omezení; nebo

-   Výjimka, kdy má časové omezení zásadní význam: Daný časový limit má zásadní
    význam pro danou činnost a jeho prodloužením by byl význam činnosti
    znehodnocen; nebo

-   Výjimka pro limit delší než 20 hodin: Daný časový limit je delší než dvacet
    hodin.

Poznámka: Toto kritérium přístupnosti pomáhá zaručit, že uživatel bude mít
dostatek času na dokončení úkolů, aniž by se obsah či kontext neočekávaně změnil
v důsledku časového omezení. Toto kritérium přístupnosti je třeba brát do úvahy
ve spojení s kritériem 3.2.1, které klade omezení na změny v obsahu či kontextu
způsobené akcí uživatele.

#### 2.2.2 Pauza, Stop, Skrýt: Pro všechny informace, které se pohybují, blikají, rolují nebo se automaticky aktualizují, platí všechny následující body: (Úroveň A)

-   Pohybující se, blikající, rolující: Pro každý pohybující se, blikající či
    rolující obsah, který se (1) spouští automaticky, (2) objevuje na delší dobu
    než 5 sekund, (3) objevuje souběžně s ostatním obsahem. je dostupný
    mechanismus, který uživateli umožní pozastavení, úplné zastavení nebo skrytí
    tohoto obsahu. Výjimku tvoří případ, kdy má pohyb, blikání nebo rolování
    zásadní význam pro činnost, jejíž je součástí; a

-   Automatické aktualizování: Pro každý automaticky se aktualizující obsah,
    který se (1) spouští automaticky, (2) objevuje souběžně s ostatním obsahem
    je dostupný mechanismus, který uživateli umožňuje pozastavení, úplné
    zastavení, skrytí obsahu nebo regulování frekvence, s níž se obsah
    aktualizuje. Výjimku tvoří případ, kdy má automatické aktualizování zásadní
    význam pro činnost, jejíž je součástí.

Poznámka 1: Informace o blikajícím a kmitajícím obsahu naleznete v pravidle 2.3.

Poznámka 2: Jelikož jakýkoliv obsah, který nesplňuje toto kritérium
přístupnosti, může narušit schopnost uživatele pracovat s celou webovou
stránkou, musí toto kritérium splňovat každý obsah, nehledě na to, zda je
zároveň používán pro splnění nějakého jiného kritéria přístupnosti. Více
informací v části “Vyhovující obsah”, bod 5 “Soulad v interakci prvků”.

Poznámka 3: Jestliže software aktualizuje obsah pravidelně nebo jestliže je
obsah přenášen formou streamingu, nepožaduje se, aby klient byl schopen
uchovávat a zobrazovat informace přenesené v době mezi pozastavením a opětovným
spuštěním prezentace. Jednak je takový postup technicky patrně nemožný a jednak
by mohl být v mnoha situacích zavádějící.

Poznámka 4: O animaci, která se zobrazuje během fáze načítání obsahu či v
podobných situacích lze říci, že má zásadní význam, jestliže v té době nemá
žádný uživatel možnost interakce a absence jakéhokoli ukazatele průběhu by mohla
v uživatelích vyvolat zmatek či dojem, že proces zamrzl nebo se zhroutil.

#### 2.2.3 Žádné časování: Časování není zásadní součástí prezentované činnosti či události s výjimkou neinteraktivních synchronizovaných multimediálních prvků a událostí probíhajících v reálném čase. (Úroveň AAA)

#### 2.2.4 Přerušení: Přerušení, jako například aktualizace obsahu, může být uživatelem oddáleno či potlačeno, s výjimkou přerušení, které si vyžádala naléhavá situace. (Úroveň AAA)

#### 2.2.5 Aktualizace zabezpečeného obsahu: Jestliže doba pro práci se zabezpečeným obsahem vyprší, může uživatel po opětovném přihlášení se pokračovat v práci bez ztráty dat. (Úroveň AAA)

### Pravidlo 2.3 Záchvaty: Vynechte z prezentace takové prvky, u nichž je známo, že mohou vyvolat záchvat.

#### 2.3.1 Tři záblesky nebo podprahové blikání: Webové stránky neobsahují žádné prvky, blikající více jak třikrát za sekundu nebo je toto blikání pod prahem stanoveným obecně pro blikání a pod prahem stanoveným pro červené blikání. (Úroveň A)

Poznámka: Jelikož jakýkoliv obsah, který nesplňuje toto kritérium přístupnosti,
může narušit schopnost uživatele pracovat s celou webovou stránkou, musí toto
kritérium splňovat každý obsah , nehledě na to, zda je zároveň používán pro
splnění nějakého jiného kritéria přístupnosti. Více informací v části
“Vyhovující obsah”, bod 5 “Soulad v interakci prvků”.

#### 2.3.2 Tři záblesky: Webové stránky neobsahují žádné prvky, blikající víc než třikrát za sekundu. (Úroveň AAA)

### Pravidlo 2.4 Snadná navigace: Usnadněte uživatelům navigaci, hledání konkrétního obsahu a určování aktuální pozice.

#### 2.4.1 Přeskoč bloky: Uživatel má k dispozici mechanismus, umožňující mu přeskakovat bloky informací, které se opakovaně objevují na více webových stránkách. (Úroveň A)

#### 2.4.2 Každá stránka má titulek: Každá webová stránka má název popisující její téma či účel. (Úroveň A)

#### 2.4.3 Pořadí procházení prvku: Je-li možné webovou stránku stránku procházet v určitém pořadí, majícím vliv na smysl a funkčnost, získávají prvky focus v pořadí, které smysl a funkčnost zachovává. (Úroveň A)

#### 2.4.4 Účel odkazu (v kontextu): Účel každého odkazu může být určen pouze z textového označení nebo z textového označení v kombinaci s jeho programově určeným kontextem. Výjimku tvoří případ, kdy je účel odkazu nejednoznačný pro všechny uživatele. (Úroveň A)

#### 2.4.5 Více způsobů: Uživatel má k dispozici více než jeden způsob, jak mezi stránkami webové prezentace nalézt konkrétní požadovanou webovou stránku. Výjimku tvoří případ, kdy je tato stránka výsledkem určitého procesu nebo slouží k jeho vykonání (například proces vyhledávání) (Úroveň AA)

#### 2.4.6 Nadpisy a popisky: Nadpisy a popisky odpovídají svému účelu nebo tématu. (Úroveň AA)

#### 2.4.7 Viditelný focus: Každé uživatelské rozhraní ovladatelné z klávesnice nabízí režim, v němž je viditelný ukazatel focusu relevantního pro ovládání z klávesnice. (Úroveň AA)

#### 2.4.8 Aktuální pozice: Uživatel má k dispozici informaci o tom, na které stránce se v rámci webové prezentace právě nachází. (Úroveň AAA)

#### 2.4.9 Účel odkazu (pouze z textu odkazu): Je k dispozici mechanismus, který umožňuje určit účel odkazu pouze z jeho textové popisky, Výjimku tvoří případ, kdy účel odkazu je nejednoznačný pro všechny uživatele. (Úroveň AAA)

#### 2.4.10 Záhlaví jednotlivých částí: Záhlaví jednotlivých částí slouží k uspořádání obsahu. (Úroveň AAA)

Poznámka 1: Pojem záhlaví je chápán v obecném smyslu a zahrnuje veškeré
prostředky sloužící k logickému strukturování obsahu jako např. nadpisy apod.

Poznámka 2: Toto kritérium přístupnosti se týká strukturování textů na webu,
nikoliv strukturování jednotlivých prvků uživatelského rozhraní. Prvky
uživatelského rozhraní se zabývá kritérium přístupnosti 4.1.2.

Princip 3: Srozumitelnost: Informace a ovládání uživatelského rozhraní musí být srozumitelné.
---------------------------------------------------------------------------------------------

### Pravidlo 3.1 Čitelné: Zajistěte, aby textový obsah byl čitelný a srozumitelný.

#### 3.1.1 Jazyk stránky: Výchozí jazyk (=řeč, nikoli programovací) každé stránky lze programově určit. (Úroveň A)

#### 3.1.2 Jazyk jednotlivých částí: Jazyk (=řeč, nikoli programovací) každé pasáže či fráze lze programově určit. Výjimku tvoří vlastní jména, odborné termíny, slova neurčitého jazykového původu a zavedené fráze nebo slova mající význam v rámci svého nejbližšího kontextu. (Úroveň AA)

#### 3.1.3 Neobvyklá slova: Je dostupný mechanismus umožňující nalezení definic slov a frází použitých neobvyklým způsobem nebo ve specifickém kontextu. To platí rovněž pro idiomy a žargon. (Úroveň AAA)

#### 3.1.4 Zkratky: Je dostupný mechanismus umožňující nalezení rozepsané formy zkratek nebo jejich definice. (Úroveň AAA)

#### 3.1.5 Úroveň čtení: Jestliže pochopení textu vyžaduje vyšší než nižší stupeň středoškolského vzdělání, je poskytnut doplňující text s vynechanými vlastními jmény a názvy nebo verze nevyžadující vyšší vzdělání než nižší stupeň středoškolského vzdělání. (Úroveň AAA)

#### 3.1.6 Výslovnost: Je dostupný mechanismus k určení specifické výslovnosti u slov, jejichž význam by v kontextu bez znalosti jejich výslovnosti byl nejednoznačný. (Úroveň AAA)

### Pravidlo 3.2 Intuitivní: Zajistěte, aby vzhled a ovládání vašich webových stránek byl intuitivní.

#### 3.2.1 Focus: Jestliže prvek získá focus, nezpůsobí to změnu kontextu. (Úroveň A)

#### 3.2.2 Při akci uživatele: Jestliže uživatel provede změnu v nastavení určité položky uživatelského rozhraní, nevyvolá to automaticky změnu kontextu nebo je na změnu předem upozorněn. (Úroveň A)

#### 3.2.3 Konzistentní navigace: Navigační mechanismy, které se opakují na stránkách v rámci webu, jsou pokaždé zobrazeny ve stejném relativním pořadí, pokud změnu zobrazení pořadí neprovede uživatel. (Úroveň AA)

#### 3.2.4 Konzistentní identifikace: U prvků se stejnou funkcí je použito jednotného způsobu jejich identifikace. (Úroveň AA)

#### 3.2.5 Vyžádané změny: Změny kontextu se provádějí pouze v důsledku akce uživatele nebo je k dispozici mechanismus umožňující potlačení těchto změn. (Úroveň AAA)

### Pravidlo 3.3 Pomoc při zadávání: Pomozte uživatelům vyvarovat se chyb nebo chyby opravit.

#### 3.3.1 Identifikace chyby: Jestliže je při zadávání automaticky zjištěna chyba, je chybná položka označena a chyba je uživateli popsána ve formě textu. (Úroveň A)

#### 3.3.2 Popisky nebo pokyny: Je-li vyžadován vstup uživatele, má uživatel k dispozici popisky nebo pokyny. (Úroveň A)

#### 3.3.3 Návrhy pro opravení chyby: Je-li při zadávání automaticky zjištěna chyba a jsou známy návrhy na její opravení, jsou návrhy prezentovány uživateli. Výjimku tvoří případ, kdy je takový postup v rozporu s bezpečností nebo účelem obsahu. (Úroveň AA)

#### 3.3.4 Předcházení chybám – právní, finanční, data: Pro webové stránky, z nichž vyplývají právní důsledky, stránky, umožňující provádět finanční transakce, stránky umožňující modifikaci nebo mazání uživatelských dat uložených v systémech pro uchovávání dat nebo pro stránky, pomocí nichž se odesílají odpovědi na testové otázky, platí alespoň jeden z následujících bodů: (Úroveň AA)

-   Zrušitelnost: Akce uživatele lze vrátit zpět.

-   Kontrola dat: Data zadaná uživatelem jsou zkontrolována na chyby a uživatel
    má možnost chyby opravit.

-   Potvrzení: Je dostupný mechanismus umožňující zkontrolování, potvrzení a
    opravení informací před dokončením zadávání.

#### 3.3.5 Nápověda: K dispozici je kontextová nápověda. (Úroveň AAA)

#### 3.3.6 Prevence chyb (celková): Pro webové stránky vyžadující po uživateli, aby vložil informace platí alespoň jeden z následujících bodů. (Úroveň AAA)

-   Zrušitelnost: Akce uživatele lze vrátit zpět.

-   Kontrola dat: Data zadaná uživatelem jsou zkontrolována na chyby a uživatel
    má možnost chyby opravit.

-   Potvrzení: Je dostupný mechanismus umožňující zkontrolování, potvrzení a
    opravení informací před dokončením zadávání.

Princip 4 Robustnost: Obsah musí být dostatečně robustní, aby mohl být spolehlivě interpretován širokou škálou přístupových zařízení včetně asistivních technologií.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Pravidlo 4.1 Kompatibilní: Snažte se o maximální kompatibilitu se současnými i budoucími přístupovými zařízeními včetně asistivních technologií.

#### 4.1.1 Syntaktická analýza: Prvky, které jsou součástí obsahu, mají při použití značkovacího jazyka definovány značky pro začátek a konec, nedochází ke křížení značek, prvky neobsahují zdvojené atributy, všechny identifikátory jsou jedinečné, s výjimkou, kdy tyto vlastnosti povoluje jejich specifikace. (Úroveň A)

Poznámka: Počáteční a koncové značky, u nichž chybí nějaký kritický znak jako
pravá hranatá závorka či uvozovky při definování hodnot atributů, nejsou
kompletní.

#### 4.1.2 Název, funkce, hodnota: U všech prvků uživatelského rozhraní zahrnující, avšak neomezující se pouze na prvky formátu a vzhledu, odkazy a prvky generované skriptem, lze název a funkce programově určit. Statusy, hodnoty nebo vlastnosti, které může nastavovat uživatel, mohou být programově nastaveny a oznámení o změnách u těchto položek je dostupné přístupovým prostředkům na straně uživatele včetně asistivních technologií. (Úroveň A)

Poznámka: Toto kritérium přístupnosti se týká hlavně těch autorů webu, kteří
vyvíjejí nebo skriptují vlastní prvky uživatelského rozhraní. Například ovládací
prvky ve standardním HTML toto kritérium již splňují, pokud se používají v
souladu s jejich specifikací.

Přístup k naplňování principů a pravidel přístupnosti
=====================================================

Výše uvedené principy a pravidla je nutno naplnit již při samotném rozmýšlení,
jakým způsobem bude obsah a informace prezentovány. To znamená, že kupříkladu,
pokud se to bude týkat prezentace informací formou internetových stránek, je
nutno na tyto principy myslet již v okamžiku, kdy se rozhoduje o systému či
platformě, na které příslušný web poběží.

Výše uvedené principy a pravidla a požadavky je tedy vhodné aplikovat:

1.  Již při přípravě projektu
2.  Při výběru platformy/systému který bude obsah spravovat a publikovat
3.  Při tvorbě designu
4.  Při tvorbě šablon a jejich automatizací a omezení
5.  Při tvorbě samotného obsahu
6.  Při zpětné kontrole přístupnosti
