# jQuery - zadania domowe
> Czytaj dokładnie opisy do zadań. Jeśli w zadaniu jest napisane, żeby napisać funkcje
o konkretnej nazwie to taką nazwę właśnie przyjmij dla swojej funkcji. Jeśli w zadaniu jest
powiedziane, że należy zwrócić tablicę to zwróć tablicę.

> Zadania z dopiskiem "dodatkowe" są dla chętnych. Znajdziesz je na końcu.

### Dzień 1 - jQuery

#### Zadanie 1

Zajrzyj do pliku ```index.html```. Jest tam sporo elementów. Za pomocą jQuery znajdź wszyskie elementy z klasą ```border``` i nadaj im dowolne obramowanie.
//test
function check(sel, prop) {
    var i, property, $o = $(sel), directions = ["left", "right", "top", "bottom"];

    for (i = 0; i < directions.length; i++) {
        property = $o.css(prop + '-' + directions[i] + '-style');
        if (property !== 'solid') {
             return false;
        }
    }

    return true;
}

#### Zadanie 2

Zajrzyj do pliku ```index.html```. Znajdź element o id ```menu``` i zapisz do zmiennej.
Zapisz do innej zmiennej również wszystkie dzieci tego elementu. Napisz kod, który zamieni
tekst ostatniego dziecka na "Jestem ostatnim dzieckiem".

#### Zadanie 3

Zajrzyj do pliku ```index.html```. Elementy menu masz już zapisane do zmiennej (Jeśli udało Ci się zrobić poprzednie zadanie). Ustaw każdemu z nich kolor tekstu na taki jaki mają ustawiony w atrybucie `data-color`.


### Dzień 2 - jQuery

#### Zadanie 1
Zajrzyj do pliku ```index.html```. Napisz kod, za pomocą którego po najechaniu na którykolwiek
obrazek uniesie się on lekko do góry (dokładniej mówiąć o 10px). Po zjechaniu powinien wrócić do poprzedniej
pozycji. Wykorzystaj jakąś animację.

#### Zadanie 2
Dodawanie tagów.
Znajdź w pliku `index.html` element ```userPanel```. Jest w nim pole typu ```input``` oraz element o klasie ```panel```. Napisz kod, za pomocą którego tekst wpisany do pola input zostanie ( po wciśnięciu w przycisk `Wstaw` ) dodany do elementu o klasie ```panel```. Tekst powinien być dodawany jako span `span` z klasą **tag**.


### Dzień 3 - dokończ warsztaty jeśli nie skończyłeś na zajęciach. Jeśli masz skończone zrób zadania dodatkowe (niżej)

### Dzień 4 - Ajax
