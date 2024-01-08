---
layout: default
title: Návrh implementace § 6 ZoPDS Právo na nahrazení podpisu a souvisejících povinností
parent: Implementační doporučení ZoPDS
nav_order: 6
last_modified_date: 2023-10-16
grand_parent: Postupy
---
Toto je dokument Digitální a informační agentury zpracováný v rámci [Implementace povinností dle zákona o právu na digitální služby](https://archi.gov.cz/znalostni_baze:implementace_zopds?s[]=implementace%2A&s[]=z%C3%A1kona%2A&s[]=o%2A&s[]=pr%C3%A1vu%2A&s[]=na%2A&s[]=digit%C3%A1ln%C3%AD%2A)




### Obecné předpoklady úředního ověření elektronického podpisu

Pro některá právní jednání zákony vyžadují úřední ověření podpisu.
Úředním ověřením se rozumí legalizace ve smyslu § 10 zákona č. 21/2006
Sb., o ověřování shody opisu nebo kopie s listinou a o ověřování
pravosti podpisu (dále jen „zák. o ověřování"). Legalizací se na žádost
ověřuje, že žadatel listinu před ověřující osobou vlastnoručně podepsal
nebo podpis na listině uznal za vlastní.

Legalizaci podpisu podle zák. o ověřování provádí krajský úřad, obecní
úřad, újezdní úřad, držitel poštovní licence a Hospodářská komora České
republiky. Úřední ověření podpisu provádí také notář podle § 74 zákona
č. 358/1992 Sb., o notářích a jejich činnosti (notářský řád). Advokát
podle § 25a zákona č. 85/1996 Sb., o advokacii, prohlášením o pravosti
podpisu prohlašuje, že jednající osoba dokument před ním vlastnoručně
podepsala, přičemž toto prohlášení má stejné účinky jako úřední ověření
podpisu.

ZoPDS umožňuje splnit požadavek na úřední ověření podpisu také
elektronickým podpisem, a to využitím některé z těchto variant:

1.  Elektronickým dokumentem nedílně spojeným s kvalifikovaným
    elektronickým podpisem a kvalifikovaným elektronickým časovým
    razítkem osoby oprávněné provádět ověřování pravosti podpisu, která
    postupem podle jiného právního předpisu ověřila, že podepisující
    osoba dokument před ní elektronicky podepsala nebo uznala
    elektronický podpis za vlastní.

2.  Elektronicky podepsaným dokumentem nedílně spojeným se záznamem
    informačního systému veřejné správy opatřeným kvalifikovanou
    elektronickou pečetí a kvalifikovaným elektronickým časovým razítkem
    jeho správce o provedení elektronické identifikace podepisujícího
    prostřednictvím kvalifikovaného systému elektronické identifikace s
    úrovní záruky vysoká.

3.  Využitím uznávaného elektronického podpisu, pokud lze s využitím
    údajů základního registru obyvatel nebo portálu veřejné správy
    ověřit, že kvalifikovaný certifikát pro elektronický podpis, na
    jehož základě podepisující vytvořil uznávaný elektronický podpis na
    dokumentu, patří podepisujícímu.

ZoPDS se v § 6 nijak nevěnuje tomu, jakou úroveň elektronického podpisu
lze postupy dle bodu 1 a 2 ověřovat. Vzhledem k tomu se domníváme, že
podepisující osoba může elektronický dokument podepsat kteroukoliv
úrovní elektronického podpisu, včetně elektronického podpisu prostého.
Jediný požadavek na elektronický podpis upravuje § 5a odst. 3 vyhláška
č. 36/2006 Sb., o ověřování shody opisu nebo kopie s listinou a o
ověřování pravosti podpisu, podle nějž elektronický podpis umístěný v
dokumentu s elektronickým podpisem musí být viditelný, nejedná-li se o
zaručený elektronický podpis založený na certifikátu pro elektronický
podpis. Totožný požadavek vychází z § 2 odst. 4 nařízení vlády č.
317/2021 Sb. v souvislosti s prováděním ověřování pravosti podpisu
notáři. U postupu dle bodu 3 pak ZoPDS stanoví, že pro jeho využití je
třeba použít uznávaný elektronický podpis. Jednotlivé postupy rozebíráme
níže.

### Ověření osobou oprávněnou provádět ověření podpisu

Podle zák. o ověřování provádí legalizaci obecní úřad, újezdní úřad,
držitel poštovní licence a Hospodářská komora České republiky.
Legalizaci na dokumentu v elektronické podobě však neprovádí všechny
obecní úřady, ale pouze ty, které jsou kontaktními místy veřejné správy
(srov. § 5 zák. o ověřování). V souvislosti s prováděním legalizace
elektronických podpisů notáři byl novelizován notářský řád a jeho §74 a
upravuje její postup. Stejně tak byl novelizován zákon o advokacii,
podle jehož § 25a odst. 1 prohlášením o pravosti podpisu advokát
prohlašuje, že jednající osoba dokument před ním vlastnoručně podepsala
nebo elektronický podpis na dokumentu uznala za vlastní. V legislativním
procesu je aktuálně [novela zákona o
advokacii](https://odok.cz/portal/veklep/material/KORNCT9MD56I/), která
míří mimo jiné na novelizaci tohoto ustanovení zákona o advokacii.

Podepisovaný nebo podepsaný dokument má být ZoPDS nedílně spojen s
kvalifikovaným elektronickým podpisem a kvalifikovaným elektronickým
razítkem ověřující osoby. Konkrétní postup pro ověření elektronického
podpisu dle zák. o ověřování je stanoven § 5a a 5b vyhlášky č. 36/2006
Sb., o ověřování shody opisu nebo kopie s listinou a o ověřování
pravosti podpisu. Podle vyhlášky však ověřující osoba připojuje svůj
elektronický podpis a časové razítko k ověřovací doložce (srov. § 5b
odst. 3). Stejně tak připojuje notář svůj kvalifikovaný elektronický
podpis na doložku podle § 74a notářského řádu.

### Dokument nedílně spojený se záznamem informačního systému veřejné správy 

ZoPDS umožňuje také splnit požadavek úředně ověřeného podpisu dokumentem
nedílně spojeným se záznamem informačního systému veřejné správy o
provedení elektronické identifikace podepisujícího prostřednictvím
kvalifikovaného systému elektronické identifikace s úrovní záruky
vysoká. V tomto případě je tedy identifikace podepisující osoby
provedena prostřednictvím elektronické identifikace, nikoliv úřední
osobou jako v předchozím případě. Záznam informačního systému veřejné
správy musí být opatřený kvalifikovanou elektronickou pečetí a
kvalifikovaným elektronickým časovým razítkem správce informačního
systému.

Konkrétní postup a technické řešení, kterým lze tento způsob splnění
požadavku elektronického podpisu ZoPDS v souladu se zásadou technické
neutrality nijak neřeší a bude záležitostí informačního systému veřejné
správy, jaké technické řešení bude zvoleno.

### Využití údajů základního registru obyvatel nebo portálu veřejné správy

Poslední možností je využití uznávaného elektronického podpisu
podepisující osoby, pokud lze s využitím údajů základního registru
obyvatel nebo portálu veřejné správy ověřit, že kvalifikovaný certifikát
pro elektronický podpis, na jehož základě podepisující vytvořil uznávaný
elektronický podpis na dokumentu, patří podepisujícímu.

Uznávaným elektronickým podpisem je kvalifikovaný elektronický podpis a
zaručený elektronický podpis založený na kvalifikovaném certifikátu.
Rozdíl mezi těmito dvěma podpisy spočívá v tom, že pro podepisování
kvalifikovaným elektronickým podpisem je třeba mít kvalifikovaný
prostředek pro vytváření elektronických podpisů (certifikovanou čipovou
kartu či USB token), a kvalifikovaný certifikát s příznakem umístění
soukromého klíče na tomto prostředku. Pro zaručený elektronický podpis
založený na kvalifikovaném certifikátu naproti tomu není třeba mít
soukromý klíč uložený na kvalifikovaném prostředku, ale lze jej mít
uložený například na pevném disku počítače. Podepisující osobě pak stačí
kvalifikovaný certifikát pro elektronický podpis bez zmíněného příznaku.

V současné chvíli postačí, aby uživatel vložil prostřednictvím portálu
občana do registru obyvatel svůj kvalifikovaný certifikát. Bližší popis
postupu zápisu údajů o kvalifikovaném certifikátu do registru obyvatel
se nachází na [Portálu veřejné
správy](https://portal.gov.cz/rozcestniky/zapis-kvalifikovaneho-certifikatu-do-registru-obyvatel-RZC-113).

V návaznosti na tuto variantu nahrazení úředního ověření podpisu byl
novelizovaný zákon č. 111/2009 Sb., o základních registrech, a rozsah
údajů uváděných v registru obyvatel v § 18 odst. 1 tohoto zákona. Těmito
údaji jsou tak rovněž sériové číslo, vydavatele a platnost
kvalifikovaného certifikátu pro elektronický podpis.

Tento stav vyvolává nutnost pro OVM u agendy, v rámci které je pro úkon
vyžadováno úřední ověřený podpis, aby ověřoval, zda jsou údaje o daném
certifikátu zapsány do registru obyvatel. Ověření, že certifikát v
registru obyvatel je, však může být pro některé OVM problematické.

### Ověření na základě zápisu údajů o čísle dokladu do kvalifikovaného certifikátu pro elektronický podpis

Výkladem ustanovení § 6 odst. 2 ZoPDS lze také dojít k dalšímu řešení,
které spočívá v tom, že pro dosažení právního účinku úředně ověřeného
podpisu dle § 6 odst. 2 zákona č. 12/2020 Sb., není nezbytně nutné, aby
údaje o kvalifikovaném certifikátu pro el. podpis musely být evidovány v
registru obyvatel, ale naopak pomocí údajů o podepisující osobě
uvedených v kvalifikovaném certifikátu pro el. podpis, nalézt a
ztotožnit tuto podepisující osobu (na straně ověřovatele uznávaného
elektronického podpisu) v registru obyvatel, a to s využitím údajů o
čísle a typu dokladu. DIA poskytla kvalifikovaným poskytovatelům služeb
vytvářejících důvěru návrh doporučení, jak údaje o čísle a typu dokladu
do kvalifikovaného certifikátu pro elektronický podpis zapisovat.
V současné době probíhá připomínkování tohoto návrhu.

### Plná moc pro právní jednání dle § 441 odst. 2 poslední věty občanského zákoníku

Z posledního odstavce rozebíraného ustanovení vyplývá, že pro plnou moc
k právnímu jednání, pro které je vyžadována forma veřejné listiny, lze
použít ověření elektronicky podepsaného dokumentu pouze při jeho ověření
osobou oprávněnou provádět legalizaci, resp. advokátem.

