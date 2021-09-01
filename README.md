PLAN TESTÓW PLATFORMY „CODERS GURU” – v. 1.0

|         |       PLAN TESTÓW       |
|:-------:|:-----------------------:|
| Projekt | PLATFORMA „CODERS GURU” |
|  Wersja |        WERSJA 1.0       |

# Metryka dokumentu

|                       |                                                                                                                                                      METRYKA DOKUMENTU                                                                                                                                                     |                             |            |
|:---------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|-----------------------------|------------|
| Nazwa dokumentu:      | Plan testów dla aplikacji „CODERS GURU”                                                                                                                                                                                                                                                                                    |                             |            |
| Nr ID dokumentu:      | 1.1.1                                                                                                                                                                                                                                                                                                                      |                             |            |
| Streszczenie:         | Plan testów aplikacji „CODERS GURU” Platforma łącząca doświadczonych programistów z osobami, które potrzebują wsparcia w rozwiązaniu konkretnego problemu. Umożliwia zdalne połączenie dwóch osób za pomocą czata wideo i tekstowego, wymiany plików i edycji kodu na żywo. Rozliczenia za czas połączenia z wykładowcą. |                             |            |
| Projekt:              | „CODERS GURU”                                                                                                                                                                                                                                                                                                              |                             |            |
| Właściciel dokumentu: | Bartosz Lis                                                                                                                                                                                                                                                                                                                |                             |            |
| Sporządził:           | Bartosz Lis                                                                                                                                                                                                                                                                                                                |                             |            |
| Nr wersji: 1.0        |                                                                                                                                                                                                                                                                                                                            | Data sporządzenia:          | 13.08.2021 |
| Status: Gotowy        | Gotowy                                                                                                                                                                                                                                                                                                                     | Data ostatniej modyfikacji: | 14.08.2021 |
| Zatwierdził:          | Maciej Wlazło                                                                                                                                                                                                                                                                                                              | Data zatwierdzenia:         | 15.082021  |

# Historia zmian dokumentu

|           | HISTORIA ZMIAN DOKUMENTU |            |            |            |       |
|:---------:|:------------------------:|:----------:|:----------:|:----------:|:-----:|
| Nr wersji |           Data           | Opis zmian | Działanie* | Rozdział** | Autor |
|           |                          |            |            |            |       |
|           |                          |            |            |            |       |

```sh
* N - nowy, M – modyfikacja, W – weryfikacja
** Numer rozdziału lub W – wszystkie rozdziały
```

# Lista załączników

|     |      LISTA ZAŁĄCZNIKÓW     |       |
|:---:|:--------------------------:|:-----:|
| Lp. |          Załącznik         | Uwagi |
|  1  | Dokumentacja „CODERS GURU” |       |

# Wykaz użytych skrótów, symboli i terminów

|                          |                                                                                  WYKAZ UŻYTYCH SKRÓTÓW, SYMBOLI I TERMINÓW                                                                                  |       |
|:------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----:|
|       Skrót/termin       |                                                                                                  Znaczenie                                                                                                  | Uwagi |
| Testowanie eksploracyjne | Nieformalna technika projektowania testów, w której tester projektuje testy w czasie, gdy są one wykonywane i wykorzystuje informacje zdobyte podczas testowania do projektowania nowych i lepszych testów. |       |
| Pokrycie wymagań         | stopień, wyrażany w procentach, w jakim zakresie zestaw testowy wykorzystał przedmiot pokrycia.                                                                                                             |       |

# 1. Wprowadzenie

## 1.1. Cel i zakres dokumentu

Plan testów posiada informacje jak będzie przebiegał proces testowy aplikacji „CODERS GURU”. Dokument ma za zadanie
usystematyzowanie zadań testowych i określenie potrzebnego czasu do odpowiedniego testowania danej aplikacji, procesu
testowego i wszystkich działań które zostały podjęte.

## 1.2. Oczekiwania

Podstawowym oczekiwaniem jest aby aplikacja „CODERS GURU” była szczegółowo przetestowana pod kątem wymagań zawartych w
załączonej dokumentacji „CODER GURU”.

# 2. Przedmiot testów

## 2.1. Ogólna charakterystyka produktu

Aplikacja „CODER GURU” ma za zadanie łącznie doświadczonych programistów z osobami które potrzebują wsparcia w
rozwiązaniu konkretnego problemu. Aplikacja umożliwia zdalne połączenie dwóch osób za pomocą czata wideo i tekstowego,
wymiany plików i edycji kodu na żywo.

## 2.2. Użytkownicy i cele produktu

B2C

- Potencjalni kursanci - osoby, które myślą o nauce programowania ale nie wiedzą czym ono jest.
- Uczący się samodzielnie - osoby potrzebujące w procesie edukacji wsparcia mentora.

B2B

- Pakiet dla firm - zbliżone do Grupy 3 – opłacone przez firmy jako benefit dla pracowników.

Celem produktu jest zbudowanie bazy potencjalnych wykładowców oraz powiększenie potencjalnych osób chcących uczyć się
programowania pod okiem doświadczonego mentora.

## 2.3. Elementy podlegające testowaniu

Testowaniu podlega cała aplikacja „CODERS GURU” wg. wytycznych zawartych w dokumentacji załączonej do planu testów w
wersji 1.0.


# 3. Zakres planowanych testów

## 3.1. Wymagania objęte zakresem testów

Wymagania zawarte w załączniku „CODERS GURU” dołączonym do dokumentacji.

```sh
W-FUN – Wymaganie funkcjonalne
W-INT – Wymaganie dotyczące integracji z systemami zewnętrznymi
W-UX – Wymaganie dotyczące użyteczności serwisu
W-BD – Wymaganie dotyczące baz danych
```

## 3.2. Wyłączenie z zakresu testów

Wymagania zawarte w załączniku „CODERS GURU” dołączonym do dokumentacji.

```sh
W-WYD – Wymagania wydajnościowe
W-BEZ – Wymagania bezpieczeństwa
```


# 4. Podejście do testów

## 4.1. Poziom i typ testów

Poziom planowanych testów:

- Testy systemowe

Typ testów:

- testy funkcjonalne
- testy dymne
- testy eksploracyjne

## 4.2. Wykorzystane techniki projektowania testów oraz narzędzia • Techniki czarnoskrzynkowe

- Techniki oparte na doświadczeniu

Narzędzia:

- JIRA

## 4.3. Fazy testów

- Testy modułów
- Testy systemu
- Testy akceptacji


# 5. Kryteria

## 5.1. Kryteria zaliczenia / niezaliczenia testu

Kryteria zaliczenia:

- dostępność testowalnych wymagań, historyjek użytkownika i/lub modeli,
- dostępność elementów testowych, które spełniły kryteria wyjścia obowiązujące na wcześniejszych poziomach testowania,
- dostępność i gotowość środowiska testowego,
- gotowość narzędzi testowych w środowisku testowym,
- dostępność testowalnego kodu,
- dostępność danych testowych.

Warunkiem niezaliczenia:

- brak wymagań testowych, historyjek użytkownika i/lub modeli
- brak elementów testowych, które spełniły kryteria wyjścia obowiązujące na wcześniejszych poziomach testowania,
- problemy środowiska testowego,
- problem z narzędziami testowymi w środowisku testowym,
- brak dostępności testowalnego kodu,
- brak danych testowych.

## 5.2. Warunki rozpoczęcia testów

- Zaakceptowana dokumentacja testowa
- ostępność i gotowość środowiska testowego,
- Gotowość narzędzi testowych w środowisku testowym,
- Przygotowane kopie zapasowe wynikające z procedur odtworzeniowych
- Zaakceptowany harmonogram testów

## 5.3. Warunki zakończenia testów

- Zakończenie sukcesem 100% scenariuszy przypadków testowych
- Pokrycie jak największej ilości przetestowanych wymagań
- Dostępność danych testowych
- Brak otwartych błędów Critical i High dla zakresu scenariuszy testów regresji.
- Brak otwartych błędów kategorii Critical dla pozostałych scenariuszy.

## 5.4. Kryteria zawieszenie i wznowienia testów

Kryteria zawieszenia testów:

- Przekroczenie budżetu
- Przekroczenie ilości czasu poświęconego na projekt
- Problemy z środowiskiem testowym
- Duża ilość wykrytych usterek

Kryteria wznowienia testów:

- Zwiększenie budżetu
- Przedłużenie czasu projektu
- Brak problemów z środowiskiem testowym


# 6. Produkty procesu testowego

- Raport z testów
- Harmonogram testów
- Zarchiwizowana dokumentacja
- W pełni działający produkt końcowy


# 7. Czynności i zadania testowe

- planowanie testów
- monitorowanie testów i nadzór nad testami
- analiza testów
- projektowanie testów
- implementacja testów
- wykonywanie testów
- ukończenie testów


# 8. Środowisko testowe

Komputer w systemem Windows 10 Pro x64 (64 bitowa wersja)

Przeglądarki internetowe:

- Google Chrome: Wersja 91.0.4472.124 (Oficjalna wersja) (64-bitowa)
- Mozilla Firefox: 89.0.2 (64 bitowa wersja)


# 9. Role i odpowiedzialności, potrzeby szkoleniowe

## 9.1. Podział obowiązków procesu testowego

- Planowanie i nadzór: odpowiada Kierownik testów
- Analiza i projektowanie: Tester

## 9.2. Potrzeby szkoleniowe

BRAK


# 10. Harmonogram

    BRAK


# 11. Rejestr ryzyk

## 11.1. Ryzyka projektowe

• czynniki organizacyjne

- braki w umiejętnościach, szkoleniach lub personelu
- problemy kadrowe o problemy polityczne takie jak:

- problemy z testerami komunikującymi swoje potrzeby oraz wyniki testów
- brak reakcji zespołu w związku z informacjami pozyskanymi podczas testów i przeglądów (np. brak doskonalenia procesów
  produkcji i testowania)
- nieprawidłowe nastawienie i oczekiwania od testowania (np. niedocenianie wartości znajdowania błędów podczas
  testowania)

• problemy techniczne

- problemy ze zdefiniowaniem poprawnych wymagań
- stopień, w jakim wymagania mogą zostać spełnione przy istniejących ograniczeniach
- środowisko testowe niegotowe na czas o spóźniona konwersja danych,
- planowanie migracji oraz rozwój i testowanie narzędzi do migracji i konwersji danych o niska jakość projektu, kodu,
  danych konfiguracyjnych, danych testowych i testów

• problemy z dostawcami

- niewywiązywanie się dostawców ze zobowiązań
- problemy z kontraktami

## 11.2. Ryzyka produktowe

- dostarczanie awaryjnego oprogramowania
- możliwość wyrządzenia szkody człowiekowi lub firmie przez oprogramowanie lub sprzęt
- niedostateczne atrybuty oprogramowania (np. funkcjonalność, niezawodność, użyteczność lub wydajność)
- niska jakość lub brak spójności danych (np. problemy z migracją danych, problemy z konwersją danych, problemy z
  przekazywaniem danych, naruszenie standardów danych)
- oprogramowanie, które nie spełnia założonych funkcji