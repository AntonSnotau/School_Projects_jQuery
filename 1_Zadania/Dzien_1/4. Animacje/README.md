# Animacje

> Odpowiedzi wpisz w odpowiednich plikach, chyba że treść polecenia wskazuje inaczej.
Pamiętaj, żeby oddzielać ćwiczenia komentarzami i pisać czytelny, dobrze sformatowany kod.
Jeśli  polecenie w zadaniach brzmi: "Stwórz nową funkcję, w której wykonasz te czynności" to znaczy, że
należy stworzyć funkcję. Nawet jeśli treści zadań są mało skomplikowane
ucz się używać funkcji.

## Zadanie rozwiązywane z wykładowcą

### Click  (~ 5min - 7min)
Ustaw event ```click``` na elementach **button**. Po kliknięciu w każdy z nich konsola ma wypisać tekst znajdujący się
na klikniętym elemencie. Użyj funkcji ```text()```.

### Zanikanie  (~ 5min - 7min)
Po kliknięciu w element o **klasie** ```content``` ustaw animację przygaszania (czyli zmień ```opacity``` na **0.5**) z czasem zanikania dwie sekundy.
Po zakończeniu przygaszania wróć do normalnej widoczności elementu z czasem 0,7 sekundy.

-----------------------------------------------------------------------------------------------------

## Zadania do samodzielnego wykonania

### Zadanie 1 (~ 5min - 10min)

Znajdź w pliku **index.html** element o **klasie** ```buttons```. Stwórz odpowiednią funkcję i wykonaj w niej następujące czynności:
* po kliknięciu w pierwszy przycisk &ndash; pokaż element o **klasie** ```content```,
* po kliknięciu w drugi element &ndash; ukryj element o **klasie** ```content```,
* po kliknięciu w trzeci element raz pokaż, a raz ukryj element o **klasie** ```content```.

### Zadanie 2 (~ 5min - 10min)

Znajdź w pliku **index.html** element o **klasie** ```images```, stwórz odpowiednią funkcję i wykonaj w niej następujące czynności:
* ukryj obrazek drugi,
* po kliknięciu w pierwszy obrazek ma on zostać ukryty o pokazać się drugi obrazek.
Wykorzystaj funkcje z rodziny ```fade```.

### Zadanie 3  (~ 10min - 15min)

Znajdź w pliku **index.html** element o **klasie** ```select```, a następnie napisz dla niego następującą funkcję:
* po kliknięciu w strzałkę zostaje rozwinięta lista **ul** o **klasie** ```select-body```,
* po ponownym kliknięciu lista zwija się z powrotem,
* spróbuj zmodyfikować zadanie tak, aby strzałka wskazywała w przeciwną stronę, gdy oczekuje na zwinięcie.

### Zadanie 4  (~ 10min - 15min)

Znajdź w pliku **index.html** element o klasie ```histogram```. Następnie napisz dla niego funkcję, wewnątrz której wykonaj:
* znajdź wszystkie elementy **div** wewnątrz sekcji ```histogram```,
* za pomocą animacji jQuery trwającej 2sekundy, powiększ:
    * pierwszy słupek do szerokości 100px,
    * drugi słupek do szerokości 150px,
    * trzeci słupek, do szerokości 80px,
    * czwarty słupek do szerokości 200px.

Kod napisz tak, aby kolejny słupek zaczynał swoją animację dopiero wtedy, gdy poprzedni skończy.


### Zadanie 5  (~ 10min - 15min)

Znajdź w pliku **index.html** element o **klasie** ```running-element```. Następnie napisz dla niego funkcję, wewnątrz której wykonaj następujące czynności:
* ustaw event ```click``` na elemencie ```running-element```,
* po kliknięciu w element przesuń **div** (znajdujący się wewnątrz niego) o ```20px``` w prawo,
* ustaw czas trwania jednego przesunięcia na dwie sekundy,
* po zakończeniu każdego przesunięcia wypisz w konsoli tekst "Przesuwanie zakończone".
