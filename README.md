# Virtual Challenge
**Autor:** *Šlégl Jan*

## Představení

Aplikace je pro skupinu nebo jednotlivce. Uživatel má možnost si zvolit start a cíl a na základě nastavené aktivity si může určit cíl kam má přesně dojít. Ukazuje průběh dané cesty. Má motivační charakter.

V uživatelské prostředí by měla být úvodní obrazovka lišící se podle toho, zda má uživatel nějakou aktivní trasu nebo ne. Pokud ne, tak by jej vyzvala na přidání do skupiny nebo založení sólo výzvy. V případě aktivní trasy by člověk viděl cíl, mapu, kde se aktuálně na cestě nachází a počet ujitých kilometrů. Další okna by byl uživatelský profil a možnost zobrazení skupin, kde se uživatel nachází.

Aplikace musí umožnit propojení s ostatními fitness track providery jako Garmin, Strava, Polar atd., stejně tak jako možnost vlastního zápisu dat. 

## Paleta barev

+ ![#4ac1cf](https://via.placeholder.com/15/4ac1cf?text=+) `#4ac1cf` 
+ ![#e7f2f8](https://via.placeholder.com/15/e7f2f8?text=+) `#e7f2f8` 
+ ![#ffa384](https://via.placeholder.com/15/ffa384?text=+) `#ffa384` 
+ ![#efe7bc](https://via.placeholder.com/15/efe7bc?text=+) `#efe7bc` 

Ty pastelový barvy jsou trochu divný, takže do what you will jestli chcete trochu kontrastnější barvičky. Určitě by připadal v úvahu dark mode, ale na ten nemáme dostatečný funding. 

## Fonty
V projektu jsou použity dva fonty
+ Primárně handwriting [Grape Nuts](https://fonts.google.com/specimen/Grape+Nuts)
+ Sekundární bezpatkový [Epilogue](https://fonts.google.com/specimen/Epilogue)

## Navigační menu

Jako první máme domovskou stránku, druhá je pro seznam aktuálních tras. V případě, že žádná ještě není tak se ukazuje na domovské stránce rovnou vytvoření nové výzvy. Jako třetí je tzv. "community tab". Jako základní stav je tabulka skupin. Další možnost je nahoře se překliknout na novinky od ostatních přátel a lidí ve vašich skupinách. Poslední je osobní profil, kde vidíme jméno, foto a poslední aktivity. Je možnost se překliknout na statistiky a osobní údaje.

##Problémy

Největší problém je zobrazení mapy a ukázaní aktuálního progresu na mapě. Pravděpodobně je nutné použít asi API? nějakých map a využít spojení těch dvou míst. Já osobně bych využíval nejrychlejší cestu, ale je nutné ji uložit protože třeba google mapy se mění na základě dopravní situace a stím by se měnili i kilometry celkové trasy. Je nutné použít databázi na ukládání všech dat. Bylo by potřeba vytvořit profily a registrační systém. Další oříšek by bylo propojení jednotlivých fitness trackerů a využití jejich dat, primárně gpx souborů a využití jejich dat.

## Jednotlivé stránky

### Homepage
![homepage.](https://github.com/pslib-cz/2021l4web-app-mockup-SleglJan/blob/main/design/Homepage.png){ 400px, 865px }

### Vytvoření trasy
![vytvoreni_tras.](https://github.com/pslib-cz/2021l4web-app-mockup-SleglJan/blob/main/design/Vytvoreni_tras.png){ 400px, 865px }

### Seznam výzev
![seznam_tras.](https://github.com/pslib-cz/2021l4web-app-mockup-SleglJan/blob/main/design/Seznam_tras.png){ 400px, 865px }

### Community tab - Skupiny
![skupiny.](https://github.com/pslib-cz/2021l4web-app-mockup-SleglJan/blob/main/design/Community_tab-skupiny.png){ 400px, 865px }

### Community tab - Novinky
![novinky.](https://github.com/pslib-cz/2021l4web-app-mockup-SleglJan/blob/main/design/Community_tab-novinky.png){ 400px, 865px }

### Profil
![profil.](https://github.com/pslib-cz/2021l4web-app-mockup-SleglJan/blob/main/design/Profil.png){ 400px, 865px }
