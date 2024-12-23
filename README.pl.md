# 📚 System Zarządzania Biblioteką
> Oparty na bazie danych system do efektywnego zarządzania książkami, członkami i wypożyczeniami w bibliotece, zaprojektowany w celu usprawnienia operacji bibliotecznych.  

[![pl](https://img.shields.io/badge/lang-pl-red.svg)](./README.pl.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](./README.md)

## Spis treści
* [Informacje ogólne](#informacje-ogolne)
* [Technologie](#technologie)
* [Funkcje](#funkcje)
* [Instalacja](#instalacja)
* [Przykłady](#przyklady)
* [Model związków encji](#model-zwiazkow-encji)
* [Model relacyjny](#model-relacyjny)
* [Status projektu](#status-projektu)
* [Możliwości poprawy](#mozliwosci-poprawy)

## Informacje ogólne
- 📖 **System Zarządzania Biblioteką** to projekt mający na celu uproszczenie zarządzania książkami, członkami i wypożyczeniami w bibliotece.
- 🎓 Projekt został opracowany w ramach zajęć **"Wprowadzenie do baz danych"**, aby zastosować koncepcje projektowania baz danych, normalizacji oraz manipulowania danymi.
- 🛠️ System pozwala bibliotekom na efektywne zarządzanie swoimi operacjami przy jednoczesnym zmniejszeniu nakładu pracy manualnej.
- 🌐 Strona internetowa jest zaprojektowana dla dwóch typów użytkowników:
  - **Bibliotekarze**: Zarządzają książkami, członkami i wypożyczeniami.
  - **Użytkownicy**: Przeglądają wypożyczone książki, terminy zwrotów i historię wypożyczeń.

## Technologie
- ASP.NET Core MVC - do budowy aplikacji internetowej
- EF Core - do zarządzania bazą danych i ORM
- PostgreSQL - jako główny system bazy danych
- JWT Tokens - do uwierzytelniania i autoryzacji
- Tailwind CSS - do stylizacji interfejsu użytkownika

## Funkcje
- **Zarządzanie książkami**: Dodawanie, aktualizowanie, usuwanie i wyszukiwanie książek według tytułu, autora lub gatunku.
- **Zarządzanie członkami**: Rejestrowanie nowych członków, aktualizowanie informacji o członkach i utrzymywanie rekordów.
- **Wypożyczanie i zwroty**: Śledzenie wypożyczonych książek, terminów zwrotu i statusów zwrotów.
- **Wyszukiwanie i filtry**: Zaawansowane możliwości wyszukiwania książek i członków.
- **Raporty**: Generowanie raportów o przetrzymywanych książkach i historii wypożyczeń.

## Instalacja

## Przykłady

## Model związków encji
🖋️ Model ER wizualizuje encje, ich atrybuty oraz relacje między nimi. Diagram ER jest dostępny w pliku [Model związków encji](./docs/LibraryERD.png).

## Model relacyjny
🔗 Model relacyjny to przekształcony model ER na reprezentację tabularyczną pokazujący tabele, klucze i relacje. Diagram modelu relacyjnego jest dostępny w pliku [Model relacyjny](./docs/LibraryRelationalDiagram.png).

## Status projektu
Projekt jest: _w trakcie realizacji_ 🛠️

## Możliwości ulepszeń