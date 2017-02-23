# jQuery - zadania domowe
> Kod wpisz w odpowiednim pliku, zgodnie z poleceniem zadania.
BARDZO WAŻNE - Wasze zadania są sprawdzanie przy pomocy automatycznego systemu. Żeby odpowiedzi zostały uznane za poprawne strony MUSZĄ wyświetlać te same komunikaty co w treści zadania, a funkcjie i metody MUSZĄ posiadać nazwy dokładnie takie same jak podane w zadaniu.


## Dzień 1 - jQuery
> Zadania z tego dnia wykonuj w pliku app.js

### Zadanie 1

Zajrzyj do pliku ```index.html```. Jest tam sporo elementów. Za pomocą jQuery znajdź wszyskie elementy z klasą ```border``` i nadaj im dowolne obramowanie.

### Zadanie 2

Zajrzyj do pliku ```index.html```. Znajdź element o id ```menu``` i zapisz do zmiennej.
Zapisz do innej zmiennej również wszystkie dzieci tego elementu. Napisz kod, który zamieni tekst ostatniego dziecka na "Jestem ostatnim dzieckiem".

### Zadanie 3

Zajrzyj do pliku ```index.html```. Zapisz do zmiennej elementy menu. Ustaw każdemu z nich kolor tekstu na taki jaki mają ustawiony w atrybucie `data-color`.

### Zadanie 4

W pliku **index.html** znajdź formularz o **klasie** ```login```. W pliku **app.js** stwórz funkcję, która będzie reagować na wciśnięcie przycisku ```show-hide-btn```.
Na początek ustaw event tak, aby po wciśnięciu wypisał w konsoli "działam". Następnie funkcja ma sprawdzać, jakiego typu jest element przechowujący hasło. Jeśli ```password``` &ndash; zmień **type** na ```text```. Jeśli ```text``` &ndash; zmień na ```password```.


### Zadanie 5 - dodatkowe

Znajdź w pliku **index.html** element o **klasie** ```running-element```. Następnie napisz dla niego funkcję, wewnątrz której wykonaj następujące czynności:
* ustaw event ```click``` na elemencie ```running-element```,
* po kliknięciu w element przesuń **div** (znajdujący się wewnątrz niego) o ```20px``` w prawo,
* ustaw czas trwania jednego przesunięcia na dwie sekundy,
* po zakończeniu każdego przesunięcia wypisz w konsoli tekst "Przesuwanie zakończone".

### Zadanie 6  - dodatkowe

Znajdź w pliku **index.html** element o **klasie** ```select```, a następnie napisz dla niego następującą funkcję:
* po kliknięciu w strzałkę zostaje rozwinięta lista **ul** o **klasie** ```select-body```,
* po ponownym kliknięciu lista zwija się z powrotem,
* spróbuj zmodyfikować zadanie tak, aby strzałka wskazywała w przeciwną stronę, gdy oczekuje na zwinięcie.


### Zadanie 7 - dodatkowe

Za pomocą funkcji ```each()``` znajdź wszystkie elementy **a**, następnie
ustaw ich atrybut **href** na adres [CodersLab](www.coderslab.pl).
