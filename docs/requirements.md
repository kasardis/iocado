# Wymagania

Wymagania (Requirements) określają, co system powinien robić oraz jakie właściwości i ograniczenia powinien spełniać.

Wymagania powinny być jednoznaczne, zrozumiałe i możliwe do zweryfikowania. Opisujemy oczekiwane zachowanie systemu, a nie sposób jego implementacji.


## Oznaczenia

- **FR** (Functional Requirement) — wymaganie funkcjonalne, określające, co system powinien robić.

- **NFR** (Non-Functional Requirement) — wymaganie niefunkcjonalne, określające, jakie właściwości lub ograniczenia powinien spełniać system.

Każde wymaganie posiada unikalny identyfikator, np. `FR-01` lub `NFR-01`.

## Wymagania funkcjonalne

| ID | Wymaganie |
|---|---|
| FR-01 | System umożliwia użytkownikowi zdefiniowanie wymagań kulinarnych. |
| FR-02 | System umożliwia użytkownikowi wyszukanie przepisu zgodnego z wymaganiami kulinarnymi. |
| FR-03 | System umożliwia dodawanie własnych przepisów przez użytkowników. |
| FR-04 | System umożliwia użytkownikowi rejestrację oraz logowanie do konta. |
| FR-05 | System umożliwia użytkownikowi edycję danych profilowych oraz zapisanych wymagań kulinarnych (np. diety, alergie, wykluczone składniki). |
| FR-06 | System umożliwia użytkownikowi ocenienie przepisu. |
| FR-07 | System rekomenduje użytkownikowi przepisy, które zostały dobrze ocenione przez użytkowników o podobnych upodobaniach. |
| FR-08 | System umożliwia zalogowanemu użytkownikowi dodawanie przepisów do listy „Ulubione”. |
| FR-09 | System umożliwia użytkownikowi przeglądanie historii wcześniej przyrządzonych przepisów. |

## Wymagania niefunkcjonalne

| ID | Wymaganie |
|---|---|
| NFR-01 | Dane osobowe użytkowników oraz ich preferencje kulinarne muszą być przechowywane zgodnie z wymogami RODO. |
| NFR-02 | Interfejs użytkownika musi spełniać standardy dostępności WCAG 2.1 na poziomie AA (np. odpowiedni kontrast tekstu, obsługa za pomocą klawiatury). |
| NFR-03 | Interfejs systemu musi być responsywny i poprawnie wyświetlać się na urządzeniach mobilnych oraz stacjonarnych (ekrany o szerokości od 320px). |


## Pytania otwarte
* W jaki sposób będzie dokonywała się moderacja nadsyłanych przepisów?
