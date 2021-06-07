
                        
                        
                        Autorzy:
                        Michał Łabuda, WZISN2-1212, 217045
                        Kamil Rąpała, WZISN2-1212, 217320
                        Przemysław Niedziela, WZISN2-1212, 217245
 

# YourMovieHub - Filmowy Serwis Informacyjny
 Spis Treści
1. Krótki opis Aplikacji
2. Nazwy użytych technologii i oprogramowania
3. Linki do oprogramowania które zostało wykorzystane
4. Instrukcja i instalacja aplikacji
5. Instrukcja obsługi Aplikacji (YourMovieHub) i opis funkcjonalności
aplikacji
6. Linki do składowych projektu:

## Krótki opis aplikacji
Aplikacja pozwalająca na przeglądanie bazy filmów, przeglądanie
aktualności kinowych czy propozycji do obejrzenia ( np. #zostań w domu -
proponowane filmy na udany wieczór w formie losowania) oraz na
zamieszczanie wpisów w postaci ocen i swoich odczuć na temat
obejrzanych filmów.

Funkcjonalności które zostały zawarte to:
- wyszukiwanie filmów w bazie danych
- przeglądanie ocen użytkowników i ich opinii
- możliwość ocenienia filmu, dodania swojej opinii o nim
- bezpośrednie przeglądanie najnowszych produkcji
- Rejestracja i logowanie do serwisu

## Nazwy użytych technologii i oprogramowania
1. PhpStorm -to komercyjne, wieloplatformowe IDE dla PHP,
zapewnia edytor PHP, HTML i JavaScript z analizą kodu w
locie, zapobieganiem błędom i automatycznym refaktoryzacją
kodu PHP i JavaScript. Jeden z dwóch edytorów, które zostały
wykorzystywane do stworzenia aplikacji.
2. VisualStudioCode - darmowy, desktopowy edytor
programistycznych kodów źródłowych z kolorowaniem składni
dla wielu języków, stworzony przez Microsoft. Jeden z dwóch
edytorów, które zostały wykorzystywane do stworzenia
aplikacji.
3. Github - hostingowy serwis internetowy przeznaczony dla
projektów programistycznych wykorzystujących system kontroli
wersji Git. Została wykorzystany również do prowadzenia
postępu w projekcie.
4. Firebase - to platforma do tworzenia aplikacji mobilnych i
internetowych. Została wykorzystana do logowania i rejestracji
oraz przechowywania ocen i komentarzy użytkowników.
5. Vue+Vuetify - jest strukturą JavaScript typu open source
Model-view-viewmodel do budowania interfejsów użytkownika i
aplikacji jednostronicowych. Vuetify jest szkieletem
komponentów dla Vue.

## Linki do oprogramowania które zostało wykorzystane


1. [https://www.jetbrains.com/phpstorm/](https://www.jetbrains.com/phpstorm/)
2. [https://code.visualstudio.com/](https://code.visualstudio.com/)
3. [https://github.com/](https://github.com/)
4. [https://firebase.google.com/](https://firebase.google.com/)
5. [https://vuejs.org/](https://vuejs.org/)
6. [https://vuetifyjs.com/en/](https://vuetifyjs.com/en/)

## Linki do składowych projektu


   1. [Link do witryny z dokumentacja projektu](https://kamilr96.github.io/YourMovieHub-Doc/)
   2. [Link do repozytorium](https://github.com/pniedziela/YourMovieHub/tree/develop)
   3. [Link do zarządzania projektem informatycznym na GitHub](https://github.com/users/kamilr96/projects/1)
   4. [Link do wykonanej aplikacji](https://pniedziela.github.io/YourMovieHub/)



## Instrukcja i instalacja aplikacji
1. Należy pobrać, zainstalować i uruchomić Git Bash.
2. Należy pobrać, zainstalować i uruchomić PhpStorm/Visual
Studio Code.
3. Po uruchomieniu Git Basha pobrać poprzez wpisanie git clone
+ repozytorium z linku:
[https://github.com/pniedziela/YourMovieHub](https://github.com/pniedziela/YourMovieHub)
4. Uruchomić poprzez wybrany program pobrane repozytorium
5. W konsoli wprowadzić następującą treść :
npm install - zaczekać aż pobierze wszystkie moduły i
biblioteki
6. Po pobraniu i instalacji wprowadzić kolejną komendę:
npm run serve - gdy się skompiluje nacisnąć w konsoli na:
Network: [http://192.168.1.105:8080/](http://192.168.1.105:8080/)

## Instrukcja obsługi Aplikacji ( YourMovieHub)

1. Po uruchomieniu npm run serve oraz wejsciu na link
[http://192.168.1.105:8080/](http://192.168.1.105:8080/) lub [https://pniedziela.github.io/YourMovieHub/](https://pniedziela.github.io/YourMovieHub/) ukazuje się główne menu (strona
domowa) aplikacji.

<p align="center">
 <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/1.png?raw=true" alt="Location"/>
</p>

Na stronie domowej znajdują się dwa przyciski z których korzysta się do
poprawnego funkcjonowania aplikacji. Są to “Zarejestruj się” i “Zaloguj
się”. Po wciśnięciu przycisku “Zarejestruj się” ukazuje nam się pole z
formularzem (E-mail, Wybierz Hasło , Potwierdź Hasło), który należy
wypełnić poprawnymi danymi (Hasło musi mieć co najmniej 6 znaków a
e-mail @ w swoim wyrazie).

<p align="center">
 <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/2.png?raw=true" alt="Location"/>
 
 </p>
 Jeśli hasło jest za krótkie wyskakuje odpowiednie powiadomienie.
<p align="center">
 <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/3.png?raw=true" alt="Location"/>
  </p>
  Po poprawnej rejestracji aplikacja automatycznie zaloguje nas do serwisu.
Naciskając przycisk “Zaloguj się” (Podczas pierwszego logowania po
rejestracji) wyświetli nam się pole z miejscem do wprowadzenia loginu i
hasła, a następnie należy wcisnąć przycisk “Zaloguj”. Przycisk “Zamknij”
w obu przypadkach zamyka okna z formularzami.
  <p align="center">
  <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/4.png?raw=true" alt="Location"/>
  </p>
  
  Użytkownikowi który poprawnie się zarejestrował i zalogował ukazuje się
baza z filmami polecanymi w menu głównym.
   
 <p align="center">
   <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/5.png?raw=true" alt="Location"/>
  </p>
                                                                                                     
  W menu głównym znajdują się cztery przyciski, które pobierają informacje z
bazy(API) są to “Filmy”, “Seriale”, “Polecane”, “#Zostań w Domu”,
odpowiednie Pole do wprowadzenia tytułu filmu którego poszukujemy, oraz
przycisk “Szukaj” który aktywuje poszukiwania.
W prawym górnym rogu znajduje się Ikona wraz z początkiem nazwy z
maila oraz przycisk “Wyloguj się” który wylogowywuje nas z bazy i cofa
do strony domowej.

<p align="center">
<img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/6.png?raw=true" alt="Location"/>
 </p>
Przykładowo wprowadzamy frazę “Avengers” i Aplikacja wyszukuje nam
wszystkie filmy i seriale powiązane z tą nazwą po wciśnięciu przycisku
“Szukaj”

Po wciśnięciu na plakat filmowy otwiera nam się okno w którym znajduje
się dwa przyciski “Zamknij” który zamyka okno oraz “Komentarze”, który
pozwala na skomentowanie filmu i obejrzenie komentarzy innych
użytkowników. W oknie znajduje się również opis filmu który przeglądamy.
     
   <p align="center">               
 <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/7.png?raw=true" alt="Location"/>
    </p>
Gwiazdki oznaczają ocenę od 1 do 5 i w zależności jak zaznaczymy i jaką
ocenę wystawimy danemu filmowi, aplikacja po ponownym otwarciu okna
pokaże nam średnią ogólną z naszą już dodaną do bazy oceną
  <p align="center">
   <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/8.png?raw=true" alt="Location"/>
  </p>
W polu komentarzy są dwa przyciski “Zamknij” który je zamyka oraz
“Skomentuj” który pozwala na dodanie komentarza po ówczesnym
wpisaniu go w odpowiednie do tego miejsce.
 <p align="center">
   <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/9.png?raw=true" alt="Location"/>
  </p>
 Komentarz jest dodany i od razu wyświetla się użytkownikowi. Inne
komentarze innych użytkowników są wyświetlane w liście również na żywo.
   <p align="center">                                                                                                   
    <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/10.png?raw=true" alt="Location"/>                                    <p/>                                                        
   Aplikacja jest również responsywna i odpowiednio się skaluje na
urządzeniach mobilnych co jest pokazane na poniższych screenach
 <p align="center">
    <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/11.png?raw=true" alt="Location"/>
         </p>    
   <p align="center"> 
     <img src="https://github.com/kamilr96/kamilr96.github.io/blob/master/12.png?raw=true" alt="Location"/>                
     </p>
     
   

