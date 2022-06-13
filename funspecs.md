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
   * 1.5 [Odkazy na ostatní dokumenty](#15-odkazy-na-ostatní-dokumenty)
* 2 [Scénář](#2-scénář)
   * 2.1 [Všechny reálné způsoby použití](#21-všechny-reálné-způsoby-použití)
   * 2.2 [Typy uživatelských rolí personas](#22-typy-uživatelských-rolí-personas)
   * 2.3 [Vymezení rozsahu - co v sw NEbude](#23-vymezení-rozsahu---co-v-sw-nebude)
   * 2.4 [Na co se nebude klást důraz](#24-na-co-se-nebude-klást-důraz)
* 3 [Celková hrubá architektura](#3-celková-hrubá-architektura)
   * 3.1 [Pracovní tok](#31-pracovní-tok)
   * 3.2 [Všechny detaily: obrazovky, okna, tisky, chybové zprávy, logování](#32-všechny-detaily-obrazovky-okna-tisky-chybové-zprávy-logování)
   * 3.3 [Všechny možné toky programu a jejich projevy](#33-všechny-možné-toky-programu-a-jejich-projevy)
   * 3.4 [Všechny dohodnuté principy](#34-všechny-dohodnuté-principy)

  
# 1. Úvod

### 1.1 Účel
Účelem tohoto dokumentu je všem co mají zájem o tuto velice jednoduchou kalkulačku, a chtějí se dozvědět jak bude vypadat, fungovat. Dozvíte se vše o mé kalkulačce, od detailů, až po nejzákladnější informace.

### 1.2 Konvence dokument
Změny v dokumentu budou obestaveny + pluskami +

Příkazy do konzole budou značeny „uvozovkami“

Odpovědi konzole budou psány [v hranatých závorkách]

### 1.3 Pro koho je dokument určený
Tento dokument je určen pro lidi, co se chtějí zjistit nebo mě kritizovat za to , jak bude moje kalkulačka, kterou tvořím, vypadat.

### 1.4 Další informace
#### Kontakty
Email: majer.ad.2019@skola.ssps.cz

Telefon: +420 606 791 015

### 1.5 Odkazy na ostatní dokumenty
Odkaz na SRS kalkulačky: https://github.com/MajerAdam/calculator/blob/main/SRS_for_Kalkulacka.docx 

# 2. Scénář

### 2.1 Všechny reálné způsoby použití
Kalkulačka se dá využít všemi běžnými způsoby jako jiná kalkulačka, ale narozdíl od ostaních kalkulaček bude umět o hodně míň věcí a věřím tomu, že i kdyby ji někdo opravdu chtěl využít. Tak to bude maximálně, proto, aby upravil kód mé kalkulačky v něco použitelnějšího.

### 2.2 Typy uživatelských rolí personas
Vzhledem k programu a jeho využití se uživatrlé nerozdělují, všichni uživatelé mají přístup ke stejným údajům.

### 2.3 Vymezení rozsahu - co v sw-nebude
Program nebude mýt různé módy, čí nějaké komlikované rovnice, podle kterých by kalkulačka mohla počítat.

### 2.4 Na co se nebude klást důraz
Ze začátku se nebude klást důray na responzivitu nebo comfort uživatelů. Bude se hlavně prioritizovat funkcionalita, aby se nejdřív zprovoznily část, které maají a musí fugovat.

# 3. Celková hrubá architektura

### 3.1 Pracovní tok
Začne se na kalkulačce pracovat poté co budou dodělány, všechny dokumenty, keré potřebuju napsat k uskutečnění práce. Tím pádem do týdne po dokončení SRS a FS by měla být kalkulačka dokončena.

### 3.2 Všechny detaily obrazovky okna tisky chybové zprávy logování
Login kalkulačka nebude mít. Po zpuštění se kalkulačka otevře conzoly, do které bude moc uživatel zaspisova příkazy.

![image](https://user-images.githubusercontent.com/97035550/173278438-38329c46-c675-4ecb-85d8-a6c82bb9207f.png)

### 3.3 Všechny možné toky programu a jejich projevy
Program bude v jazice C# a všechen kód bude uložen zde na githabu, bezpodmínečně tu vždy bude nejnovější verze mé kalkulačky.

### 3.4 Všechny dohodnuté principy
Kalulačka musí být na githabu, vždy ve své nejnovější formě. Ať bude kdokoliv kdo by chtěl mě kontaktovat může a ať tak učiní co nejdříve aby kalkulačka dopadla podle všech přání.








