---
layout: default
title: "WCAG 2: Kontrolní seznam přístupnosti"
description: "Český kontrolní seznam přístupnosti obsahu podle standardu WCAG. Obsahuje podrobné kroky, díky kterým si může správce obsahu zkontrolovat zda a jak moc je v souladu s principy a pravidly WCAG."
nav_order: 8
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

Tento dokument obsahuje kontrolní seznam, který pomáhá správcům obsahu při
samostatné kontrole dodržování základních principů a pravidel přístupnosti
informací. Je určen pro to, aby s jeho pomocí postupně krok za krokem byl
schopen každý správně zadat požadavky na přístupnost a potom si je také ověřit,
a především si zkontrolovat jejich naplnění.

Použití tohoto dokumentu
------------------------

Tento dokument obsahuje rozpad jednotlivých principů a pravidel mezinárodního
standardu Web content accessibility guidelines (WCAG) do snadno ověřitelných
kroků. Obsahuje tak kontrolní seznam, kde krok za krokem může kdokoliv ověřit
soulad s pravidly přístupnosti u daného obsahu. Lze ho použít jak při formulaci
požadavků na přístupnost ve stádiu tvorby systému, který bude obsah prezentovat,
tak také u kontroly dodržení přístupnosti jednotlivého obsahu, ať už se to týká
celých webových stránek, nebo třeba jenom jedné stránky s určitými informacemi.

Lze jej využít také jako základní souhrn znalostí o potřebách přístupnosti na
konkrétní úrovni, tedy o tom, co a jak se má konkrétně dělat, aby byl obsah
rámcově přístupný.

Popis mezinárodního standardu WCAG
==================================

Standard Web content accessibility guidelines (WCAG 2)
------------------------------------------------------

Pro stanovení a sjednocení konkrétních technických principů a pravidel pro
přístupnost informací pro osoby se zdravotním postižením zejména u obsahu
internetových stránek a aplikací, byl vytvořen mezinárodní Standard Web content
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

Kontrolní seznam standardu WCAG 2
=================================

Níže je podrobný krokový kontrolní seznam sloužící k ověření naplnění principů a
pravidel přístupnosti podle standardu WCAG.

Princip 1: Vnímatelnost – Informace a součásti uživatelských rozhraní musí být prezentovány tak, aby je uživatelé byli schopni vnímat
-------------------------------------------------------------------------------------------------------------------------------------

**Obsah webu je vnímatelný všemi smysly – zrakem, sluchem a/nebo hmatem**

### Pravidlo 1.1 Textové alternativy: Každý netextový obsah má definovánu textovou alternativu.

#### 1.1.1 Netextový obsah (Úroveň A)

-   Všechny obrázky, obrázková formulářová tlačítka a části obrázkových map mají
    relevantní textovou alternativu.

-   Obrázky, které nejsou obsahově významné, slouží jako dekorace nebo nesou
    obsah, který už je obsažen v textu, mají atribut alt prázdný (alt="") nebo
    jsou schovány na pozadí pomocí CSS. Všechny obrázky, které slouží jako
    odkazy, mají alternativní textový popisek, který vystihuje cíl odkazu.

-   Ekvivalentní alternativy ke komplexním obrázkům jsou součástí kontextu, v
    němž jsou obrázky zobrazeny, nebo jsou na samostatné stránce (na niž vede
    odkaz nebo je na ni odkázáno v atributu longdesc).

-   Formulářová tlačítka mají výstižné popisky.

-   Formulářové prvky mají řádně přiřazeny textové popisky pomocí značky label,
    nebo, pokud nelze použít label, jsou popisky definovány v atributu title.

-   Vložené multimediální prvky jsou identifikovány prostřednictvím přístupné
    textové alternativy.

-   Rámce mají definovány výstižné titulky.

### Pravidlo 1.2 Multimediální prvky závisející na čase: Multimediální prvky závisející na čase opatřete alternativami.

POZNÁMKA:Pokud je audio nebo video alternativou k obsahu webu (například audio
verze nebo verze ve znakovém jazyce), potom web samotný slouží jako alternativa.

#### 1.2.1 Pouze audio a pouze video (předtočené) (Úroveň A)

-   Pro předtočené audio, prezentované na webu (podcasty, MP3 soubory) je
    poskytnut výstižný textový přepis.

-   Předtočené video nebo video prezentované na webu je opatřeno textovým nebo
    audio popisem (například video, které nemá audio stopu).

#### 1.2.2 Titulky (předtočené) (Úroveň A)

-   Předtočené video nebo video prezentované na webu (video na YouTube, atp.) je
    opatřeno synchronizovanými titulky.

#### 1.2.3 Audio popis nebo alternativa pro multimediální prvek (předtočené) (Úroveň A)

-   Předtočené video nebo video prezentované na webu je opatřeno textovým
    přepisem NEBO audio popisem obsahu videa.

#### 1.2.4 Titulky (živě) (Úroveň AA)

-   Synchronizované titulky jsou poskytnuty pro všechna živá multimedia, která
    obsahují audio (vysílání audio záznamů, podcasty, videokonference, Flash
    animace).

#### 1.2.5 Audiopopis (předtočený) (Úroveň AA)

-   Audio popisy jsou poskytnuty pro veškerý video obsah. Poznámka: Požaduje se
    pouze v případě, kdy video obsahuje vizuální informace, které nemají
    alternativu v hlavní zvukové stopě.

#### 1.2.6 Znakový jazyk (předtočené) (Úroveň AAA)

-   Video ve znakovém jazyku je poskytnuto jako alternativa k jakémukoliv
    multimediálnímu obsahu, který obsahuje audio.

#### 1.2.7 Rozšířený audiopopis (předtočené) (Úroveň AAA)

-   Pokud k video záznamu nelze přidat audio stopu s audio popisem kvůli
    časování (například primární audio stopa neobsahuje žádná tichá místa), je k
    dispozici alternativní verze videa s tichými místy v audio stopě, které
    umožňuje přidání audio stopy s audio popisem.

#### 1.2.8 Alternativa pro multimediální prvky (předtočené) (Úroveň AAA)

-   Pro všechny předtočené multimediální prvky, které obsahují video stopu, je
    poskytnut popisný přepis textu.

#### 1.2.9 Pouze audio (živě) (Úroveň AAA)

-   Pro veškerý živý obsah, který obsahuje audio, je poskytnut popisný textový
    přepis (například přepis živého audia).

### Pravidlo 1.3 Přizpůsobitelné: Vytvořte obsah, který lze prezentovat více způsoby (např. zjednodušený vzhled), aniž by přitom došlo ke ztrátě informací či narušení struktury.

#### 1.3.1 Informace a vzájemné vztahy (Úroveň A)

-   Sémantické značky jsou použity pro nadpisy (h1), seznamy (ul,ol,li),
    zdůrazněný nebo speciální text (například strong, code, abbr, blockquote),
    atd. Sémantické značky jsou použity v souladu se specifikací.

-   Tabulky jsou použity pro data. V případech, kdy je to potřeba, jsou buňky
    tabulky svázány s buňkami záhlaví, je vyznačen nadpis tabulky (caption) a
    popis toho, k čemu tabulka slouží (summary).

-   Formulářové prvky mají přiřazené relevantní popisky. Související formulářové
    prvky jsou seskupeny pomocí značek fieldset a legend.

#### 1.3.2 Srozumitelné pořadí (Úroveň A)

-   Pořadí při čtení a navigaci (určeno pořadím kódu) je logické a intuitivní.

#### 1.3.3 Vlastnosti na základě smyslového vjemu (Úroveň A)

-   Instrukce nejsou závislé na tvaru, velikosti nebo vizuálním umístění prvku
    (např. „Pro pokračování klikněte na čtvercovou ikonu." nebo Instrukce jsou v
    pravém sloupci.)

-   Instrukce nejsou závislé jen na zvuku (například „Pípání znamená, že můžete
    pokračovat.")

### Pravidlo 1.4 Rozlišitelné: Usnadněte uživatelům slyšet a vidět obsah včetně odlišení popředí od pozadí.

#### 1.4.1 Používání barev (Úroveň A)

-   Barva není použita jako jediný způsob pro rozlišení vizuálních prvků nebo
    sdělení informace.

-   Odkazy jsou odlišitelné od okolního textu. Pokud jsou odkazy odlišeny pouze
    barvou, je kontrastní poměr mezi odkazem a okolním textem alespoň 3:1 a
    další způsob odlišení (například podtržení) je poskytnut ve chvíli, kdy
    uživatel nad odkaz přemístí kurzor myši nebo se na něj přesune z klávesnice.

#### 1.4.2 Ovládání zvuku (Úroveň A)

-   Pro audio, které hraje na stránce déle než 3 sekundy, je poskytnut
    mechanismus k jeho zastavení, pozastavení, úplnému vypnutí nebo regulaci
    hlasitosti.

#### 1.4.3 Minimální kontrast (Úroveň AA)

-   Texty a texty ve formě obrázku mají kontrastní poměr alespoň 4,5:1.

-   Texty psané velkým fontem (větší jak 18 bodů u normálního písma nebo 14 bodů
    u tučného písma) mají kontrastní poměr alespoň 3:1.

#### 1.4.4 Změna velikosti textu (Úroveň AA)

-   Stránka je čitelná a funkční i při dvojnásobném zvětšení velikosti písma.

#### 1.4.5 Text ve formě obrázku (Úroveň AA)

-   Text není prezentován ve formě obrázku, pokud lze stejného vizuálního efektu
    docílit pouze pomocí textu.

#### 1.4.6 Zvýšený kontrast (Úroveň AAA)

-   Texty a texty ve formě obrázku mají kontrastní poměr alespoň 7:1.

-   Texty psané velkým fontem (větší jak 18 bodů u normálního písma nebo 14 bodů
    u tučného písma) mají kontrastní poměr alespoň 3:1.

#### 1.4.7 Tlumený nebo žádný podkresový zvuk (Úroveň AAA)

-   Aby byla řeč srozumitelná, neobsahuje audio záznam mluveného slova žádný
    podkresový zvuk nebo je podkresový zvuk jen velmi slabý.

#### 1.4.8 Vizuální znázornění (Úroveň AAA)

-   Bloky textu delší než jedna věta

    -   nejsou širší než 80 znaků.

    -   nejsou zarovnány do bloku.

    -   mají adekvátní řádkování (nejméně 1/2 výšky písma) a mezery mezi
        odstavci (1,5 násobek výšky řádku).

    -   mají definovánu barvu popředí a pozadí. Barvy mohou být definovány buď
        pro specifické prvky na stránce nebo pro stránku jako celek pomocí CSS
        (tím pádem převezmou tyto barvy i všechny ostatní prvky).

    -   nevyžadují horizontální scrollování, když je text zvětšen na
        dvojnásobek.

#### 1.4.9 Text ve formě obrázku (bez výjimek) (Úroveň AAA)

-   Text ve formě obrázku je použit pouze pro dekorační účely (obrázky nenesou
    žádnou informační hodnotu) NEBO v případě, kdy informace nelze prezentovat
    jen v textové podobě

Princip 2: Ovladatelnost – Všechny součásti uživatelského rozhraní a všechny navigační prvky musí být ovladatelné
-----------------------------------------------------------------------------------------------------------------

**Formulářová rozhraní, ovládací prvky a navigace jsou ovladatelné**

### Pravidlo 2.1 Přístupnost z klávesnice: Zajistěte, aby všechny funkce byly dostupné z klávesnice.

#### 2.1.1 Klávesnice (Úroveň A)

-   Veškeré funkce a úkony na stránce jsou přístupné z klávesnice. Výjimkou jsou
    situace, kdy tento úkon nelze z klávesnice provést (například psaní a
    kreslení rukou).

-   Klávesové zkratky a horké klávesy na stránce (horkým klávesám bychom se měli
    spíše vyhýbat) nejsou v konfliktu s existujícími klávesovými zkratkami
    prohlížeče a asistivní technologie

#### 2.1.2 Žádná past na klávesy (Úroveň A)

-   Při procházení stránky pomocí klávesnice nezůstane kurzor zablokován na
    jednom prvku. Uživatel se může pomocí klávesnice přesunout na a z každého
    prvku, na nějž se lze z klávesnice dostat.

#### 2.1.3 Klávesnice (bez vyjímek) (Úroveň AAA)

-   Veškeré úkony a funkce na stránce jsou dostupné z klávesnice.

### Pravidlo 2.2 Dostatek času: Poskytněte uživateli dostatek času k přečtení obsahu a práci s ním.

#### 2.2.1 Nastavitelné časování (Úroveň A)

-   Pokud je na stránce definován časový limit, uživatel má možnost jej vypnout,
    upravit nebo prodloužit. Tento požadavek se netýká událostí, přímo
    závisejících na čase (například aukce), nebo událostí, u nichž je časový
    limit delší než 20 hodin.

#### 2.2.2 Pauza, Stop, Skrýt (úroveň A)

-   Automatický pohyb, blikání nebo posouvání obsahu, které trvá déle než 3
    sekundy, může uživatel pozastavit, zastavit nebo skrýt. Pohyb, blikání nebo
    posouvání obsahu může být použito k upoutání pozornosti či zvýraznění
    obsahu, pokud trvá kratší dobu, než 3 sekundy.

-   Automaticky obnovovaný obsah (například automatické přesměrování nebo
    obnovení stránky; pole, obnovované přes AJAX; výstražné upozornění, atp.)
    může uživatel pozastavit, zastavit nebo skrýt nebo manuálně upravit časování
    těchto událostí.

#### 2.2.3 Žádné časování (úroveň AAA)

-   Pro obsah nebo funkcionalitu stránky není stanoven žádný časový limit nebo
    omezení.

#### 2.2.4 Přerušení (úroveň AAA)

-   Přerušení (hlášky, aktualizace obsahu, atp.) mohu být odloženy nebo
    potlačeny uživatelem.

#### 2.2.5 Aktualizace zabezpečeného obsahu (úroveň AAA)

-   Pokud vyprší přihlášení, uživatel se může znovu přihlásit a pokračovat v
    činnosti bez ztráty dat.

### Pravidlo 2.3 Záchvaty: Vynechte z prezentace takové prvky, u nichž je známo, že mohou vyvolat záchvat.

#### 2.3.1 Tři záblesky nebo podprahové blikání (úroveň A)

-   Žádný obsah stránky nebliká více než třikrát za sekundu, s výjimkou situace,
    kdy blikající obsah je dostatečně malý, záblesky mají nízký kontrast a
    neobsahují příliš mnoho červené barvy.

#### 2.3.2 Tři záblesky (úroveň AAA)

-   Žádný obsah stránky nebliká více než třikrát za sekundu.

### Pravidlo 2.4 Snadná navigace: Usnadněte uživatelům navigaci, hledání konkrétního obsahu a určování aktuální pozice.

#### 2.4.1 Přeskoč bloky (úroveň A)

-   K dispozici je odkaz, umožňujíci přeskočit navigaci a další prvky stránky,
    které se opakují se na každé stránce.

-   Vhodné strukturování stránky pomocí nadpisů může být považováno za
    dostatečnou techniku místo odkazu Přejít na hlavní obsah. Je třeba míti na
    paměti, že navigace po nadpisech není podporována ve všech prohlížečích.

-   Pokud stránka je tvořena pomocí rámů a rámy jsou řádně opatřeny titulky
    (atribut title), jedná se o dostatečnou techniku, umožňující přeskočit
    jednotlivé rámy.

#### 2.4.2 Každá stránka má titulek (úroveň A)

-   Webová stránka má popisný a výstižný titulek.

#### 2.4.3 Pořadí procházení prvků (úroveň A)

-   Pořadí procházení odkazů, formulářových prvků, atp. je logické a intuitivní.

#### 2.4.4 Účel odkazu v kontextu (úroveň A)

-   Účel každého odkazu (nebo formulářového obrázkového tlačítka nebo části
    obrázkové klikací mapy) může být určen ze samotného textu odkazu, nebo z
    textu odkazu a jeho kontextu (odstavce, položky seznamu, buňky tabulky nebo
    záhlaví tabulky).

-   Odkazy (nebo formulářová obrázková tlačítka), které mají stejný text, ale
    vedou na různá místa, jsou snadno odlišitelné.

#### 2.4.5 Více způsobů (úroveň AA)

-   Další webové stránky v rámci webové prezentace lze nalézt nejméně dvěma
    různými způsoby – seznam souvisejících stránek, obsah, mapa webu,
    vyhledávání nebo seznam všech stránek webu.

#### 2.4.6 Nadpisy a popisky (úroveň AA)

-   Nadpisy stránek a popisky formulářových prvků jsou výstižné. Texty nadpisů
    (například Detaily) nebo popisků (například Jméno) nejsou duplikovány, pokud
    struktura obsahu neposkytuje adekvátní způsob, jak je rozlišit.

#### 2.4.7 Viditelný focus (úroveň AA)

-   Ukazatel focusu při ovládání stránky z klávesnice je viditelný (například
    pokud prochází uživatel stránku pomocí tabulátoru, ví, kde je).

#### 2.4.8 Aktuální pozice (úroveň AAA)

-   Pokud je webová stránka součást sekvence stránek nebo součást webové
    prezentace, ke k dipozici indikátor pozice stránky, například
    prostřednictvím drobečkové navigace nebo specifikováním konkrétního kroku v
    sekvenci (například Krok 2 z 5 – Adresa dodání).

#### 2.4.9 Účel odkazu (pouze z textu odkazu) (úroveň AAA)

-   Účel každého odkazu (nebo obrázkového formulářového tlačítka nebo části
    obrázkové klikací mapy) je zřejmý ze samotného textu odkazu.

-   Odkazy nebo obrázková formulářová tlačítka, která mají stejný text, vedou na
    stejná místa.

#### 2.4.10 Záhlaví jednotlivých částí (úroveň AAA)

-   Kromě toho, že text je strukturován sám o sobě, jsou jednotlivé části
    obsahu, u nichž je to vhodné, uvozeny nadpisy.

Princip 3: Srozumitelnost – Informace a ovládání uživatelského rozhraní musí být srozumitelné
---------------------------------------------------------------------------------------------

**Informace a ovládání uživatelského rozhraní musí být srozumitelné**

### Pravidlo 3.1 Čitelné: Ujistěte se, že textový obsah je čitelný a srozumitelný.

#### 3.1.1 Jazyk stránky (úroveň A)

-   Jazyk stránky je určen pomocí HTML atributu lang (např. html lang=“en”).

#### 3.1.2 Jazyk jednotlivých částí (úroveň AA)

-   Pokud je to vhodné, je jazyk částí obsahu stránky v jiném jazyce určen např.
    pomocí atributu lang (blockquote lang=“es”).

#### 3.1.3 Neobvyklá slova (Úroveň AAA)

-   Slova, která mohou být nejednoznačná či neznámá, nebo která jsou použita
    specifickým způsobem, blíže určuje sousedící text, definiční seznam,
    slovníček pojmů či jiná vhodná metoda.

#### 3.1.4 Zkratky (úroveň AAA)

-   Zkratky jsou při prvním použití rozepsány, vysvětleny pomocí elementu abbr,
    odkazu na definici či slovníček. Poznámka: WCAG 2.0 neuvádí žádné výjimky
    pro běžně srozumitelné zkratky (např. HTML na webu o web designu musí být
    vždy rozepsáno).

#### 3.1.5 Úroveň čtení (úroveň AAA)

-   Pro obsah, který je složitější, než by jej mohl smysluplně číst člověk
    přibližně devíti letech základního vzdělání, je poskytnuta srozumitelnější
    alternativa.

#### 3.1.6 Výslovnost (úroveň AAA)

-   Jestliže výslovnost slova je pro porozumění tomuto slovu zásadní, je
    stanovena ihned za slovem nebo prostřednictvím odkazu či slovníčku.

### Pravidlo 3.2 Intuitivní: Ujistěte se, že vzhled a ovládání vašich stránek je intuitivní.

#### 3.2.1 Focus (Úroveň A)

-   Pokud prvek stránky obdrží focus, nemá to za následek podstatnou změnu
    stránky, zobrazení vyskakovacího okna, dodatečnou změnu focusu klávesnice
    nebo jinou další změnu, která by mohla uživatele zmást či dezorientovat.

#### 3.2.2 Při akci uživatele (úroveň A)

-   Pokud uživatel zadává informace nebo pracuje s ovládacím prvkem, nemá to za
    následek podstatnou změnu stránky, zobrazení vyskakovacího okna, dodatečnou
    změnu focusu klávesnice nebo jinou další změnu, která by mohla uživatele
    zmást či desorientovat, ledaže by uživatel byl o této akci předem
    informován.

#### 3.2.3 Konzistentní navigace (úroveň AA)

-   Pořadí navigačních odkazů, opakující se na webových stránkách v rámci webové
    prezentace, se na jednotlivých stránkách nemění.

#### 3.2.4 Konzistentní identifikace (úroveň AA)

-   Prvky, které mají stejnou funkčnost na více webových stránkách v rámci
    webové prezentace, jsou použity konzistentním způsobem. Například
    vyhledávací políčko na horním okraji stránky by vždy mělo být označeno
    stejným způsobem.

#### 3.2.5 Vyžádané změny (úroveň AAA)

-   Podstatné změny stránky, zobrazení vyskakovacího okna, nekontrolovaná změna
    focusu klávesnice nebo jiná další změna, která by mohla uživatele zmást či
    dezorientovat, pokud proběhne bez jeho vědomí, musí být iniciována
    uživatelem. Případně je uživateli poskytnuta možnost takové změny zakázat.

### Pravidlo 3.3 Pomoc při zadávání: Pomozte uživatelům vyvarovat se chyb nebo chyby opravit.

#### 3.3.1 Identifikace chyby (úroveň A)

-   Informace o povinných položkách formulářů nebo specifické požadavky na
    formát zadání, hodnotu či délku vstupu jsou uvedeny v popisku prvku (nebo –
    pokud popisek není určen – v atributu title).

-   Pokud je použito validování formulářů, tipy a chybová hlášení (na straně
    klienta či serveru) upozorňují uživatele na chyby vhodným, intuitivním a
    přístupným způsobem. Chyba je jasně identifikovatelná, je zajištěný rychlý
    přístup k problematickému prvku a uživatel je schopen lehce chybu opravit a
    formulář znovu odeslat.

#### 3.3.2 Popisky nebo pokyny (úroveň A)

-   Dostačující popisky, tipy a pokyny pro povinné prvky dialogu jsou zajištěny
    skrze pokyny, příklady, řádně umístěné popisky či legendy z prvku fieldset.

#### 3.3.3 Návrhy pro opravení chyby (úroveň AA)

-   Pokud je detekována chyba na vstupu (například prostřednictvím kontroly na
    straně klienta či serveru), je nápověda pro opravení chyby poskytnuta z
    hlediska času a přístupnosti vhodné podobě.

#### 3.3.4 Předcházení chybám (Právní, finanční, data) (úroveň AA)

-   Pokud uživatel může změnit nebo smazat právní či finanční data nebo výsledky
    testů, lze tyto změny/smazání vrátit zpátky, ověřit nebo potvrdit.

#### 3.3.5 Nápověda (úroveň AAA)

-   Pokud uživatel může odeslat, změnit nebo smazat informaci, lze tuto akci
    vrátit zpátky, ověřit nebo potvrdit.

#### 3.3.6 Prevence chyb (celková) (úroveň AAA)

-   Pokud uživatel může odeslat informace, je možné tuto akci vrátit, ověřit
    nebo potvrdit.

Princip 4: Robustnost – Obsah musí být dostatečně robustní, aby mohl být spolehlivě interpretován širokou škálou přístupových zařízení včetně asistivních technologií
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Obsah musí být dostatečně robustní, aby mohl být spolehlivě interpretován
širokou škálou přístupových zařízení včetně asistivních technologií**

### Pravidlo 4.1 Kompatibilní: Snažte se o maximální kompatibilitu se současnými i budoucími přístupovými zařízeními včetně asistivních technologií.

#### 4.1.1 Syntaktická analýza (úroveň A)

-   HTML/XHTML kód neobsahuje podstatné chyby. Ke kontrole použijte
    http://validator.w3.org/

#### 4.1.2 Název, funkce, hodnota (úroveň A)

-   Značkování je použito s ohledem na přístupnost. Kód odpovídá HTML/XHTML
    specifikaci a formuláře, popisky formulářových prvků, titulky rámců, atp.
    jsou použity korektně.
     
# Principy kontroly souladu se standardem WCAG a správné přístupnosti

Pro autory webových stránek a jejich obsahu je nanejvýš vhodné si osvojit jako
standardní postup i sebekontrolu souladu jejich obsahu s výše uvedenými principy
a pravidly WCAG 2, k čemuž mohou využít výše uvedené kroky kontrolního seznamu.
V praxi lze využít některé nástroje pro automatickou kontrolu souladu obsahu,
nicméně jejich využití je omezeno pouze na schopnost automatizovaně posoudit,
zda došlo k striktnímu souladu, či ne. Kupříkladu u kontrastů lze posoudit míru
kontrastu, to ovšem nesouvisí nijak se samotnou čitelností textu.

Doporučuje se tedy kromě automatizovaného prověření pomocí nástrojů absolvovat i
testování reálnými uživateli se zdravotním postižením.
