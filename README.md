# REPOSITORY
TESTING STRATEGY
Projekt końcowy dla firmy Connectors Poland Sp. z o.o.  
http://connectors.pl/

Projekt:
Projekt Generator – to nowa wersja oficjalnej strony firmowej kierowanej do przyszłych oraz obecnych kontrahentów z branży automatowe. Strona została wdrożona przez firmę zewnętrzna. Oczekujemy ze zostanie potwierdzona jakość tej strony pod kątem możliwych błędów oraz usprawnień. Zależy nam na dobrym wizerunku. Klienci pochodzą z całego świata i są to takie koncerny jak Audi, BMW, Ford, GM

## Konfiguracja wstępna: 

1) Przeglądarki - Safari,  Chrome
2) Typy urządzeń - Desktopowe, Mobilne, Tablet

## Typy testów wykonywany: 

1) Responsywność 

## Narzędzia potrzebne do testowania: 

1) Selenium IDE 
2) Market Share: https://gs.statcounter.com/browser-market-share 
3) DevTool
4) Gatling: https://gatling.io/
5) Postman 

## Zakres testów: 

1) Strona powinna być dostosowana do popularnych urządzeń oraz przeglądarek. Uwzględniono Rozdzielczości: desktopowe - 1920x1080 px, mobilne - 360 x 640px, tablet - 768 x 1024px
2) Strona w 3 językach: polski, niemiecki, angielski

## Testy:

1) ID: 3072, 3080, 3192, 3194 - Logowanie, Integracja SAP, Terminy dostaw, Kontrakty



## Link do Testplanów:

https://dev.azure.com/findbuDOTgs/Generator/_testPlans/define?planId=3048&suiteId=3320

## Struktura powyższego testplanu wygląda następująco:
W folderze z inicjałami znajdują się 4 foldery z poszczególnymi podfolderami a  wewnątrz ich przypadki testowe

## Link do dashboradów:

https://dev.azure.com/findbuDOTgs/Generator/_dashboards/dashboard/2931ce0d-7757-4762-a9c9-fede01aa28cf

#Definition of ready: 

- testy rozpoczynamy po analizie wymagań 
- dostęp do strony Connectors Poland Sp. z o.o. :http://connectors.pl/ 
- dostęp do opisanych narzędzi 
- środowisko testowe- Windows 10, Windows 8.1, przeglądarka Google Chrome, Safari

#Definition of done:

- testy są zakończone, kiedy ich status bug ma status jest zamknięty
- testy są zakończone, kiedy wszystkie możliwe ścieżki zostały pokryte testami 

