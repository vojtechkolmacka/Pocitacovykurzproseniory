# Naučím vás s počítačem – průvodce pro seniory

Statická vzdělávací webová aplikace určená pro GitHub Pages.

## Obsah
- 12 kapitol a 36 samostatných lekcí (3 lekce v každé kapitole)
- vyhledávání v obsahu kurzu
- slovníček základních pojmů
- kontrolní otázky s okamžitým vyhodnocením
- lokální označování dokončených lekcí
- ovládání velikosti písma, vysoký kontrast a tmavý režim
- PWA manifest a service worker pro základní offline dostupnost
- zachované doménové nastavení v souboru `CNAME` a původní bannery

## Nasazení
1. Nahrajte všechny soubory a složky do kořene repozitáře.
2. V GitHubu otevřete Settings → Pages.
3. Zkontrolujte, že zdrojem je větev `main` a složka `/ (root)`.
4. Po nasazení ověřte vlastní doménu a HTTPS.

## Důležitá technická omezení
Tato verze je statická aplikace. Pokrok v lekcích se ukládá do `localStorage` konkrétního prohlížeče a nesynchronizuje se mezi zařízeními. Administrace v `admin.html` je pouze lokální pracovní pomůcka pro export/import dat; není to centrální CMS.

Pro bezpečnou administraci, společné ukládání obsahu a knihy návštěv je potřeba doplnit backend a autentizaci (například Firebase nebo Supabase) a nastavit bezpečnostní pravidla. Heslo nesmí být uložené ve veřejném JavaScriptu.

## Obsah a přesnost
Názvy nabídek Windows a mobilních systémů se mohou lišit podle verze a výrobce. Před veřejným spuštěním doporučujeme redakční kontrolu postupů na skutečných zařízeních a doplnění aktuálních fotografií/snímků obrazovky. Použité bannery jsou převzaté z původního projektu.
