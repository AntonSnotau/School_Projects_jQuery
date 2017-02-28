# jQuery - zadania domowe
> Kod wpisz w odpowiednim pliku, zgodnie z poleceniem zadania.
BARDZO WAŻNE - Wasze zadania są sprawdzanie przy pomocy automatycznego systemu. Żeby odpowiedzi zostały uznane za poprawne strony MUSZĄ wyświetlać te same komunikaty co w treści zadania, a funkcjie i metody MUSZĄposiadać nazwy dokładnie takie same jak podane w zadaniu.


## Dzień 2 - jQuery
> Zadania z tego dnia wykonuj w pliku app.js

### Zadanie 1 - Prosta animacja

Zajrzyj do pliku ```index.html```. Napisz kod, za pomocą którego po najechaniu na którykolwiek
obrazek uniesie się on lekko do góry (dokładniej mówiąć o 10px). Po zjechaniu powinien wrócić do poprzedniej
pozycji. Wykorzystaj jakąś animację.

### Zadanie 2 - Dodawanie tagów

Znajdź w pliku `index.html` element ```userPanel```. Jest w nim pole typu ```input``` oraz element o klasie ```panel```. Napisz kod, za pomocą którego tekst wpisany do pola input zostanie ( po wciśnięciu w przycisk `Wstaw` ) dodany do elementu o klasie ```panel```. Tekst powinien być dodawany jako span `span` z klasą **tag**.

### Zadanie 3

Znajdź w pliku **index.html** element o **klasie** ```running-element```. Następnie napisz dla niego funkcję, wewnątrz której wykonaj następujące czynności:
* ustaw event ```click``` na elemencie ```running-element```,
* po kliknięciu w element przesuń **div** (znajdujący się wewnątrz niego) o ```20px``` w prawo,
* ustaw czas trwania jednego przesunięcia na dwie sekundy,
* po zakończeniu każdego przesunięcia wypisz w konsoli tekst "Przesuwanie zakończone".

### Zadanie 4

Znajdź w pliku **index.html** element o **klasie** ```select```, a następnie napisz dla niego następującą funkcję:
* po kliknięciu w strzałkę zostaje rozwinięta lista **ul** o **klasie** ```select-body```,
* po ponownym kliknięciu lista zwija się z powrotem,
* spróbuj zmodyfikować zadanie tak, aby strzałka wskazywała w przeciwną stronę, gdy oczekuje na zwinięcie.


### Zadanie 5 - dodatkowe

Za pomocą funkcji ```each()``` znajdź wszystkie elementy **a**, następnie
ustaw ich atrybut **href** na adres [CodersLab](www.coderslab.pl).
