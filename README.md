# Rozkład Jazdy 🚌

Rozkład busów na trasie **Ruda – Kielce** (KOWMAR zwykły, KOWMAR szybki, MAJCHRAK).  
Działa jako **PWA** — można zainstalować na telefonie jak aplikację.

🌐 **Strona:** `https://TWOJA-NAZWA.github.io/NAZWA-REPO/rozklad.html`

## Funkcje

- Dwa kafelki live: **do Kielc** i **z Kielc** z odliczaniem co sekundę
- Fallback na **jutro** gdy dziś nie ma już kursów
- Przełącznik dnia: Pon–Pt / Sobota
- Przełącznik przewoźnika i kierunku z animacją busa 🚌
- Tryb ciemny / jasny
- Działa **offline** (service worker)
- Instalowalna jako apka (PWA)

## Struktura plików

```
├── index.html       ← przekierowanie do rozklad.html
├── rozklad.html     ← główna aplikacja
├── manifest.json    ← konfiguracja PWA
├── sw.js            ← service worker (offline)
├── icon-192.svg     ← ikona apki 192×192
├── icon-512.svg     ← ikona apki 512×512
└── .github/
    └── workflows/
        └── deploy.yml  ← auto-deploy na GitHub Pages
```

## Wrzucenie na GitHub

```bash
git init
git add .
git commit -m "init: rozkład jazdy PWA"
git branch -M main
git remote add origin https://github.com/TWOJA-NAZWA/NAZWA-REPO.git
git push -u origin main
```

Potem: **Settings → Pages → Source: GitHub Actions** — gotowe.

## Instalacja jako apka

- **Android / Chrome:** otwórz stronę → menu → *Dodaj do ekranu głównego*
- **iPhone / Safari:** *Udostępnij* → *Do ekranu początkowego*
