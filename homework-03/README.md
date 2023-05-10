# To do app

Przed wami trzecia praca domowa, w której waszym zadaniem będzie zaplanowanie, zaprojektowanie i zakodowanie aplikacji "to do".

Wymagany stos technologiczny to:
- JavaScript (localStorage do zapisu danych aplikacji)
- HTML
- CSS (layout GRID, FLEXBOX lub GRID + FLEXBOX), style desktop dla width >= 1440px

Podstawowa funkcjonalność aplikacji ma obejmować dodawanie oraz usuwanie nowych zadań (mechanika usuwania może zostać przez was dowolnie zdefiniowana, tzn możecie stworzyć osobny przycisk, wykorzystać drag event, usuwać todos przy pomocy kliknięcia na wcześniej zdefiniowany tekst zadania lub cokolwiek, co przyjdzie wam do głowy)

Rozszerzona funkcjonalność powinna umożliwiać edycję już utworzonych zadań, darkMode, style mobilne aplikacji.

## Ocenie podlegać będą:

1. Plan na zbudowanie aplikacji uwzględniający (**2pkt**):
   - potrzebne funkcje
   - zachowanie aplikacji
2. Design aplikacji (**3pkt**):
   - desktop
   - mobile
   - dark mode
   
   Wystarczy zupełnie ideowy plan na layout. "Fajerwerki" mile widziane choć nie wymagane. Macie wolną rękę w doborze narzędzia do zdefiniowania takiego layoutu - paint, figma, karta i długopis (fotografia pracy zuploadowana na repo w takim przypadku ;])...

3. Jakość kodu (**9pkt**):
   - brak pozostałości po "próbie implementacji" w postaci nieusuniętych komentarzy.
   - funkcje celowo zdefiniowane powinny zostać opatrzone komentarzem tłumaczącym ich działanie, np.

   ```javascript
   /**
      Funkcja pobiera argument będący obiektem o polach "id" oraz "text" i dodaje go do store.
   */

   const addTodo = (todo) => {...}
   
   ```
   - używanie zmiennych i funkcji o adekwatnych nazwach
   - zrealizowane
      - zapis
      - odczyt
      - usuwanie 
      - edycja

      stworzonej listy zadań z localStorage
   - poprawny semantycznie HTML

   ### UWAGA!!!
   Celem poprawnej realizacji zadania potrzebna będzie metoda na rozróżnienie stworzonych zadań między sobą. Możemy przecież mieć dwa takie same zadania oczekujące na wykonanie, jak np "zrób 10 pompek". Będziecie je chcieli zatem rozróżnić. Każde zadanie zapisane w store powinno więc być obiektem zawierającym treść zadania oraz unikalny identyfikator. Skorzystajcie np z `crypto.randomUUID()`;

4. Punkty dodatkowe (**3pkt**):
   - Commitujemy tylko skończone części zadania/funkcjonalności
   - Czytelne commit messages odpowiadające naniesionym zmianom
   - W przypadku zastosowania modułów JS, odpowiednia separacja plików zawierających kod dotyczący poszczególnych części projektu.

5. Praca wykonana na branchu `homework-03` i stworzony pull request (**2pkt**)

### UWAGA!!!
Istnieje możliwość stworzenia pull requesta i oznaczenia mnie jako recenzenta przed ukończeniem całego zadania, ale po zakończeniu któregokolwiek z "głównych punktów", tj. można stworzyć PR i zadać pytanie odnośnie stworzonego przez siebie planu, designu lub jakości kodu. Nie wpłynie to na końcową ocenę w jakkolwiek negatywny sposób, ponieważ całość pracy będzie oceniana dopiero po założonym terminie.

Maksymalna punktacja, jaką można uzyskać to: **19pkt**

Termin oddania pracy: **21.04.2023**.

Zostanie on przedłużony do **23.04.2023** (do północy) w przypadku uzupełniania ankiet.

**POWODZENIA!**

