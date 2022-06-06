# Functional specification
## Kalkulačka

Verze 1.0  
Adam Majer  
6. Června. 2022

Obsah
================
* 1 [Úvod](#1-úvod)
   * 1.1 [Účel](#11-účel)
   * 1.2 [Konvence dokumentu](#12-konvence-dokument)
   * 1.3 [Pro koho je dokument určený](#13-pro-koho-je-dokument-určený)
   * 1.4 [Další informace](#14-další-informace)
   * 1.5 [Odkazy na ostatní dokumenty](#16-odkazy-na-ostatní-dokumenty)
* 2 [Scénář](#2-scénář)
   * 2.1 [Všechny reálné způsoby použití](#21-všechny-reálné-způsoby-použití)
   * 2.2 [Typy uživatelských rolí "personas"](#22-typy-uživatelských-rolí-"personas")
   * 2.3 [Detaily, motivace, "živé" příklady](#23-detaily,-motivace,-"živé"-příklady)
   * 2.4 [Vymezení rozsahu - co v sw NEbude](#24Vymezení-rozsahu---co-v-sw-NEbude)
   * 2.5 [Na co se nebude klást důraz](#25-Na-co-se-nebude-klást-důraz)
* 3 [Celková hrubá architektura](#3-Celková-hrubá-architektura)
   * 3.1 [Pracovní tok](#31-pracovní-tok)
   * 3.2 [Hlavní moduly](#32-hlavní-moduly)
   * 3.3 [Všechny detaily: obrazovky, okna, tisky, chybové zprávy, logování](#33-Všechny-detaily:-obrazovky,-okna,-tisky,-chybové-zprávy,-logování)
   * 3.4 [Všechny možné toky programu a jejich projevy](#34-Všechny--možnétoky-programu-a-jejich-projevy)
   * 3.5 [Všechny dohodnuté principy](#35-Všechny-dohodnuté-principy)
* 4 [Otevřené otázky](#4-Otevřené-otázky)
   * 4.1 [Části, na kterých se zatím nedosáhlo shody](#41-Části,-na-kterých-se-zatím-nedosáhlo-shody)
   * 4.2 [Poznámky pro realizaci](#42-Poznámky-pro-realizaci)
   
# 1. Úvod
### 1.1 Účel
