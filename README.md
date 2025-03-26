# Testy manualne – MrBuggy7 (JIRA-style Bug Report)

Ten projekt zawiera listę błędów zgłoszonych podczas testowania aplikacji **MrBuggy7**.

Poniżej przedstawiono dwa przykładowe zgłoszenia – pełna dokumentacja znajduje się w pliku `.docx`.

---

## 📌 Przykładowe zgłoszenia błędów

### 🔴 Błąd 1 – Brak walidacji pola "Confirm password"

- **Priorytet**: Niski  
- **Opis**: Podczas dodawania nowego administratora brak komunikatu walidacyjnego przy pustym polu "Confirm password".  
- **Kroki do reprodukcji**:
  I. Zaloguj się jako administrator
  II. Przejdź do zakładki “Users”
  III. Kliknij “New Admin”
  VI. Zostaw wszystkie pola puste i kliknij “Save”
- **Rzeczywisty rezultat**: Brakuje komunikatu walidacyjnego dla pola "Confirm password"  
- **Oczekiwany rezultat**: Powinien pojawić się komunikat „This field is required.”  
- **Dowód (film)**: [Zobacz nagranie](https://drive.google.com/file/d/1gD-ZyHXWGRpnlZB1e_9Xz0DpbcmzYyuo/view?usp=sharing)

---

### 🟠 Błąd 2 – Wyszukiwarka ignoruje wielkość liter

- **Priorytet**: Średni  
- **Opis**: Wyszukiwarka w zakładce „Providers” nie rozróżnia wielkich i małych liter.  
- **Kroki do reprodukcji**:
  I. Stwórz dwóch Providerów: „TEST” i „test”
  II. Wyszukaj frazę „test”
- **Rzeczywisty rezultat**: Oba wyniki są traktowane jako różne – brak walidacji  
- **Oczekiwany rezultat**: System powinien wykrywać duplikaty niezależnie od wielkości liter  
- **Dowód (film)**: [Zobacz nagranie](https://drive.google.com/file/d/1srdinhVljyG4Uj0F-2fn9C1N5X_JcHI5/view?usp=sharing)

---

## 🧾 Opis projektu

Dokument przygotowany w formacie przypominającym zgłoszenia do systemu JIRA, zawiera dokładne opisy defektów wraz z:
- Tytułem błędu
- Priorytetem
- Kroki do reprodukcji
- Rzeczywistym i oczekiwanym rezultatem
- Środowiskiem testowym
- Załącznikami (screeny, filmy – linki do Google Drive)

---

## 🧪 Zakres testów
- Walidacja pól formularzy
- Responsywność elementów interfejsu
- Obsługa klawiatury i skrótów
- Wyszukiwarka, filtrowanie, lista wyników
- Obsługa znaków specjalnych i polskich

---

## 🖥️ Środowisko testowe
- System operacyjny: Windows 11
- Przeglądarka: Opera (wersja aktualna)
- Aplikacja: MrBuggy7 (wersja testowa)

---

## 📎 Zawartość repozytorium
- `Jira test aplikacji MrBuggy.docx` – pełna dokumentacja zgłoszonych błędów
- `README.md` – opis projektu + przykładowe zgłoszenia

---

## 📍 Status projektu
Projekt demonstracyjny – część portfolio testera manualnego.  
Zadanie zrealizowane samodzielnie w ramach ćwiczeń testerskich.

