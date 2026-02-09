# PDF Maßband (GitHub Pages)

## Zweck
Ein kleines Web-Tool zum Messen in PDFs:
- 2x Tippen (Punkt A, Punkt B)
- Papiermaß (mm/cm) + Realmaß (m) via Maßstab 1:n
- Blattgröße frei wählbar (Auto/A4/A3/A2/Custom)

## Wichtig
Auf iPhone/iPad funktioniert das am zuverlässigsten über **HTTPS** (z. B. GitHub Pages).
Lokal aus der Dateien-App (`file://`) kann iOS/Safari Web-Worker/Imports blockieren.

## GitHub Pages Setup
1. Neues Repo anlegen (z. B. `pdf-messen`)
2. Diese `index.html` ins Repo (Root) hochladen
3. Repo → Settings → Pages → Branch `main` + Folder `/ (root)`
4. Fertige URL öffnen, optional: Safari → Teilen → „Zum Home-Bildschirm“

## Quellen
PDF.js CDN (cdnjs):
- https://cdnjs.com/libraries/pdf.js
Mozilla PDF.js:
- https://github.com/mozilla/pdf.js
