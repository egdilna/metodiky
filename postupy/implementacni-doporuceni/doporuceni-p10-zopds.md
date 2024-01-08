---
layout: default
title: Návrh implementace § 10 ZoPDS Právo na zápis kontaktního údaje a souvisejících povinností 
parent: Implementační doporučení ZoPDS
nav_order: 10
last_modified_date: 2024-01-08
grand_parent: Postupy
---

Toto je dokument Digitální a informační agentury zpracováný v rámci [Implementace povinností dle zákona o právu na digitální služby](https://archi.gov.cz/znalostni_baze:implementace_zopds?s[]=implementace%2A&s[]=z%C3%A1kona%2A&s[]=o%2A&s[]=pr%C3%A1vu%2A&s[]=na%2A&s[]=digit%C3%A1ln%C3%AD%2A)
**§ 10**

**Právo na zápis kontaktního údaje**

*(1) Uživatel služby má právo na zápis kontaktního údaje o elektronické adrese nebo telefonním čísle (dále jen „kontaktní údaj“) do základního registru právnických osob, podnikajících fyzických osob a orgánů veřejné moci nebo do registru obyvatel pro zasílání informací podle tohoto zákona a pro zasílání dalších informací souvisejících s poskytováním digitální služby, jejichž okruh si vybere.*

*(2) Právo na zápis kontaktního údaje uplatní uživatel služby u Agentury. Agentura zveřejní elektronický formulář k zápisu kontaktního údaje na portálu veřejné správy a zřídí službu pro zasílání informací na kontaktní údaje.*

### Obecná východiska

Uživatel služby má právo zapsat údaje o telefonním čísle a e-mailové adrese (dále „kontaktní údaje“) do registru obyvatel a registru osob, pokud je v daných registrech veden. Na tyto kontaktní údaje jsou následně zasílány informace podle ZoPDS (více k tomu § 11) a další informace. Uživatel služby si okruh zasílaných informací může upravit. Zápis kontaktních údajů se provádí prostřednictvím portálu veřejné správy. DIA implementuje službu pro zasílání notifikací.

### Zápis kontaktních údajů

Zápis kontaktních údajů se provádí na portálu veřejné správy. Na Portálu občana je zveřejněn elektronický formulář pro zápis do registru obyvatel i registru osob. Podrobné informace jsou uvedeny v příslušné službě [Zápis kontaktních údajů do základních registrů](https://gov.cz/sluzby-vs/S30521).

Kontaktní údaje jsou po zapsání součástí příslušného registru. Nejde však o referenční údaje. Ke kontaktním údajům má přístup jakýkoli orgán veřejné moci, který už využívá údaje z daného registru (více k tomu § 18 odst. 6 zákona č. 111/2009 Sb., o základních registrech).

### Volba okruhu notifikací

Volba okruhu notifikací je taktéž na portálu veřejné správy. V nastavení kontaktních údajů lze notifikace nastavovat zvlášť pro telefon (SMS) a e-mail. Aktuálně jsou volby:

-   oznámení
-   marketingová sdělení
-   změny v základních registrech
-   konec platnosti dokladů

Obrázek 1: Ukázka nastavení notifikací v Portálu občana

![Obsah obrázku text, snímek obrazovky, Písmo Popis byl vytvořen automaticky](media/dec2fef10d5ec85ea5a999ce6f9fc51f.png)

### Zasílání notifikací

Portál občana vystavuje na ISSS notifikační službu pro AIS od roku 2021. Pokud chce AIS o něčem vyrozumět osoby, které např. vede ve své evidenci, a tuto službu k tomu využít, musí sestavit XML žádosti, které obsahuje veškeré parametry, aby mohl Portál občana provést vyrozumění uživatele. Vyplněním jednotlivých elementů je následně definováno, jaké kanály mají být využity pro předání upozornění (e-mail, SMS nebo zobrazení v Portálu občana).

Uživatel sám však může nastavením svých upozornění v Portálu občana jednotlivé kanály zakazovat nebo povolovat. Je tedy možné, aby upozornění uživateli došla více kanály současně nebo mu nepřišla žádným kanálem. Samotné vyrozumění zajišťuje Portál občana.

Notifikace je možné poskytovat ve více jazykových mutacích. Uživateli je předáváno upozornění dle jeho aktuálního nastavení jazyka v Portálu občana. Pokud AIS zasílající upozornění nevloží do volání jazykovou mutaci odpovídající uživatelovu nastavení, je upozornění předáno v českém jazyce.
