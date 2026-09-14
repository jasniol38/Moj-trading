MÓJ TRADING V4 — iPhone

Ta wersja jest przygotowana jako PWA:
- index.html — aplikacja
- manifest.json — instalacja na ekranie głównym
- sw.js — cache/offline po pierwszym uruchomieniu
- ikony PNG

WAŻNE:
iPhone nie uruchamia poprawnie aplikacji JavaScript z lokalnego podglądu Plików.
Żeby V4 działała jak aplikacja na iPhonie, pliki trzeba udostępnić przez HTTPS
(np. GitHub Pages, Netlify lub inny hosting statyczny), a następnie otworzyć
adres w Safari i wybrać „Dodaj do ekranu początkowego”.

Dane dashboardu nadal są przechowywane lokalnie w przeglądarce (localStorage).
