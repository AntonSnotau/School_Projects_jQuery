# Eventy

> Odpowiedzi wpisz w odpowiednich plikach, chyba że treść polecenia wskazuje inaczej.
Pamiętaj, żeby oddzielać ćwiczenia komentarzami i pisać czytelny, dobrze sformatowany kod.
Jeśli  polecenie w zadaniach brzmi: "Stwórz nową funkcję, w której wykonasz te czynności" to znaczy, że
należy stworzyć funkcję. Nawet jeśli treści zadań są mało skomplikowane
ucz się używać funkcji.


## Zadanie rozwiązywane z wykładowcą

### Najeżdżanie i zjeżdżanie  (~ 7min - 12min)
 Ustaw event na elemencie **dt**, którego zadaniem jest wyświetlanie w konsoli informacji o elemencie, na który najechaliśmy. Przetestuj różnicę między ```mouseenter```, ```mouseover``` i ```mousemove```.

-------------------------------------------------------------------------------

## Zadania do samodzielnego wykonania

### Zadanie 1  (~ 10min - 15min)
  Znajdź w pliku **index.html** trzy **buttony** w elemencie o **klasie** ```hero-buttons```. Stwórz funkcję, w której wykonaj następujące czynności:
* ustaw każdy z trzech przycisków pod inną zmienną,
* dla elementu pierwszego ustaw event ```click```, który po kliknięciu wyświetli w konsoli napis "kliknięto mnie",
* dla elementu drugiego ustaw event ```click```, który po kliknięciu wyświetli w konsoli napis "kliknięto mnie, ale już drugi raz nie dam się kliknąć",
* dla trzeciego wywołaj metodę, która odczepi wszystkie eventy z wszystkich przycisków.

Przetestuj działanie Twojej funkcji.

### Zadanie 2 (~ 10min - 15min)

Znajdź w pliku **index.html** **sekcję** o **klasie** ```superhero-description```, a następnie napisz funkcję, w której:
1. Ukryj domyślnie wszystkie elementy **dd**.
2. Po kliknięciu w element **dt** spraw, by elementy **dd**:
* rozwijały się, jeśli są ukryte,
* zwijały się, jeśli są widoczne.
* do znalezienia najbliższego rodzeństwa danego elementu użyj funkcji .next()

### Zadanie 3  (~ 10min - 15min)

W pliku **index.html** znajdź formularz o **klasie** ```login```. W pliku **app.js** stwórz funkcję, która będzie reagować na wciśnięcie przycisku ```show-hide-btn```.
Na początek ustaw event tak, aby po wciśnięciu wypisał w konsoli "działam". Następnie funkcja ma sprawdzać, jakiego typu jest element przechowujący hasło. Jeśli ```password``` &ndash; zmień **type** na ```text```. Jeśli ```text``` &ndash; zmień na ```password```.
