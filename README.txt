PERSONAL COMMAND CENTER — PCC 0.2

To jest instalowalna aplikacja webowa (PWA), nie natywna aplikacja APK.

ZAWARTOŚĆ:
- index.html — aplikacja
- manifest.webmanifest — ustawienia instalacji
- sw.js — cache aplikacji/offline shell
- icon.svg — ikona

WAŻNE:
Aby zainstalować PCC na Androidzie jak aplikację, pliki muszą być opublikowane pod adresem HTTPS.
Samo otwarcie index.html z folderu/Pobranych pozwala przetestować stronę, ale nie zapewnia instalacji PWA.
Po opublikowaniu otwórz adres w Chrome i wybierz „Zainstaluj aplikację” lub „Dodaj do ekranu głównego”.

FUNKCJE:
- zegar i data
- pogoda dla Radomia
- lokalny kalendarz wydarzeń (LocalStorage)
- wiadomości (Google News RSS przez rss2json)
- kursy walut (Frankfurter API)
- mapa OpenStreetMap
- responsywny interfejs mobilny

Wymagane połączenie z internetem dla pogody, wiadomości, kursów walut i mapy.
Kalendarz i podstawowy szkielet interfejsu działają lokalnie.
