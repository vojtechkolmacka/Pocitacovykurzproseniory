# Naučím vás s počítačem – pracovní verze

Statický web pro GitHub Pages. Obsahuje 12 kapitol a 36 lekcí, vyhledávání, slovníček, kvízy, ukládání studijního pokroku v prohlížeči, nastavení čitelnosti, PWA manifest a základní offline cache.

## Funkce dostupné bez backendu
- Reklamní plocha na úvodní stránce (zatím obecná nabídka reklamního prostoru, ne aktivní kampaň konkrétního inzerenta).
- Sekce užitečných externích odkazů.
- Sekce video návodů s odkazy na vyhledávání na YouTube.
- Kniha návštěv – prozatím pouze lokální pracovní ukázka: vzkazy se ukládají v localStorage konkrétního prohlížeče a nejsou veřejně sdílené.
- TOPlist měřicí počítadlo ve vzhledu counter s ID 1844009 a informační panel 88 × 120 px (celkem, poslední týden, dnes a online) v patičce. Panel pouze zobrazuje statistiky; návštěvy zaznamenává samostatný měřicí kód.
- Administrativní pracovní stránka admin.html pro export/import studijních dat; není to zabezpečená serverová administrace.

## Omezení statického hostingu
GitHub Pages neumí sám bezpečně ukládat společné vzkazy, centrálně spravovat odkazy/reklamy ani počítat vlastní návštěvnost. TOPlist měří návštěvnost externě. Pro veřejnou knihu návštěv a centrální správu je nutný backend nebo externí služba s autentizací a pravidly přístupu.

## Nasazení
Nahrajte obsah této složky do kořene repozitáře GitHub Pages. Zachovejte soubory CNAME a původní bannery. Po nasazení otestujte mobilní i desktopové zobrazení, odkazy, TOPlist a PWA.

## Bezpečnost a soukromí
Nepřidávejte hesla ani tajné klíče do veřejných JavaScriptových souborů. Kniha návštěv v této verzi není veřejná a lokální záznamy se mohou ztratit při vymazání dat prohlížeče.
