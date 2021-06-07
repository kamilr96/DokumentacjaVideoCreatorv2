
                        
                        
                        Autorzy:
                  
                        Kamil Rąpała, 217320
                        Piotr Małek, 200543
 

# VideoCreatorv2 - Twórz filmiki ze swoich zdjęć!
 Spis Treści:
1. Krótki opis Aplikacji
2. Lista usług AWS wykorzystanych w projekcie:
3. Wady i zalety
4. Linki do składowych projektu
5. Dodatkowe informacje

## Krótki opis aplikacji
Aplikacja zrealizowana została w oparciu o elementy infrastruktury świadczonej w ramach usług Amazon webservices. Wykorzystane zostały funkcję powiązane z usługami Amazona takie jak zarządzanie infrastrukturą po stronie usługodawcy, skalowanie czy elastyczność. Główne założenie aplikacji to utworzenie video z wgranych wcześniej zdjęć/grafik. Zawarte podstawowe moduły to moduł uploadu, transcodingu oraz moduł notyfikacji. Integracja odbyła się w 2 wariantach. Pierwszy z nich to wykorzystanie protokołu HTTP (można wysyłać i odbierać dane), który charakteryzuje się synchronicznością - zarówno klient jak i serwer protokołu HTTP muszą działać jednolicie by zadanie było poprawnie zrealizowane. Drugi wariant jest asynchroniczny w formie serwera kolejki, gdzie dwa różne komponenty aplikacji nie musiały być aktywne w tym samym oknie czasowym, żeby zrealizować daną integrację.

Bardziej szczegółowe funkcjonalności które zostały zawarte to:
- Relase + deploymenty (w skróconej wersji)
- Rejestracja i logowanie do serwisu (z zabezpieczeniami)
- Odebranie pliku ze zdjeciem od użytkownika
- Umieszczenie pliku do przechowywania danych
- Agregacja informacji o zdjęciach, danych użytkownika i wytycznych dla albumu
- Zlecenie utworzenia albumu w oparciu o wytyczne
- Odebranie zlecenia
- Wykonanie zlecenia (stworzenie albumu)
- Umieszczenie albumu w warstwie przechowania


## Lista usług AWS wykorzystanych w projekcie:
- S3 - internetowy nośnik danych firmy Amazon, ma prosty w obsłudze interfejs WWW, który umożliwia dostęp do przechowywanych danych i zarządzanie nimi,
- Lambda - jest to usługa obliczeniowa, która uruchamia kod w odpowiedzi na zdarzenia i automatycznie zarządza zasobami obliczeniowymi wymaganymi przez ten kod,
- Cognito - to prosta usługa synchronizacji tożsamości użytkowników i danych,
- Simple Queue Service - to usługa kolejkowania wiadomości,
- Amazon Simple Email Service - to ekonomiczna, elastyczna i skalowalna usługa poczty e-mail, która umożliwia programistom wysyłanie poczty z dowolnej aplikacji
- API Gateway - to pewien rodzaj reverse proxy. Jego rolą jest odizolowanie reszty mikroserwisów od kwesti związanych z obsługą zapytań z aplikacji klienckich, a więc będzie on przekierowywał zapytania z klienta do odpowiednich serwisów.

## Wady i zalety
Wady: 
- Trudność dla początkujących w odnalezieniu się w AWS (Mnogość serwisów),
- Brak kontroli nad danymi przy niepoprawnej konfiguracji,
- Bardzo dużo opcji konfiguracyjnych,
- Bezpieczeństwo danych (ufamy, że tam jest bezpiecznie)
- Dostęp uzależniony od dostawcy chmury i dostawcy Internetu
- Ogrom dokumentacji
Zalety:
- Pomimo wady jaką jest ogrom dokumentacji do przyswojenia, jest ona dobra i treściwa,
- Dostęp z każdego miejsca,
- Super platforma do eksperymentów (w każdej chwili można wyłączyć i nie płacić),
- Duża i stosunkowo łatwa skalowalność pozioma i pionowa,
- Gotowe rozwiązania,
- Mocne SLA,

## Linki do składowych projektu


   1. [Link do witryny z dokumentacja projektu](https://kamilr96.github.io/DokumentacjaVideoCreatorv2/)
   2. [Link do repozytorium](https://github.com/VerticalMalek/videocreator_v2)
   3. [Link do zarządzania projektem informatycznym na AWS](https://s3.console.aws.amazon.com/s3/buckets/200543)
   4. [Link do wykonanej aplikacji](https://200543.s3.eu-central-1.amazonaws.com/index.html?fbclid=IwAR2toJ584XOnn-HjbtLUULHTeKHLqewH_I3rmOgP9bNeLDaEifJDdV_v1Uo)


## Dodatkowe informacje
Zostały wykonane wszystkie czynności przedstawione na zajęciach oraz ćwiczenia związane z tekstowymi obrazkami w ramach zapoznania się z funkcjonalnościami Pythona.
Do dokumentacji zostały wykorzystane materiały z zajeć: [Link do witryny z materiałami](http://wpc.dydaktyka.jkan.pl/) 

