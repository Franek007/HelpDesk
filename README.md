# Helpdesk Ticket System

Prosta aplikacja webowa typu **Helpdesk**, umożliwiająca zgłaszanie i zarządzanie problemami w jednym miejscu.  
System może być wykorzystywany w różnych środowiskach, np. w firmach, organizacjach czy instytucjach edukacyjnych.

---

## Cel aplikacji

Aplikacja umożliwia:

- zgłaszanie problemów przez użytkowników
- centralne zarządzanie zgłoszeniami
- śledzenie statusu zgłoszeń
- komunikację między użytkownikiem a administratorem
- dostęp do systemu z dowolnego urządzenia przez przeglądarkę

---

## Role użytkowników

### Użytkownik
- rejestracja i logowanie
- tworzenie nowych zgłoszeń
- przeglądanie swoich zgłoszeń
- sprawdzanie statusu zgłoszeń
- dodawanie komentarzy do zgłoszeń

### Administrator
- przeglądanie wszystkich zgłoszeń
- zarządzanie zgłoszeniami
- zmiana statusu zgłoszeń
- odpowiadanie na zgłoszenia
- dostęp do informacji o zgłaszającym

---

## System zgłoszeń

Każde zgłoszenie zawiera:

- tytuł
- opis problemu
- kategorię
- status
- historię komentarzy

---

## Statusy zgłoszeń

- **New** – zgłoszenie zostało utworzone
- **In Progress** – zgłoszenie jest obsługiwane
- **Resolved** – problem został rozwiązany

---

## Wymagania systemowe

- aplikacja webowa działająca w przeglądarce
- responsywny interfejs (telefon, tablet, komputer)
- bezpieczne przechowywanie haseł (hashowanie)
- komunikacja z serwerem przez HTTPS
- baza danych **NoSQL**

---

## Opcjonalne funkcje

- filtrowanie zgłoszeń
- powiadomienia
- obsługa załączników
- historia zmian zgłoszenia
