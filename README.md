# Portfolio_challenge_Natalia_J

## :star: Task 1 :star:
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

## :star: Task 2 :star:
### Subtask 1
### Pisanie przypadków testowych na podstawie User Story
https://docs.google.com/spreadsheets/d/1syqu9mJb71_WnkooivLK1zLWJ-v2yaMQrSzOwwVtOYU/edit?usp=sharing
### Subtask 2
### Pisanie przypadków testowych na podstawie “własnych doświadczeń"
https://docs.google.com/spreadsheets/d/1bkr1_z5aCD0tA7HTI9IfEyB1jdgK-0rv5SbLUGD6NGw/edit?usp=sharing
### Subtask 3
### Po co piszemy test case’y?
Przypadki testowe piszemy, aby zaplanować co chcemy przetestować w danej aplikacji. Pisanie przypadków testowych pozwala nam na lepsze zaplanowanie naszej pracy, a także ułatwia nam sprawdzanie czy na pewno przetestowaliśmy wszystko, co chcieliśmy. Na podstawie przypadków testowych możemy budować raporty z przeprowadzonych testów. Są one także źródłem wiedzy dla nowych osób, które dołączają do zespołu.

## :star: Task 3 :star:
### Subtask 2
### Testowanie według planów testów i raportowanie błędów
https://docs.google.com/spreadsheets/d/1BcC22mjQuX5peX6jiFsOTzkBLZ9Dn8q0PMSzjsb14_I/edit?usp=sharing
### Subtask 3
### Raport z wykonanych testów
https://docs.google.com/document/d/143ppGo7Bm9uzuukY2kQC4twtTQvb9AqcUboSy8JxD7Q/edit?usp=sharing

## :star: Task 4 :star:
### Subtask 2
### Testowanie eksploracyjne i raportowanie błędów - aplikacja mobilna
https://docs.google.com/spreadsheets/d/19Cd6dE9-cTbnNsbfb2whdoJUfcf0KW8z8OvX10PbQtQ/edit?usp=sharing
### Subtask 3
### Do czego służy ta aplikacja?
Aplikacja OLX.pl umożliwia kupowanie lub sprzedawanie przedmiotów oraz nieruchomości, a także poszukiwanie lub oferowanie pracy i innych usług. Dzięki aplikacji można publikować ogłoszenia sprzedaży lub oferty pracy. Celem aplikacji jest sprzedaż, kupno lub skorzystanie z różnych usług.

Użytkownikiem końcowym jest zarówno kupujący jak i sprzedający, oferujący lub poszukujący pracy/usług. Użytkownikiem może być każdy korzystający z internetu, gdyż dostęp do aplikacji jest bezpłatny.

Aplikacja OLX.pl jest przyjazna dla użytkownika. Aplikacja działa szybko w sposób responsywny. Bez problemu można rozpoznać do czego służą dane funkcje aplikacji. Firma oferuje wsparcie klienta, aplikacja posiada zakładkę Pomoc, która kieruje nas do Centrum pomocy. Aplikacja posiada wyszukiwarkę, która ułatwia nawigowanie. 
Grafika aplikacji jest przejszysta, a obrazkowe przedstawienie głównych kategorii ułatwia użytkowanie. 

Jeśli chodzi o usprawnienie, to pomocne byłoby, gdyby sprzedane przedmioty z opcją przesyłki olx "znikały" automatycznie z aktywnych ogłoszeń. Poza tym, podczas dodawania ogłoszenia, ilość zapytań o promowanie ogłoszenia może być irytująca dla użytkownika. 
### Subtask 4
https://challangedareit.atlassian.net/jira/software/projects/CHAL/boards/1

## :star: Task 5 :star:
### Subtask 1
SQLa uczyłam się już wcześniej, robiąc kurs na Udemy. Zapytania jakimi potrafię operować to m.in. SELECT, INSERT, UPDATE, DELETE, GROUP BY, ORDER BY, COUNT, INSERT INTO, UPDATE, INNER JOIN, operatory WHERE, AND, OR, NOT, IN, IS NULL, BETWEEN, a także Alias AS. 
### Subtask 3
:question: 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

:arrow_right: SELECT * FROM `actors` ORDER BY surname ASC

![image](https://user-images.githubusercontent.com/121819761/218564256-da6ed609-d51a-4a11-91fa-32e444d3f34d.png)

:question: 2. Wyświetl film, który powstał w 2019 roku.

:arrow_right: SELECT title FROM `movies` WHERE year_of_production = 2019

![image](https://user-images.githubusercontent.com/121819761/218565126-015ee78c-3a37-466f-814c-83cbcfa784f5.png)

:question: 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

:arrow_right: SELECT * FROM `movies` WHERE year_of_production BETWEEN '1900' AND '1999'

![image](https://user-images.githubusercontent.com/121819761/218565638-7a065ebf-85d6-4bec-8f23-769783828161.png)

:question: 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

:arrow_right: SELECT title, price FROM `movies` WHERE price < 7

![image](https://user-images.githubusercontent.com/121819761/218566083-3ae2a49a-5a3c-443d-9a6a-db5643dee0de.png)

:question: 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

:arrow_right: SELECT * FROM `actors` WHERE actor_id >=4 AND actor_id <=7

![image](https://user-images.githubusercontent.com/121819761/218566915-e4b8dcd8-d021-4d6e-ad71-d2b7e37bae5b.png)

:question: 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

:arrow_right: SELECT * FROM `customers` WHERE customer_id % 2 = 0

![image](https://user-images.githubusercontent.com/121819761/218567909-2865483a-76aa-4045-a2eb-825b09273444.png)

:question: 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

:arrow_right: SELECT * FROM `customers` WHERE customer_id IN ('1', '3', '5')

![image](https://user-images.githubusercontent.com/121819761/218568735-b68526f5-1a87-43d9-ab17-822efa69d14e.png)

:question: 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An".

:arrow_right: SELECT * FROM `actors` WHERE name LIKE 'An%'

![image](https://user-images.githubusercontent.com/121819761/218569178-e5fbd1a6-be52-459d-a97c-81df44a40e21.png)

:question: 9. Wyświetl dane klienta, który nie ma podanego adresu email.

:arrow_right: SELECT * FROM `customers` WHERE email IS null

![image](https://user-images.githubusercontent.com/121819761/218569587-33a8687f-13a7-4faf-be35-55972e2461d2.png)

:question: 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

:arrow_right: SELECT * FROM `movies` WHERE price > 9 AND movie_id BETWEEN 2 AND 8

![image](https://user-images.githubusercontent.com/121819761/218570296-0dc233c8-c5b1-4f7e-b9d0-f5b963e896f4.png)

:question: 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój błąd.

:arrow_right: UPDATE customers SET surname = "Miler" WHERE surname = "Muler"

![image](https://user-images.githubusercontent.com/121819761/220195367-869af78b-16f5-4821-8542-fe628bc84ff0.png)

:question: 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila.

:arrow_right:



:question: 13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com.

:arrow_right: UPDATE customers SET email = "pati@mail.com" WHERE email IS NULL

![image](https://user-images.githubusercontent.com/121819761/220197824-4c25f721-edd2-41de-ab5f-069cf1f72f71.png)

:question: 14.


:question: 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

:arrow_right: ALTER TABLE customers ADD pseudonym varchar (40)



![image](https://user-images.githubusercontent.com/121819761/220200067-635e6e2e-fe91-4e0c-a1f0-a362136dd6f3.png)

:question: 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

:arrow_right: SELECT DISTINCT sale.movie_id, movies.title FROM sale INNER JOIN movies on sale.movie_id = movies.movie_id

![image](https://user-images.githubusercontent.com/121819761/220449424-03375051-e53b-4e84-a980-f3a54f2ef3ff.png)

:question: 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

:arrow_right: SELECT name FROM customers UNION SELECT name FROM actors ORDER BY name

![image](https://user-images.githubusercontent.com/121819761/220450642-22b82d5e-6856-4bf9-98ee-38ea50b8ecb3.png)

:question: 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

:arrow_right: UPDATE movies SET price = price + 2.5 WHERE year_of_production > 2000

![image](https://user-images.githubusercontent.com/121819761/220452392-04c04150-73cf-4c0c-ae49-99123106580d.png)





