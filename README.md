# PowerBI

Můj první PowerBI projekt, na základě absolvovaného kurzu Datové Akademie od Engeto na podzim 2024.
Data jsem si našel a zpracoval sám, téma jsem měl jasné od začátku. 

Hlavní myšlenkou bylo ukázat, jak nynejší ruský režim přistupuje k obrovským ztrátám vlastních vojáků při agresi na Ukrajinu, ve srovnání s předchozími konflikty SSSR v Afghánistánu a dvou válkách v Čečensku.
Získání dat pro válku na Ukrajině bylo komplikované. Neexistují relevantní ověřitelné zdroje reálných ztrát, a tak jsem analyzoval více zdrojů, jejich hodnoty zprůměroval a volil spíše konzervativní, tj. nižší výsledky. Ani data pro Afghánistán a Čečensko nejsou stoprocentní, také zde neexistují definitivní čísla, ale spíše kvalifikované odhady z publikací a zpráv.  

Grafickou podobu jsem záměrně zvolil tmavou, aby korespondovala s tématem. Úvodní obrázek jsem si nadefinoval sám a nechal vygenerovat AI. Barvy vizuálů odpovídají úvodnímu obrázku a vycházejí z vlajky Ruské federace.

Výzvou bylo zobrazit na mapě Čečensko, které není státem, ale republikou v rámci RF. Musel jsem na to přes souřadnice ve správném formátu. Trvalo mi také správné nastavování průřezů, protože na monitoru ntb nebyly správně vidět ikony propojení s dalšími vizuály a vzájemně se rušily. 
Hodně času jsem také strávil úpravou "vizuálu ve vizuálu" (kombinovaný čárový graf a vložená karta na poslední stránce), kdy mi editor střídavě zobrazoval a schovával kartu v grafu. Pomohlo až uložení a promítnutí hotové prezentace a ta už vložený seskupený vizuál zobrazovala korektně. 

Myslím, že jsem splnil všechna požadovaná kritéria projektu až na jedno - víceúrovňovou hierarchii sloupcového geografického grafu na poslední stránce. Má zobrazovat data pro země, regiony a světadíly. Povedlo se mi sice vytvořit příslušné skupiny zemí ve zdrojové tabulce, ale nedokážu dát správná data na osu y, aby se mi to promítlo do frontendu. Budu konzultovat s lektorem, abych to mohl opravit. 

Na projektu jsem strávil caa 2,5 týdne, vždy po zaměstnání, včetně zpětného shlédnutí záznamů všech relevantních lekcí. 
