---
layout: default
title: Návrh implementace § 2 a 3 ZoPDS Pojmy a uživatelé digitální služby
parent: Implementační doporučení ZoPDS
nav_order: 2
last_modified_date: 2024-04-20
grand_parent: Postupy
---

Toto je dokument Digitální a informační agentury zpracováný v rámci [Implementace povinností dle zákona o právu na digitální služby](https://archi.gov.cz/znalostni_baze:implementace_zopds?s[]=implementace%2A&s[]=z%C3%A1kona%2A&s[]=o%2A&s[]=pr%C3%A1vu%2A&s[]=na%2A&s[]=digit%C3%A1ln%C3%AD%2A)


### Vymezení pojmů
1. Uživatelem služby je fyzická osoba nebo právnická osoba, kterým je poskytována
digitální služba nebo které činí digitální úkon, a které při poskytování digitální služby nebo při
činění digitálního úkonu nemají postavení orgánu veřejné moci.
2. Digitální službou je úkon vykonávaný orgánem veřejné moci vůči uživateli služby v
rámci agendy a vedený v katalogu služeb jako úkon v elektronické podobě; za digitální službu
se považuje i úkon vykonávaný vůči uživateli služby kontaktním místem veřejné správy v
rámci agendy.
3. Digitálním úkonem je úkon vykonávaný uživatelem služby vůči orgánu veřejné moci
v rámci agendy a vedený v katalogu služeb jako úkon v elektronické podobě.
4. Katalogem služeb je část údajů vedená v základním registru agend, orgánů veřejné
moci, soukromoprávních uživatelů údajů a některých práv a povinností (dále jen “registr práv
a povinností”), které se týkají úkonů orgánů veřejné moci vykonávaných v rámci agendy vůči
subjektům, které přitom nemají postavení orgánů veřejné moci, a úkonů subjektů, které při
jejich vykonávání nemají postavení orgánů veřejné moci, vůči orgánům veřejné moci.
#### Uživatel služby
„Uživatel služby“ je klíčový pojem ZoPDS. Vymezení práv uživatelů, resp. povinností OVM
v rámci poskytování digitálních služeb je důvodem pro přijetí tohoto zákona. To vyplývá ze
samotného vymezení věcné působnosti ZoPDS v § 1, podle kterého zákon upravuje zejména
právo fyzických a právnických osob jakožto uživatelů služeb na poskytnutí digitálních služeb a
jejich právo digitální úkony a naproti tomu povinnost OVM poskytovat digitální služby a přijímat
digitální úkony.
Uživatelem služby je fyzická nebo právnická osoba, kterým je poskytována digitální služba
nebo které činí digitální úkon (k těmto pojmů viz dále). Nejde však o každou fyzickou či
právnickou osobu, ale tyto osoby nesmí být v postavení OVM. Zákon tím vylučuje, aby se jeho
ustanovení týkající se digitálních služeb a úkonů uplatnila i v komunikaci OVM ve
vrchnostenském postavení mezi sebou. Když OVM koná v postavení klienta veřejné správy
(žádá o stavební povolení, registruje vozidlo atp.), pak uživatelem služby je.

Uživatelem služby je ta osoba, která digitální úkon činí, nikoliv její zástupce, prostřednictvím
nějž je digitální úkon činěn. Uživatelem služby tak typicky nebude například advokát, který
v zastoupení svého klienta dle zmocnění doručuje prostřednictvím své datové schránky
klientovo podání vypracované a podepsané tímto advokátem. Tento závěr však může být
problematický například v případě vystavování osvědčení dle § 5 ZoPDS. V případě
automatizovaného vystavení osvědčení bezodkladně po učinění digitálního úkonu dle § 5 odst.
3 ZoPDS není ze strany OVM bez provedení obsahové kontroly podání možné identifikovat,
že digitální úkon nečiní osoba, prostřednictvím jejíž datové schránky je úkon činěn, ale
zastoupená osoba (např. zmocnitel).

Nad rámec zákonné definice je však pro poskytování digitálních služeb, resp. činění digitálních
úkonů podstatné, aby uživatel služby byl evidován v základním registru obyvatel nebo
základním registru osob. Zákon nevylučuje, a ani nemůže vylučovat, poskytování digitálních
služeb pro osoby s občanstvím jiného státu či se sídlem mimo Českou republiku. Prakticky
tyto osoby nicméně nemají v některých aspektech rovnocennou pozici s občany České
republiky a právnickými osobami se sídlem v ČR. Důvody této skutečnosti jsou identifikovány
především ve vzdálené identifikaci, a tedy využívání identifikačních prostředků dle zákona č.
250/2017 Sb., o elektronické identifikaci, a následné možnosti komunikace. Protože ač by
klient neevidovaný v základním registru obyvatel mohl učinit úkon pomocí datové zprávy či
elektronicky podepsaným dokumentem a v některých případech i na kontaktním místě veřejné
správy, je následně odstřižen od možnosti například kontrolovat stav svého podání na
samoobslužném portále.
Prostředek elektronické identifikace dle výše zmíněného zákona může vlastnit pouze ta fyzická
osoba, která je vedena v základním registru obyvatel – to nemusí být (dle chybného názvu
registru) jen obyvatel České republiky, ale i další fyzické osoby:

1. cizinci, kteří pobývají na území České republiky v rámci trvalého pobytu anebo na
základě dlouhodobého víza nebo povolení k dlouhodobému pobytu,
2. občané jiných členských států Evropské unie, občané států, které jsou vázány
mezinárodní smlouvou sjednanou s Evropským společenstvím, a občané států, které
jsou vázány smlouvou o Evropském hospodářském prostoru, a jejich rodinní
příslušníci, kteří pobývají na území České republiky v rámci trvalého pobytu nebo
kterým byl vydán doklad o přechodném pobytu na území České republiky delším než
3 měsíce,
3. cizinci, kterým byla na území České republiky udělena mezinárodní ochrana formou
azylu nebo doplňkové ochrany,
4. jiné fyzické osoby, u nichž to vyžaduje jiný právní předpis.

Pokud však fyzická osoba není vedena v základním registru obyvatel, nemusí být bez dalších
kroků možné ji vzdáleně poskytovat digitální službu, protože bez nich nemusí proběhnout její
ztotožnění. Problém není vyřešen ani nařízením (EU) č. 910/2014 ze dne 23. července 2014
o elektronické identifikaci a službách vytvářejících důvěru pro elektronické transakce na
vnitřním trhu (dále jen „eIDAS“), protože ten pro potřebu identifikace pracuje s tzv. minimálním
datasetem (jméno, příjmení, datum narození, jednoznačný identifikátor)1. Tyto údaje nestačí
na nic jiného, než identifikaci (můžeme věřit, že na druhé straně je daná osoba), ale není
možné jednoznačně provést autentizaci a autorizaci, protože i jen pro osoby obsažené
v evidenci obyvatel Česka existuje pro výše zmíněné údaje cca 30 000 víceplicit.

Každý poskytovatel služeb si může míru, po kterou je schopen akceptovat identifikaci jako
dostatečnou, může zvolit. Tedy rozhodnutí, zda je přihlašující se osoba se jménem Helmut
Schmidt, narozen 1.1.1990, tou stejnou osobou, která je pod stejnými nacionály vedená
v evidenci. Po uživateli si lze vyžádat další údaje, jako například dokumenty prokazující vazbu
s osobou vedenou v evidenci.
Veškeré situace, které pro české poskytovatele služeb poskytující služby na samoobslužném
portále mohou nastat, jsou popsány na webu archi.gov.cz.3
#### Digitální služba
Digitální službou je úkon:

1. vykonávaný OVM vůči uživateli služby,
2. vykonávaný v rámci agendy, a
3. vedený v katalogu služeb jako úkon v elektronické podobě.

Jak vyplývá i z předchozího bodu, digitální službu je možné vykonávat pouze ze strany OVM
a vůči uživateli. Musí být také vykonávaný pouze v rámci agendy OVM, tedy v rámci ucelené
oblasti působení orgánu veřejné moci [srov. § 2 písm. e) zákona č. 111/2009 Sb., o základních
registrech]. Za digitální službu se přitom považuje i úkon vykonávaný vůči uživateli služby
kontaktním místem veřejné správy v rámci agendy (k pojmu „kontaktní místo veřejné správy“
srov. § 8a a 8b zákona č. 365/2000 Sb., o informačních systémech veřejné správy).
Příkladem digitální služby je kompletně elektronicky vyřízená žádost uživatele služby o výpis
ze živnostenského rejstříku (viz důvodová zpráva ZoPDS k § 2).
#### Digitální úkon
Digitálním úkonem je podle zákonné definice:

1. úkon vykonávaný uživatelem služby vůči OVM,
2. vykonávaný v rámci agendy OVM, a
3. vedený v katalogu služeb jako úkon v elektronické podobě.

Z této definice vyplývá charakter digitálního úkonu jako určitého opaku digitální služby – tu
vykonává v rámci své agendy OVM vůči uživateli služby, naproti tomu uživatel služby vůči
OVM činí v rámci agendy tohoto OVM digitální úkon.
Typickým digitálním úkonem je například podání žádosti, nahlášení změny údajů, žádost o
výpis/výstup údajů nebo úhrada správního poplatku.
#### Katalog služeb
Katalogem služeb je:

1. část údajů vedená v registru práv a povinností,
2. tyto údaje se týkají úkonů OVM vykonávaných v rámci agendy vůči subjektům, které
přitom nemají postavení orgánů veřejné moci, a
3. úkonů subjektů, které při jejich vykonávání nemají postavení OVM, vůči OVM.
Subjekty bez postavení OVM zmíněné v zákonné definice budou v případě digitálních služeb
uživateli služeb.

Textace ZoPDS použitá pro výše uvedené zákonné definice je úzce propojena s § 51 odst. 6
písm. d) až g) zákona o základních registrech. Zatímco ZoPDS se omezuje na digitální služby
a úkony, zákon o základních registrech požaduje evidovat i ostatní, nedigitální úkony. ZoPDS
pak tyto údaje souhrnně nazývá katalogem služeb. Jinými slovy, každá agenda musí být
evidována v katalogu služeb, bez ohledu na to, zda je či není poskytována jako digitální služba.
Struktura katalogu služeb je:

1. služba veřejné správy,
2. úkon, a
3. obslužný kanál.

Služba veřejné správy se skládá z jednoho či více úkonů a každý úkon má jeden či více
obslužných kanálů. Pokud lze úkon realizovat digitálním obslužným kanálem a vykonává jej
klient (uživatel služby), jde o digitální úkon.
### Právo na digitální službu (§ 3)
§ 3
Právo na digitální službu

(1) Uživatel služby má právo využívat digitální službu a orgán veřejné moci má povinnost
poskytovat digitální službu.

(2) Práva a povinnosti podle jiných zákonů nejsou tímto zákonem dotčena.
#### Právo využívat digitální služby
Zákon zde v návaznosti na § 1 výslovně konstatuje uživatelovo právo využívat digitální služby.
Tomuto právu pak odpovídá povinnost OVM poskytovat digitální služby. Toto právo a povinnost
je nutné číst zejména v kontextu § 14 odst. 4 a odst. 5 ZoPDS. Podle odst. 4 vláda stanoví do
12 měsíců ode dne účinnosti tohoto zákona harmonogram a technické způsoby provedení
postupné digitalizace úkonů obsažených v katalogu služeb, které dosud nejsou poskytovány
jako digitální služby nebo prováděny jako digitální úkony a jejichž povaha to nevylučuje, pro
období následujících 4 let. V návaznosti na to mají ohlašovatelé agend povinnost, pokud
dosud digitalizované nejsou, zajistit digitalizaci těchto úkonů. Po uplynutí tohoto období, tedy
od 1. 2. 2025, se všechny tyto úkony poskytují též jako digitální služby nebo se umožňují
provádět jako digitální úkony.
Odstavec 5 pak zároveň stanoví, že existuje-li úkon, který není obsažen v katalogu služeb a
jehož povaha to nevylučuje, příslušný OVM jej po uplynutí 5 let od účinnosti ZoPDS poskytuje
též jako digitální službu nebo jej umožňuje provádět též jako digitální úkon, pokud jiný zákon
nestanoví jinak. To nicméně nevylučuje, aby OVM poskytoval tyto úkony též jako digitální
službu i před uplynutím 5 let od účinnosti tohoto zákona, nestanoví-li jiný zákon jinak.
Z těchto ustanovení vyplývají výjimky z povinnosti poskytovat digitální služby – povaha úkonu
vylučuje jejich poskytování jako digitální služby či jiný zákon vyloučí jejich poskytování
prostřednictvím digitální služby. Kromě toho zákona zmiňuje ještě další výjimky:

1. Škola a školské zařízení poskytují digitální službu pouze u úkonu, u kterého je
poskytnutí v digitální podobě vyznačeno v katalogu služeb.
2. Povinnost poskytovat digitální služby se nevztahuje na Národní bezpečnostní úřad při
provádění bezpečnostního řízení
3. Povinnost se nevztahuje na zpravodajské služby České republiky.
4. Územní samosprávný celek při výkonu samostatné působnosti má právo, nikoli
povinnost poskytovat digitální služby podle tohoto zákona.

Platí také, že nepodnikající fyzické osoby nemají povinnost činit digitální úkony a využívat
digitální služby (v § 14 odst. 1 ZoPDS). Musí jim být tedy dána možnost učinit úkon vůči OVM
v rámci jeho agendy i nedigitálně. 
Ustanovení tak nebrání tomu, aby zvláštní zákon stanovil
pro podnikající fyzické osoby a právnické osoby, že některá agenda bude vůči nim vykonávána
výhradně jako digitální služba. Příkladem takového ustanovení budiž § 72 odst. 6 daňového
řádu. Stejný závěr však bude možné vztáhnout i na nepodnikající fyzické osoby. Lze si tak
představit, že zvláštní zákon určí povinnost činit nějaký úkon pouze jako digitální úkon (k tomu
srov. i § 3 odst. 2 ZoPDS dále). Zákonodárce by však vzhledem k § 14 odst. 1 ZoPDS měl
velmi obezřetně zvažovat, zda v konkrétním případě prolomí ochranu fyzických osob danou
tímto ustanovením.
#### Práva a povinnosti podle jiných zákonů
Předmětné ustanovení také výslovně přiznává subsidiaritu ZoPDS svým konstatováním, že
práva a povinnosti podle jiných zákonů nejsou tímto zákonem dotčena. Zákon zde vyjadřuje
postavení ZoPDS jako obecného zákona s tím, že jiný zvláštní zákon může například odchylně
stanovovat způsob provedení digitální úkonu, že nějaký úkon je prováděn výhradně
v nedigitální podobě či naopak pouze digitálně.

