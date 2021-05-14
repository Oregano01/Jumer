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

Aktualnie zaimplementowane element do gry:

-Animacje postaci oraz "nagrody" - DO ZROBIENIA więcej klatek animacji, aby były płynniejsze oraz dokładniejsze,a tick rate mógłbyc stały w granicach 60 fps dla lepszej płynności 

-Zmiana poziomów po ditarciu do końca mapy - DO ZROBIENIA zakładka wyboru poziomu w menu głównym

-Skok jako element grawitacji postaci i gry - DO ZROBIENIA kolizja z platrformami, po których gracz będzie się przemieszczał

-Optymalizacja kodu, wprowadzenie klas - DO ZROBIENIA wyjęcie głównej funkcji "running" z definicji

Do Zrobienia

**DO ZROBIENIA zakładka wyboru poziomu w menu głównym**
