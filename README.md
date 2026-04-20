# ROZKLAD

Prosta aplikacja PWA z rozkładem jazdy, przygotowana tak, żeby działała lokalnie i po wrzuceniu na GitHub Pages.

## Co już ma

- instalowalną apkę PWA
- tryb jasny i ciemny
- animowane przejście autobusu między zakładkami
- licznik najbliższego kursu
- osobne odliczanie dla kierunków
- widok `Tylko dziś` albo `Wszystkie warianty`
- linkowanie do konkretnej zakładki przez hash, np. `#kowmar`

## Jak wrzucić na GitHub

1. Utwórz repozytorium na GitHubie.
2. Wrzuć do niego zawartość tego folderu.
3. W ustawieniach repozytorium wejdź w `Pages`.
4. Ustaw publikację z gałęzi `main` albo `master`, z katalogu `/root`.
5. Po chwili aplikacja będzie dostępna pod adresem GitHub Pages.

## Ważne pliki

- `index.html` - wejście pod GitHub Pages
- `rozklad.html` - główna aplikacja
- `manifest.json` - konfiguracja PWA
- `sw.js` - service worker do cache i pracy offline

## Instalacja jako apka

- Android / Chrome: otwórz stronę i wybierz `Dodaj do ekranu głównego`
- iPhone / Safari: użyj `Udostępnij` -> `Do ekranu początkowego`
