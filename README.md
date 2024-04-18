# Projekt Cypress - testy publicznego API - https://httpbin.org/#/ 

## Opis projektu
Repozytorium zawiera serię testów dla publicznego API HTTPBin. W ramach tego zadania zostało wykonanych 11 testów, które uwzględniają różne aspekty:
1. Wykorzystanie różnych metod HTTP, takich jak GET, POST itp.
2. Wysyłanie i sprawdzanie nagłówków, zarówno standardowych (np. User-Agent), jak i niestandardowych.
3. Wysyłanie parametrów zapytania, w tym generowanie wartości losowych.
4. Sprawdzanie treści odpowiedzi zwracanej przez API.
5. Sprawdzanie czasu trwania żądania.

Testy te mają na celu zapewnienie poprawności działania API oraz pokrycie różnych scenariuszy jego użycia.

## Instalacja
1. Sklonuj repozytorium na swój komputer:
    ```
    git clone <adres_url_repozytorium>
    ```
2. Przejdź do katalogu projektu Cypress:
    ```
    cd nazwa_katalogu_projektu
    ```
3. Zainstaluj wszystkie wymagane zależności:
    ```
    npm install
    ```
## Uruchomienie testów
Po zainstalowaniu projektu, możesz uruchomić testy Cypress w terminalu, wykonując polecenie:
    ```
    npm run cypress:open
    ```
    Wybierz odpowiednią przeglądarkę i kliknij na test, który chcesz uruchomić.

## Autor
Autor: Weronika Skarbek
Kontakt: w3r0n1k4sk4rb3k@gmail.com
