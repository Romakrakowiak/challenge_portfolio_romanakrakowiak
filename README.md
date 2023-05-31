# challenge_portfolio_romanakrakowiak

# TASK 1
### SUBTASK 1
>_6 Punktow 😉_
### SUBTASK 3
>_HEJ HEJ, mam na imię Roma i jestem tu nie z przypadku :blush: Od kilku miesięcy bardzo mnie interesuje praca jako tester. Dużo czytałam i oglądałam na ten temat żeby się upewnić że chcę rozwijać się w tym kierunku. Więc tak własnie trafiłam tutaj :blush:. Jestem pełna motywacji i z niecierpliwością czekam na kolejne taski i uważam że wiedza zdobyta na tym kursie pomoże mi znależć wymarzoną pracę._
### SUBTASK 4
* W aplikacji można dodawać graczy pilki noznej (imię, nazwisko oraz wiek), ilość zagranych meczy, pozycję na boisku oraz w jakim klubie grają. Do czego slużą te dane - nie wiadomo!
* Funkcjonalność: 
  * logowanie do systemu oraz wylogowanie się z niego
  * opcja dodania nowego gracza
  * wyszukiwarka
  * moźliwość edytowania danych graczy
  * moźliwość sortowania oraz filtrowania graczy
  * opcja zmiany języka na angielski. 
* Interfejs:
  * dość prosty
  * brak ikonek, zdjęć lub video (strona wygląda zbyt pusta)
  * brak logo oraz opisu strony (do czego służy)
  * opcja "dodaj gracza" jest mało wyraźna
  * brak przycisku "edytuj" (dane gracza). Trzeba domyślić jak zedytować 
  * 
  * brak przycisku "anuluj" przy edytowaniu lub dodaniu gracza.
  * przy edytowniu klienta pojawiają sie nowe funkcje strony: raport meczowy oraz opcja dodania meczu.
 * Błędy:
   * przy edytowaniu lub dodaniu gracza przycisk "clear" - nie działa.


# TASK 2
### SUBTASK 1 and 2: [google drive ](https://drive.google.com/drive/folders/1IV53XuGjcY3kJONxKjmzOV2eoz31Q6CY?usp=share_link)
### SUBTASK 3 - For what do we write test cases?
>_A Test Case contains test steps, test data, precondition, postcondition developed for specific test scenario to verify any requirement. These test cases are used by software testers to check if the application works as expected and to identify any bugs or defects that need to be fixed. Writing test cases is an important part of the software development process and is essential for ensuring high-quality software products._
# TASK 3
### SUBTASK 1 and 2: [Google drive](https://docs.google.com/spreadsheets/d/1SETxbfKJBHUZmMRifgrrXUF_OBaIBsBoTS6uFuHjNiI/edit?usp=share_link)
### SUBTASK 3 [TEST REPORT](https://docs.google.com/document/d/1QyetxdFaz0JCLjLLoWMStUinxhV30SAoRlW6ysbDxCU/edit?usp=share_link)
# TASK 4
### SUBTASK 1 and 2: [google drive](https://drive.google.com/drive/folders/1cn22pj7qkaiPsa3pbHg_Z4HHFspJruq-?usp=share_link)
### SUBTASK 3
>_This application helps people to sell things they don't need anymore or to buy things they need. People can literally sell and buy everything there._
>_The end user should probaly be a person that want in an easy and fast way sell or buy things, usually without going out from home._
>_The appliacation is a user friendly and seems to be easy to understand. In a visible places you can find sections buy/sell (deppends on what user needs), sections you need such as real estate, cars, job, pets, etc._ 
>_Nothing would change on this stage._ 


# TASK 5
### SUBTASK 1
>_Zapytania ktorych sie w tym zadaniu nauczylam to: SELECT, INSERT, UPDATE, DELETE._

### SUBTASK 2 and 3
 **1.Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**
 
 SELECT * FROM `actors` ORDER BY surname ASC
 
 <img width="192" alt="2023-05-23_23h02_30" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/201b26fb-d576-4814-8252-028a85c88c8e">

 **2.Wyświetl film, który powstał w 2019 roku.**
 
 SELECT * FROM `movies` WHERE `year_of_production`=2019
 
<img width="259" alt="2023-05-23_23h09_35" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/58078ac6-e47b-4726-b020-d953394432f6">

**3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**

SELECT * FROM `movies` WHERE `year_of_production` BETWEEN 1900 AND 1999

<img width="381" alt="2023-05-23_23h13_39" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/1d6631b1-1792-45f5-83a4-73cad35a7f3d">

**4.Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$**

SELECT `title`,`price` FROM `movies` WHERE `price`<7

<img width="215" alt="2023-05-23_23h21_02" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/5341638d-fe46-46a5-9ace-7153ad158b7c">

**5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**

SELECT * FROM `actors` WHERE `actor_id`>=4 AND `actor_id`<=7

<img width="174" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/8b4c15ca-57ad-4b13-b502-3a5864303302">

**6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**

SELECT * FROM `customers` WHERE `customer_id`=2 OR `customer_id`=4 OR `customer_id`=6

<img width="263" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/df7faa68-9b92-4af3-9042-bbeabc298d7e">

**7.Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**

SELECT * FROM `customers` WHERE `customer_id` IN (1,3,5)

<img width="252" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/68530d5d-7c82-4732-a9bb-1b580a6c4846">

**8.Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**

SELECT * FROM `actors` WHERE `name` LIKE "An%";

<img width="166" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/3d658638-cac4-480e-b958-13ed31bbf2da">

**9.Wyświetl dane klienta, który nie ma podanego adresu email.**

SELECT * FROM `customers` WHERE `email` IS null

<img width="216" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/d0a60cce-0f14-4a71-b81f-ed60a8dfd0e1">

**10.Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**

SELECT * FROM `movies` WHERE `price`>9 AND `movie_id` BETWEEN 2 AND 8

<img width="272" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/91337ec1-c545-4d67-b094-02c4db81760b">


# TASK 6
### SUBTASK 2
>_14 punktow :)

### SUBTASK 1

**11.Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈**

UPDATE `customers` SET `surname`='Miler' WHERE `surname`='Muler'

<img width="261" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/85283068-0605-459d-b95d-0da229d48fe0">

**12.Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.**

SELECT customers.name, customers.email FROM customers INNER JOIN sale ON customers.customer_id = sale.customer_id WHERE sale.movie_id=4

<img width="122" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/0c8a16a8-b26e-4230-ac44-710688a53f97">

**13.Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com**

UPDATE `customers` SET `email`='pati@mail.com' WHERE `name`='Patrycja'

<img width="264" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/0ebb47a6-1a08-45c3-a9a4-b05bea7dc9a7">

**14.Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**

SELECT customers.name, customers.surname, movies.title FROM ((customers INNER JOIN sale ON customers.customer_id = sale.customer_id) INNER JOIN movies ON movies.movie_id = sale.movie_id);

<img width="283" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/74beaa42-ff3f-4d64-a268-9441046c82bd">

**15.W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag**

Dodanie kolumny: ALTER TABLE `customers` ADD `pseudonym` VARCHAR(3) NULL DEFAULT NULL ;

Wypełnienie: UPDATE `customers` SET `pseudonym`= CONCAT(LEFT(`name`,2), RIGHT(`surname`,1))

<img width="328" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/f1a13561-e1be-4d67-85c7-ffe2165575fb">

**16.Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**

SELECT DISTINCT title FROM movies INNER JOIN sale ON movies.movie_id = sale.movie_id

<img width="180" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/a23df558-18b7-4831-ad85-52e940a23112">

**17.Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)**

SELECT name FROM customers
UNION
SELECT name FROM actors
ORDER BY name ASC;

<img width="73" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/74f27968-a7d9-416f-9040-cf54fb08b797">

**18.Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

UPDATE movies SET price = price + 2.5;

**19.Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał**

SELECT actors.name, actors.surname, movies.title FROM ((cast INNER JOIN movies ON movies.movie_id = cast.movie_id) INNER JOIN actors ON actors.actor_id = cast.actor_id) WHERE actors.actor_id = 4;

<img width="160" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/ff7c8b55-0f5b-4e53-abb7-709ab7729635">

**20.A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa**

INSERT INTO `customers`(`customer_id`, `name`, `surname`, `email`, `pseudonym`) VALUES ('7','Honia','Stuczka-Kucharska','honia@mail.com','Hoa');

<img width="372" alt="image" src="https://github.com/Romakrakowiak/challenge_portfolio_romanakrakowiak/assets/131308406/d5748c21-bae8-492d-b7c5-e9a5adae5f02">

