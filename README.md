# Portfolio_challenge_Natalia_J

## Task 1 
### Subtask 1
7/10 punktów
### Subtask 3
Cześć! Mam na imię Natalia i jestem na etapie przebranżowienia. Aktualnie jestem na "urlopie" macierzyńskim i zależy mi, aby po powrocie znaleźć pracę jako tester manualny. Zdecydowałam się wziąć udział w projekcie, ponieważ zdaję sobie sprawę jak ważne jest posiadanie doświadczenia i praktycznych umiejętności podczas poszukiwania pracy jako tester. Mam nadzieję, że projekt ten pozwoli mi zbudować swoje portfolio, którym będę mogła pochwalić się aplikując o pracę. 
### Subtask 4
* Aplikacja "Futbol Kolektyw" jest to platforma skautingowa, która służy zarządzaniu graczami i meczami piłki nożnej. Dzięki aplikacji możemy uzyskać dane na temat graczy, takie jak np.: wiek, główna pozycja, klub, ilość rozegranych meczów, lub osiągnięcia. Aplikacja umożliwia także tworzenie obserwcji podczas meczu i odtworzenie ruchów zawodnika na boisku oraz tworzenie raportów meczowych. 
* Do funkcjonalności aplikacji należą:
  - logowanie się - służy do zalogowania się do aplikacji poprzez podanie poprawnego loginu i hasła, 
  - przeglądanie listy graczy - strona pokazuje listę wszystkich graczy, wraz z danymi takimi jak: imię, nazwisko, wiek, pozycja, klub, recenzja, mecze i raporty. Umożliwia także posortowanie rosnące lub malejące według każdej grupy danych (oprócz meczów i raportów). Według mnie sortowanie według tych grup danych również powinno być możliwe. Na stronie jest także możliwe ściągnięcie listy w pliku CSV, wydrukowanie, dostosowanie wyglądu tabeli (wybór kolumn, które chcemy widzieć), a także filtrowanie danych. Kliknięcie na danego gracza pozwala nam zedytować dane o nim.      
  - dodawanie i edytowanie graczy - służy do dodawania nowych graczy wraz z informacjami o nich. Zakładka jest niezbyt intuicyjna, ponieważ nie ma możliwości jej zamknięcia. Jedyne przyciski do wyboru to "Submit" lub "Clear".
  - wyszukiwarka graczy - pole z lupką daje możliwość wyszukiwania graczy na podstawie wszystkich danych.
  - przeglądanie statystyk z meczów - służy do przeglądania informacji na temat zagranych przez danego gracza meczów. Podaje nam informacje takie jak: drużyna zawodnika, zdobyte gole, stracone gole, drużyna przeciwnika, data meczu, czas gry, recenzja, autor. W tej zakładce mamy także możliwość edytowania każdego meczu, dodanie raprotu z meczu, oraz rozpoczęcie obserwacji meczu.
  - edytowanie meczów - podobnie jak zakładka edycji graczy - nie ma możliwości jej zamknięcia. 
  - tworzenie raportów z meczów - pozwala na zawarcie w nich takich informacji jak: inteligencja boiskowa, mentalność, dane statystyczne oraz recenzja zawodnika. 
  - odtwarzanie ruchów zawodnika na boisku podczas meczów - funkcjonalność ta była dla mniej najtrudniejsza to odczytania. Moim zdaniem dużym ułatwieniem byłoby dodanie opisów do przycisków nad rysunkiem boiska (po najechaniu na przycisk), a także krótki opis "instrukcja" jak korzystać z tej funkcji aplikacji. 
  - zmiana języka aplikacji - aplikacja przetłumaczona jest na język polski i angielski. 
 * Intefejs aplikacji jest dość prosty, aczkolwiek czytelny. Przyciski są widoczne. Teskt jest klarowny i zrozumiały. 
 * Aplikacja mogłaby być bardziej intuicyjna. Pozwala na wprowadzanie danych w pola, które raczej nie są możliwe (np. cyfry w imieniu lub nazwisku gracza, lub w kolorze koszulki, litery w polu Telefon). Przy dodawaniu nowego gracza aplikacja nie pozwoli nam zapisać formularza, jeśli pole E-mail nie jest uzupełnione w odpowiednim formacie (z "@"), jednak nie ma o tym informacji, musimy sami domyślić się dlaczego. 
* Błędy:
  - W formularzu dodawania nowego gracza możliwe jest podanie minusowej wartości w polu "Waga" oraz "Wzrost", a także podanie daty z przyszłości w polu "Data urodzenia".
  ![image](https://user-images.githubusercontent.com/121819761/212422592-c31db909-45e1-4b30-860c-0a5a24172975.png) 
  - W formularzu edycji meczu możliwe jest wprowadzenie minusowej wartości w polu "Czas gry".
  ![image](https://user-images.githubusercontent.com/121819761/212424791-1584d18e-4647-4f8d-bf0c-69938491c6c9.png)
  - Linki w polach "Niezapisany mecz" nie działają. Otrzymujemy następujący komunikat w DevTools: "Uncaught (in promise) Error: The provided `as` value (/pl/players/6026b48956c79737b3f3c624/reports/start) is incompatible with the `href` value (/players/[id]/reports/start)."
  ![image](https://user-images.githubusercontent.com/121819761/212566732-60287c67-81a2-4d86-abf5-dc635b476171.png)
  - W formularzu edycji meczu możliwe jest podanie minusowej wartości w polu "Numer".
  ![image](https://user-images.githubusercontent.com/121819761/212567557-a75e4eb7-d2b7-4a0a-a336-130fb77e8113.png)

