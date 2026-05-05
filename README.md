# REHAB FIVE — Landing Pages

Statische HTML-Vorschau aller themenspezifischen Landing Pages und Standort-Detailseiten für [rehab-five.com](https://www.rehab-five.com).

## Struktur

- **36 Landing Pages** (`*-landingpage.html`) — Beschwerden, Körperregionen, Zielgruppen, Stadtteile, B2B
- **4 Standort-Detailseiten** (`standort-*.html`) — Scharnhorst, Friedrich-Ebert 127/122, Weseler 71
- **`index.html`** — Übersichtsseite mit kategorisierten Kacheln zu allen Seiten
- **`img/`** — Hero-Bilder und Asset-Bilder für alle Standort- und Themenseiten

## Features

- **Docmedico-Online-Buchung** (`?dmropen=1`) auf jeder Seite
- **„Mehr zum Thema"-Sektion** verlinkt zu rehab-five.com Blog-Artikeln
- **Patientenstimmen** mit Original-Google-Reviews
- **Schema.org-Markup** für Local SEO + Rich Snippets
- **Tailwind CSS via CDN** + Barlow Font

## Lokale Vorschau

```sh
python3 -m http.server 8080
```

Dann im Browser: `http://localhost:8080/`

## Deployment

GitHub Pages — die Seiten sind unter folgender URL erreichbar:
- https://abraemswig-wq.github.io/r5-landing-pages/

## Pflege

Updates am Patientenstimmen-Inhalt: `.r5-reviews/reviews.json` editieren und `update_reviews.py` laufen lassen (außerhalb des Repos).

---

© REHAB FIVE Münster · Inhaber Aric Brämswig
