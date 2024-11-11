RadekMocek/tulpresentation
==========================
Upravená verze tulpresentation.cls od Ing. Jana Koprnického, Ph.D. (http://pub.mti.tul.cz/~jan.koprnicky/), kde:

Ž1 * Úvodní a finální snímek se nepočítají do celkového počtu snímků

Ž1 * Finální snímek neobsahuje jméno autora, e-mail atd.; pouze „Děkuji za pozornost“

Ž1 * Styl odrážek u `enumerate` jsou barevná čísla, nikoliv bílá čísla v barevném kruhu

Ž1 * Nový příkaz `\subheader{...}` pro barevný podnadpis

Ž2 * Výchozí poměr stran je 4:3; na 16:9 lze přepnout přidáním volby `widescreen`
     (např. `\documentclass[FM,widescreen]{tulpresentation}`)

Ž2 * Nový příkaz `\titlesub{...}{...}{...}{...}` pro jednodušší vyplnění 4 informačních řádků na úvodním snímku

Ž2 * Nové příkazy `\itemChO` a `itemChX` pro odrážky ve stylu (ne)zaškrtnutého pole

Předpoklad úspěšného spuštění
=============================
Je potřeba mít v OS nainstalovaná tato písma:
* TULMono-Bold.otf – najdeme např. v originálním repozitáři: https://www.overleaf.com/read/hrbxyzcbwcvh
* Inter – stahovat výhradně zde: https://rsms.me/inter/download/

Příklady použití
================
https://github.com/RadekMocek/BP/blob/main/Slideshow/BS/presentation.tex
https://github.com/RadekMocek/BP/blob/main/Slideshow/Final/presentation.tex

Historie
========
Verze Ž2 – listopad 2024
Verze Ž1 – červen 2024

===============================================
Následuje originální readme (licence přetrvává)
===============================================

Styl pro LaTeX beamer umožňující sazbu prezentací podle vizuálního stylu Technické
univerzity v Liberci. Nastavení používá zavedené definice z třídy tulthesis.cls P. Satrapy (http://www.nti.tul.cz/~satrapa/vyuka/latex-tul/)

Návod k instalaci a použití najdete v souboru manual-tulpresentation.tex 

Odkaz na v overleafu zprovozněnou verzi lze nalézt zde:
https://www.fm.tul.cz/personal/jan.koprnicky

Licence
=======
Dílo je vydáno pod licencí Creative Commons CC BY. Můžete je
rozmnožovat a distribuovat, remixovat, změnit a vyjít z původního díla
pro jakýkoliv účel, a to i komerční.

Historie
========
Verze 2.1 - únor 2023
oprava chybné velikosti symbolu

Verze 2.0 - únor 2023