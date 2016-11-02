# jQuery - zadania domowe
> Kod wpisz w odpowiednim pliku, zgodnie z poleceniem zadania.
BARDZO WAŻNE - Wasze zadania są sprawdzanie przy pomocy automatycznego systemu. Żeby odpowiedzi zostały uznane za poprawne strony MUSZĄ wyświetlać te same komunikaty co w treści zadania, a funkcjie i metody MUSZĄposiadać nazwy dokładnie takie same jak podane w zadaniu.

> Zadania z dopiskiem "dodatkowe" są dla chętnych. Znajdziesz je na końcu.

### Dzień 1 - jQuery
> Zadania z tego dnia wykonuj w pliku dzienPierwszy.js

#### Zadanie 1

Zajrzyj do pliku ```index.html```. Jest tam sporo elementów. Za pomocą jQuery znajdź wszyskie elementy z klasą ```border``` i nadaj im dowolne obramowanie.

#### Zadanie 2

Zajrzyj do pliku ```index.html```. Znajdź element o id ```menu``` i zapisz do zmiennej.
Zapisz do innej zmiennej również wszystkie dzieci tego elementu. Napisz kod, który zamieni
tekst ostatniego dziecka na "Jestem ostatnim dzieckiem".

#### Zadanie 3

Zajrzyj do pliku ```index.html```. Zapisz o zmiennej elementy menu. Ustaw każdemu z nich kolor tekstu na taki jaki mają ustawiony w atrybucie `data-color`.


### Dzień 2 - jQuery
> Zadania z tego dnia wykonuj w pliku dzienDrugi.js

#### Zadanie 1 - Prosta animacja

Zajrzyj do pliku ```index.html```. Napisz kod, za pomocą którego po najechaniu na którykolwiek
obrazek uniesie się on lekko do góry (dokładniej mówiąć o 10px). Po zjechaniu powinien wrócić do poprzedniej
pozycji. Wykorzystaj jakąś animację.

#### Zadanie 2 - Dodawanie tagów

Znajdź w pliku `index.html` element ```userPanel```. Jest w nim pole typu ```input``` oraz element o klasie ```panel```. Napisz kod, za pomocą którego tekst wpisany do pola input zostanie ( po wciśnięciu w przycisk `Wstaw` ) dodany do elementu o klasie ```panel```. Tekst powinien być dodawany jako span `span` z klasą **tag**.


### Dzień 3
> Zadania z tego dnia wykonuj w pliku dzienTrzeci.js

#### Zadanie 1
Dokończ warsztaty jeśli nie skończyłeś na zajęciach. Jeśli masz skończone powtórz materiał.

### Dzień 4 - Ajax
> Zadania z tego dnia wykonuj w pliku dzienCzwarty.js

#### Zadanie 1 - Galeria zdjęć

Znajdź w pliku `index.html` element ```gallery```. Jest to sekcja, w której znajduje się pusta lista ```ul```.
Twoim zadaniem jest stworzenie galerii z obrazkami :). Obrazki pobierz z api udostępnionego przez serwis jsonplaceholder.
Wczytaj plik ```json``` z adresu https://jsonplaceholder.typicode.com/photos
Kolejne obrazeki wstawiaj do kolejnych elementów ```li```. Dodaj do galerii tylko 10 obrazków, nie więcej.

Efekt powinieć wyglądać mniej więcej tak:
![galeria](images/galeria.png)

-----------------------------------------
<!--- Czekam az bedzie api
### Dodatkowe

#### Zadanie 1 - Lista ToDO


W folderze ```toDO``` znajdziesz pliki potrzebne do stworzenia listy toDO.
Spróbuj zrobić je za pomocą jQuery, zapisując i usuwając elementy z serwera. Wykorzystaj AJAX.

Pod adresem http://api.coderslab.pl/todoList są przechowywane elementy listy toDO.
Lista ta ma spełniać następujące założenia:

1. Po wpisaniu zadania i naciśnięciu guzika ```Add task``` do listy ma zostać dodane nowe zadanie (z wpisaną odpowiednią treścią). Jednocześnie ma się wyświetlić guzik służący do oznaczenia tego zadania jako zrobione oraz guzikiem służącym do usunięcia tego zadania (przykładowe zadanie jest zakomentowane w HTML).
Zadanie powinno również zostać zapisane na serwerze.

2. Po naciśnięciu na guzik ```Complete``` treść zadania ma się zmienić na kolor czerwony (jeżeli zadanie jest zrobione). Po ponownym naciśnieciu zadanie wraca do koloru domyślnego (czyli oznaczającego zadanie niezrobione).

3. Po naciśnieciu guzika ```Delete``` zadanie ma zniknąć z listy.
Zadanie powinno również zostać usunięte z serwera.

4. Po naciśnięciu guzika ```Remove finished tasks``` wszystkie zrobione zadania mają zniknąć z listy.
Zadania powinny również zostać usunięte z serwera. Pokaż użytkownikowi komunikat czy jest pewien tego że wszystkie elementy listy zostaną usunięte.

5. Zadanie może być dodane tylko gdy jego treść ma więcej niż pięć, a mniej niż sto znaków.

6. Po dodaniu zadania wartość inputa ma się zerować.

7. Ponad listą ma się znajdować licznik pokazujący, ile zadań zostało nam do zrobienia.
-->
