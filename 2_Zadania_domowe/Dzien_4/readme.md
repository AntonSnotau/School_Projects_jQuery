# jQuery - zadania domowe
> Kod wpisz w odpowiednim pliku, zgodnie z poleceniem zadania.
BARDZO WAŻNE - Wasze zadania są sprawdzanie przy pomocy automatycznego systemu. Żeby odpowiedzi zostały uznane za poprawne strony MUSZĄ wyświetlać te same komunikaty co w treści zadania, a funkcjie i metody MUSZĄposiadać nazwy dokładnie takie same jak podane w zadaniu.

> Zadania z dopiskiem "dodatkowe" są dla chętnych. Znajdziesz je na końcu.

## Dzień 4 - Ajax
> Zadania z tego dnia wykonuj w pliku dzienCzwarty.js

### Zadanie 1 - Galeria zdjęć

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
