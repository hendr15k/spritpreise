# Spritpreise Deutschland 🇩🇪

Live-Spritpreise und Preisprognose für Deutschland. Zeigt aktuelle Tankstellenpreise auf einer Karte mit Filterung nach Kraftstoffart (E5, E10, Diesel) und Entfernung.

**v10 (03.04.2026):** SEO Meta-Tags, Service-Worker-PWA, National-Scrape-Fix, Aktualisierungs-Timestamps, GitHub-Link

**[Live Demo →](https://hendr15k.github.io/spritpreise/)**

## Features

- **Live-Karte** (Leaflet.js) mit allen Tankstellen in deiner Nähe
- **Preisfilter** — E5, E10, Diesel sortierbar
- **Preisprognose** — Chart.js-Verlauf für Trendvorhersage (nächster Anstieg/Rückgang)
- **Tankerkönig API** — Echte deutsche Marktdaten
- **Dark/Light Mode** — Design nach Tageszeit
- **Sharing** — Teile die günstigste Tankstelle per Link
- **PWA** — Installierbar auf dem Handy, Offline-Support

## Tech-Stack

- Vanilla HTML/CSS/JavaScript
- Leaflet.js (Karten)
- Chart.js (Preisverlauf)
- Tankerkönig API (Tankstellen-Daten)
- Jina AI Reader (Fallback für nationale Durchschnitte)

## Setup

Benötigst einen [Tankerkönig API-Key](https://creativecommons.tankerkoenig.de/) für lokale Tankstellen:

```html
<!-- In index.html ersetzen: -->
const API_KEY = 'DEIN_API_KEY';
```

Nationale Durchschnitte funktionieren auch ohne API-Key über Jina AI Scraping.

## Deployment

GitHub Pages — push to `main` → automatisch live auf `https://hendr15k.github.io/spritpreise/`
