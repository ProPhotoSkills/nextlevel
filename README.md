# ProPhotoSkills – Photoguide Next Level

Eigenständige, statische HTML-Seite (keine Build-Tools, kein Framework) – einfach `index.html` im Browser öffnen oder per GitHub Pages hosten.

## Stack
- Reines HTML/CSS/JS, kein Build-Schritt
- Schrift: [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts CDN
- FAQ-Akkordeon: Vanilla JS (kein jQuery)
- FAQPage-Schema (JSON-LD) für Rich Snippets eingebettet

## GitHub Pages Deploy
1. Repo erstellen, `index.html` ins Root legen (oder `/docs`-Ordner, je nach Branch-Einstellung)
2. Settings → Pages → Branch auswählen → Speichern
3. Seite ist nach kurzer Zeit unter `https://<username>.github.io/<repo>/` erreichbar

## Struktur
Alles in `index.html`: Styles im `<head>`, Markup + Akkordeon-Script + JSON-LD im `<body>`. Bewusst single-file gehalten für einfaches Forken/Anpassen.

## Hinweis
Bilder werden aktuell von `prophotoskills.com`/`nextlevel.prophotoskills.com` referenziert (absolute URLs). Für einen komplett unabhängigen Stand müssten die Cover-Bilder lokal mit ins Repo (z. B. `/assets/`) und die `src`/`background-image`-Pfade entsprechend angepasst werden.
