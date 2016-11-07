# JavaScript - egzamin

Zadanie 1-2 rozwiąż w pliku odpowiedzi.txt

Resztę zadań rozwiąż w odpowiednich plikach js.

Nie zmieniaj nic w plikach HTML.

## Zadania:
1. (2ptk) Wytłumacz czym jest i kiedy można używać słowa kluczowego this?

2. (1ptk) Napisz jaka jest różnica w używaniu == i ===.

3. (3ptk) Napisz funkcję longestWord(stringToCheck) która ma zwracać długość najdłuższego słowa znajdującego się w podanym napisie. Jeżeli napis składa się tylko z jednego słowa to funkcja ma zwrócić jego długość. Jeżeli funkcja dostanie inny typ danych niż napis powinna zwrócić wartość -1
Np:
  ```
  longestWord("Ala ma kota");                // => 4
  longestWord("Lorem ipsum dolor sit amet"); // => 5
  longestWord("test");                       // => 4
  longestWord(12);                           // => -1
  ```

4. (5ptk) Używając JavaScript:
  1. Znajdź wszystkie elementy o klasie ```sample_class``` i wypisz w konsoli ich id,
  2. Znajdź element o id ```sample_id``` i dodaj mu klasę ```exercise_2```,
  3. Znajdź wszystkie elementy znajdujące się w zerowym dziecku elementu o klasie ```sample_class_2``` i wypisz znajdujący się w nich tekst,
  4. Znajdź wszystkie linki i wypisz adresy, na które wskazują,
  5. Znajdź element o klasie ```sample_class_3``` i spowoduj że wszystkie jego dzieci będą miały w sobie napis ```jestem i dzieckiem``` (pod ```i``` podstaw odpowiedni numer).

5. (3ptk) Na stronie znajduje się kilka divów i span. Musisz dopisać do nich takie eventy kótre spowodują:
  1. Po najechaniu myszką na diva powinien on urosnąć (zwięszkyć swoją szerokość i wysokość) o wartość którą trzyma w ```data-size```.
  2. Po zjechaniu myszką z diva powinien się on zmiejszać do rozmiarów podstawowych.
  3. W chwili w której myszka jest nad elementem span powinien pokazywać id tego elementu.

6. (6ptk) Używając JavaScript dopisz event do formularza. Event ma reagować na wysłanie formularza. Event ma:
  1. Zapobiegać przeładowaniu strony,
  2. Sprawdzić czy długość danych w polu email jest dłuższa niż 5 zniaków i czy zawiera w sobie znak `@`. Jeżeli warunek nie jest spełniony odpowiednia wiadomość powinna być pokazana w divie o klasie ```error_message```,
  3. Sprawdzić czy wartości pól Hasło i Hasło2 są identyczne. Jeżeli warunek nie jest spełniony odpowiednia wiadomość powinna być pokazana w divie o klasie ```error_message```,
  4. Sprawdzić czy została wybrana poprawna płeć (poprawnymi są wszystkie wybory poza pierwszym),
  5. Jeżeli wszystkie warunki są spełnione w konsoli wyświetl wszyskie informacje z fomularza, a w divie o klasie ```success_message``` wyświetl informację o tym że rejstracja się udała.
