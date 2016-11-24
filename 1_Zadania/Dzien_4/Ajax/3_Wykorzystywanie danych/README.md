# Wykorzystywanie danych

> Odpowiedzi wpisz w odpowiednich plikach, chyba że treść polecenia wskazuje inaczej.
Pamiętaj, żeby oddzielać ćwiczenia komentarzami i pisać czytelny, dobrze sformatowany kod.
Jeśli  polecenie w zadaniach brzmi: "Stwórz nową funkcję, w której wykonasz te czynności" to znaczy, że
należy stworzyć funkcję. Nawet jeśli treści zadań są mało skomplikowane
ucz się używać funkcji.


## Zadania do samodzielnego wykonania

# Zadanie 1 (~ 15min - 20min)

Pod adresem https://holidayapi.com/ jest przechowywana baza świąt państwowych różnych krajów.
Aby z niej skorzystać trzeba wygenreować swój klucz API - wejdź na stronę i wygeneruj swój klucz.
Za pomocą funkcji ```ajax()``` wczytaj do elementu **select** wszystkie daty świąt..
Aby poprawnie wczytać dane w funkcji ```ajax()``` trzeba przekazać wymagane parametry,
o których mowa na stronie. **Uwaga**- daty mogą być tylko historyczne (nie bierzący rok).
Każda data powinna być wczytana w elemencie **option** z atrybutem ```value``` o wartości odpowiadającej tej dacie.

# Zadanie 2 (~ 10min - 15min)

Do swojego kodu dodaj nową funkcjonalność- w zależności od wybranej opcji w elemencie **select**
wyświetl nazwę śwęta odpowiadającego wybranej dacie w elemencie **h1**.

# Zadanie 3 - dla chętnych (~ 15min - 20min)

Zadanie polega na tym, aby przy ładowaniu dat do elementu **select** dodawać elementy **optgroup**,
które będą grupowały miesiącami wyświetlane daty. Jeśli w danym miesiącu nie ma święta, **optgroup** także nie powinien być dodawany.
