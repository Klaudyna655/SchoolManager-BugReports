---
name: Błąd Drugi
about: Oceny nie są poprawnie wyświetlane w dzienniku.
title: ''
labels: bug, calculation, grades
assignees: ''

---

**Tytuł błędu:**
Nieprawidłowe wyświetlanie średniej ocen w dzienniku elektronicznym
**Opis problemu:**
W module 'Dziennik' średnia ocen ucznia jest błędnie obliczana. System nie uwzględnia wag ocen
przy obliczaniu średniej ważonej.
**Kroki do reprodukcji:**
1. Zaloguj się jako nauczyciel
2. Przejdź do Dziennik → Oceny → Klasa 4a
3. Wybierz ucznia: Anna Nowak
4. Sprawdź średnią z matematyki
**Oczekiwany rezultat:**
Średnia ważona: 4.2 (obliczona z wagami: sprawdzian waga 5, kartkówka waga 3)
**Rzeczywisty rezultat:**
Wyświetlana średnia: 3.8 (średnia arytmetyczna bez wag)
**Środowisko:**
- System operacyjny: Windows 11
- Przeglądarka: Firefox 121
- Wersja aplikacji: 2.3.1
**Priorytet:**
[ ] Krytyczny
[x] Wysoki
[ ] Średni
[ ] Niski
**Dodatkowe informacje:**
brak
