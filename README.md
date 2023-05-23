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

