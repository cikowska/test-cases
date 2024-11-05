# 3. Przypadek testowy

Dodawanie produktów do koszyka

- Dane testowe: dostępne produkty na stronie
- Warunki wstępne: użytkownik znajduje się na stronie listingu produktów w danej kategorii; koszyk jest pusty
- kroki:
  - użytkownik klika w interesujący go produkt na stronie listingu
  - użytkownik klika w przycisk "dodaj do koszyka" na stronie wybranego produktu
- oczekiwany rezultat:
  - użytkownik zostaje przeniesiony na stronę wybranego produktu
  - produkt został dodany do koszyka
- Warunki końcowe: strona listingu produktów wyświetla takie same produkty jak przed kliknięciem w wybrany produkt, w koszyku nie znajdują się produkty

# 4. Przypadek testowy

Wysyłanie zapytania przez formularz kontaktowy

- dane testowe: adres e-mail użytkownika, imię użytkownika, treść wiadomości
- warunki wstępne:
  - użytkownik znajduje się na stronie formularza kontaktowego, pola formularza są puste
- kroki:
  - użytkownik w pole "imię" wpisuje swoje imię
  - użytkownik w pole "adres e-mail" wpisuje swój adres e-mail
  - użytkownik w poe "treść wiadomości" wpisuje swoją wiadomość
  - użytkownik klika w przycisk "wyślij"
- oczekiwany rezultat:
  - w polu "imię" znajduje się imię użytkownika
  - w polu "adres e-mail" znajduje się adres e-mail użytkownika
  - w polu "treść wiadomości" znajduje się wpisana wiadomość
  - wyświetla się wiadomość "wiadomość została wysłana"
- Warunki końcowe: Pola formularza są puste, strona formularza wygląda jak przed wysłaniem wiadomości
