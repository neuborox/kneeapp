# Knie-Tagebuch

Kleine Web-App (PWA) zum Dokumentieren von Knie-Schmerzen, Schwellung und Training.
Alle Daten bleiben im Browser auf dem jeweiligen Gerät (localStorage), es gibt keinen Server.

## Hosting

- **Netlify:** Ordner entpacken und auf https://app.netlify.com/drop ziehen.
- **GitHub Pages:** Inhalt dieses Ordners ins Repository (Root) hochladen, dann
  Settings → Pages → „Deploy from a branch“ → `main` / `/ (root)`.

HTTPS ist nötig, damit Offline-Modus und Installation funktionieren (bei beiden automatisch).

## Aufs Handy

- **iPhone:** In Safari öffnen → Teilen → „Zum Home-Bildschirm“. Danach immer über das Icon starten,
  denn Safari und die installierte App haben getrennte Speicher.
- **Android:** In Chrome öffnen → Menü (⋮) → „App installieren“.

## Updates

Nach Änderungen an `index.html` reicht es, neu hochzuladen. Werden Schriften oder Icons geändert,
in `sw.js` die Versionsnummer (`knie-tagebuch-v2`) erhöhen.

Schriften: Bebas Neue und Barlow, SIL Open Font License (siehe `fonts/`).
