# Aplikacja lista zadań (To-Do Application)

Aplikacja lista zadań (To-Do Application) to prosta aplikacja webowa, która umożliwia użytkownikom zarządzanie listą zadań. Użytkownicy mogą dodawać, edytować, usuwać oraz oznaczać zadania jako ukończone.

## Architektura aplikacji

Aplikacja jest oparta na architekturze MVC (Model-View-Controller), która zapewnia podział aplikacji na trzy główne warstwy:

- **Model**: Reprezentuje dane aplikacji oraz logikę biznesową.
- **View**: Odpowiada za prezentację danych użytkownikowi w interfejsie użytkownika.
- **Controller**: Zarządza żądaniami użytkownika, przetwarza logikę biznesową i aktualizuje interfejs użytkownika.

## Składniki projektu

Projekt aplikacji lista zadań składa się z następujących głównych składników:

- **Modele (models)**: Reprezentują strukturę danych aplikacji.
- **Kontrolery (controllers)**: Odpowiadają za obsługę żądań HTTP oraz zarządzają logiką biznesową.
- **Repozytoria (repositories)**: Udostępniają interfejs do komunikacji z bazą danych.
- **Konfiguracja (config)**: Zawiera konfigurację aplikacji oraz inicjalizację danych początkowych.
- **Widoki (views)**: Odpowiadają za prezentację danych użytkownikowi w interfejsie użytkownika.

## Technologie użyte

- Spring Boot: Framework do tworzenia aplikacji Java.
- Spring MVC: Framework do tworzenia aplikacji webowych.
- Spring Data JPA: Umożliwia operacje na bazie danych.
- Thymeleaf: Silnik szablonów do tworzenia widoków HTML.
- Lombok: Biblioteka ułatwiająca tworzenie kodu poprzez automatyczne generowanie metod dostępowych.

## Uruchomienie aplikacji

Aby uruchomić aplikację:

1. Skonfiguruj połączenie z bazą danych w pliku `application.properties`.
2. Uruchom aplikację za pomocą klasy głównej (`TodoApplication`) lub użyj narzędzi do budowania projektów Spring Boot.

Po uruchomieniu aplikacji, możesz uzyskać dostęp do interfejsu użytkownika poprzez przeglądarkę internetową pod adresem `http://localhost:8080/`.

## Podsumowanie

Aplikacja lista zadań jest prostym narzędziem do zarządzania codziennymi zadaniami. Dzięki zastosowaniu technologii Spring Boot i Spring MVC, aplikacja zapewnia wygodny interfejs użytkownika oraz umożliwia efektywne zarządzanie listą zadań.

