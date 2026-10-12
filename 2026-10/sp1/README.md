# SP1 Kroužky
Kód žáka: IT2-24
## Tři problémy původní tabulky

1. **Data se zbytečně opakují.** Údaje o kroužku (vedoucí, den, čas, místnost, cena) jsou
   napsané na každém řádku znovu. Robotika je v tabulce čtyřikrát, Šachy třikrát. Kdyby
   se změnila cena nebo místnost, musel bych opravit každý řádek zvlášť a snadno bych
   některý zapomněl. Stejně tak se opakují žáci: Adam Novák je tam dvakrát.

2. **Stejná věc je pokaždé napsaná jinak.** Robotika je zapsaná jako „Robotika“,
   „robotika “ (s mezerou) a „ROBOTIKA“, vedoucí jako „Mgr. Horák“, „Horák“ a „Horak“,
   den jako „čt“ a „čtvrtek“. Cena je jednou číslo (600) a jednou text („450 Kč“), takže
   se s ní nedá spolehlivě počítat. Počítač bere tyhle zápisy jako různé hodnoty.

3. **Na rozumné otázky se nedá spolehlivě odpovědět.** Když se zeptám, kolik kroužků
   škola nabízí, z tabulky vyjde 12 řádků, ale skutečně jsou jen čtyři kroužky. Kdyby se
   navíc na nějaký kroužek nikdo nepřihlásil, v tabulce by vůbec nebyl. Bez ruční opravy
   nejde ani zjistit, kolik žáků chodí na Robotiku, protože je zapsaná třemi způsoby.
