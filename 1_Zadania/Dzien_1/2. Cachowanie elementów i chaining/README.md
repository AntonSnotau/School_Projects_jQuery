# Cachowanie elementów i chaining

> Odpowiedzi wpisz w odpowiednich plikach, chyba że treść polecenia wskazuje inaczej.
Pamiętaj, żeby oddzielać ćwiczenia komentarzami i pisać czytelny, dobrze sformatowany kod.
Jeśli  polecenie w zadaniach brzmi: "Stwórz nową funkcję, w której wykonasz te czynności" to znaczy, że
należy stworzyć funkcję. Nawet jeśli treści zadań są mało skomplikowane
ucz się używać funkcji.


## Zadanie rozwiązywane z wykładowcą

### 1 (~ 2min - 5min)

Znajdź element ```nav``` i zapisz do zmiennej. Następnie za pomocą funkcji ```css()``` dodaj do niego obramowanie. Ustaw również funkcję ```fadeOut``` z bardzo wolnym zanikaniem oraz funkcję ```slideDown()```. Połącz wszystko w jeden łańcuch (chain).

-------------------------------------------------------------------------------

## Zadania do samodzielnego wykonania

### Zadanie 1  (~ 5min - 10min)

Popraw swoje zadanie 2. z poprzedniego rozdziału, tak aby jQuery tylko raz przeszukiwało dokument. Następnie połącz całe zapytanie w jeden łańcuch (jeśli to możliwe i jeśli jeszcze tego nie zrobiłeś).

### Zadanie 2 (~ 5min - 7min)

Napisz selektor, który znajdzie wszysktie elementy **section** w HTML-u. Sprawdź, jakie mają klasy. Wypisz te klasy w konsoli.

### Zadanie 3  (~ 5min - 7min)

Wypisz w konsoli pierwszy, trzeci i ostatni element menu. Użyj odpowiednich funkcji. Dodaj do znalezionych elementów **klasę** ```menuLinks```.

### Zadanie 4  (~ 5min - 7min)

Znajdź wszystkie elementy **li** znajdujące się wewnątrz **sekcji** o klasie ```main``` i **diva** o klasie ```container```. Każdemu z elementów przełącz **klasę** ```toggleMe```: jeśli element posiada tę klasę &ndash; wyłącz ją, jeśli nie posiada &ndash; włącz.

Wypisz w konsoli elementy, które posiadają klasę ```toggleMe```

Zadbaj o to, aby Twój kod był jak najprostszy. :)


### Zadanie 5 (~10min - 15min)

Znajdź wszystkie elementy **li** znajdujące się wewnątrz **sekcji** ```articles``` oraz **klasy** ```container```.

1. pierwszemu elementowi znalezionego zestawu, nadaj metodą ```css()``` kolor biały,
2. drugiemu elementowi &ndash; żółty,
3. trzeciemu &ndash; czerwony.
Do wyboru kolejnych elementów, użyj odpowiedniej metody jQuery.
4. Wszystkim znalezionym elementom **li** dodaj **klasę** ```articles-li```, którą znajdziesz w pliku css dołączonym do tego zadania. Jeśli zrobisz to poprawnie, wokół elementów listy powinna pojawić się biała ramka. Zaokrąglij odpowiednim stylem narożniki ramek. Użyj do tego metody ```css()```. Zadbaj o to, by tę część zadania (dodanie ramek i zaokrąglenie rogów) zmieścić w jednej linijce kodu.

Pamiętaj o tym, by nie wyszukiwać elementów **li** wielokrotnie.
