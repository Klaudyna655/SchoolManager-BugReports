---
name: Błąd Pierwszy
about: Nauczyciel nie może się zalogować do systemu.
title: ''
labels: bug, critical, login
assignees: ''

---

**Tytuł błędu:**
Błąd logowania - komunikat 'Invalid credentials' przy poprawnych danych
**Opis problemu:**
Użytkownik z rolą 'nauczyciel' nie może się zalogować do systemu pomimo wprowadzenia
prawidłowego loginu i hasła. System wyświetla błąd 'Invalid credentials'.
**Kroki do reprodukcji:**
1. Otwórz stronę logowania (https://schoolmanager.example.com/login)
2. Wpisz login: jan.kowalski@szkola.pl
3. Wpisz hasło: Test123!
4. Kliknij przycisk "Zaloguj"
**Oczekiwany rezultat:**
Użytkownik zostaje zalogowany i przekierowany do panelu nauczyciela
**Rzeczywisty rezultat:**
Wyświetla się komunikat "Invalid credentials" i użytkownik pozostaje na stronie
logowania
**Środowisko:**
- System operacyjny: Windows 11
- Przeglądarka: Chrome 120
- Wersja aplikacji: 2.3.1
**Priorytet:**
[x] Krytyczny
[ ] Wysoki
[ ] Średni
[ ] Niski
**Dodatkowe informacje:**
Update: Problem występuje również w przeglądarce Safari.
Testowałem na macOS Sonoma.
