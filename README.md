# Projekt Jumper


# Technologia
Do tego projektu użyjemy Pythona 3.8, a tak dogłębniej to jedną z jego bibliotek, a mianowicie pygame w wersji 2.0. Na nim oprzemy większość naszej gry.

# Plan
-menu główne (Miłosz Kapłanek, Tomasz Paruzel - design)

-grafika postaci (Tomasz Paruzel)

-animacje postaci (Tomasz Paruzel)

-design poziomów (Tomasz Paruzel, Miłosz Kapłanek)

-Fizyka gry (Miłosz Kapłanek, Tomasz Paruzel)

-przeciwnicy i implementacja ich zachowania (Tomasz Paruzel-design, Miłosz Kapłanek - zachowanie)

-zapis gry (opcjonalnie) (Współpraca) ??

-efekty dźwiękowe (Współpraca) ??

# Prace (raport II)
W aktualnej wersji alpha zostałostworzone Menu główne, pioerwszy(prototypowy poziom) na którym jest póki co testowane działanie sterowania gracza oraz zachowanie przeciwników czy samo działanie elementów jak "wygrana" czy "przegrana". Pierwsze ktatki przeciwników, z których będą stworzone w kolejnych krokach animacje.

Na ten moment mamy działające menu, pare zakładek, początkowe grafiki oraz kolizje między graczema jego przeciwnikiem lub nagrodą.

# Prace (Prototyp)

W naszej bierzącej wersji gry została zmieniona grafika, wygląd poziomów jak i postaci jest zrobiona z większą  dokładnością.
Animacje są tworzone w programie Affinity Designer. Każda klatka jest osobno edytowana i eksportowana do pliku PNG.
Aktualnie pracujemy nad stworzeniem kolizji z obiektami, platformami, po których nasza postac będzie mogła skakać tak dotrzećdo "nagrody" bądź uniknąć przeciwnika.

Głównym problemem było wyjęcie 

Aktualnie zaimplementowane element do gry:

-Animacje postaci oraz "nagrody"

-Zmiana poziomów po dotarciu do końca mapy 

-Skok jako element grawitacji postaci i gry

-Optymalizacja kodu, wprowadzenie klas

# Do Zrobienia

-Zakładka wyboru poziomu w menu głównym

-Więcej klatek animacji, aby były płynniejsze oraz dokładniejsze,a tick rate mógłbyc stały w granicach 60 fps dla lepszej płynności 
 
-Wyjęcie głównej funkcji "running" z definicji
 
-Efekty dźwiękowe(opcjonalne)

-Zapisy Gry(opcjonalne)
 
 # Prace (Raport 3)
 
 W aktualnej wersji nastała duża zmiana, jeżeli chodzi o funkcjonalnośc grawitacji, ponieważ została od nowa stworzona funkcja odpowiedzialna za działanie grawitacji i przyciąganie postaci do ziemi. Następnie przy pomocy dodanej definicji w klasie Gracz "On_the_ground" sprawdzamy czy nasza postać znajduje się na jakiejś powierzchni np. podłoże mapy lub platforma. Sama grawitacja w tej wersji gry oddziałowuje na naszą postać przez cały czas działania.
Kolizja z platformami, która była planowana działa i jst możliwość chodzenia pod i na platformie. 
Globalna definicja z przyciskiem Main Menu, która jest wykorzystywana w każdej zkładce, Twórców, Opcji oraz w konkretnych poziomach gry.
Dodany został nowy przeciwnik w formie klasy wraz z animacją. 
Platformy glbalnie definiowane w celu wykorzystania ich w klasie "Gracz".
Dodane zostały 2 dodatkowe poziomy jest ich aktualnie 5. 
