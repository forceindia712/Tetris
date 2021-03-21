# Tetris
Odwzorowałem grę Tetris z 1984 roku.
Gra posiada 5 klas:
- Window - klasa ma za zadanie utworzyć okno w którym otworzy się gra. Włącza ona również możliwość korzystania z myszki i klawiatury.
- Title - klasa ma za zadanie rysowania klocków. Umożliwia ona również kliknięcie w przyciski pauzy oraz resetu.
- Shape - klasa shape jest to klasa wysyłająca informację o klocku oraz jego położeniu do klasy title. Wszystkie funkcje mają za zadanie aktualizację położenia klocków, generowania nowych w przypadku dotknięcia granicy oraz usuwania poziomu w przypadku ułożenia całego poziomu.
- ImageLoader - klasa ładuje muzykę oraz obsługuje wyjątki
- Board - klasa ma za zadanie wysłać informację o całej tablicy do klasy shape. Jest odpowiedzialna za koniec gry, liczenie punktów, resetowanie gry, generowanie następnego klocka, itp. W programie można wygenerować 7 rodziajów klocków z góry ustalonych. Po postawieniu klocka, program losuje kolejny który będzie wyświetlony na tablicy.

Program posiada również wiele funkcji pomocniczych, np. obsługa klocków (strzałki). Jednak są one na tyle intuicyjne i oczywiste że pominąlem wspominanie o takich rzeczach.

![tetris](https://github.com/forceindia712/Tetris/blob/main/tetris.png)
