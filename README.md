# Meri – KI im Service (Impuls)

Interaktive, dreisprachige Präsentations-App (Single-File HTML) zum Thema **KI im Industrieservice** für **Meri – Sustainable Environmental Solutions**.

Erstellt als Impuls von **Tobias Stein**.

## Features

- **Single-File**: alles in `index.html` (HTML/CSS/JS), keine Abhängigkeiten, kein Build.
- **Dreisprachig**: Deutsch · English · 中文 — live umschaltbar oben rechts.
- **7 Story-Schritte**: Frage → Werkzeug → Beweis → Kreislauf → Flotte → Modell → Antwort.
- **Live-Demo**: Service-Copilot mit Anlagenkontext und Telemetrie am Beispiel des **LION Shredder** (Drehzahl, Hydraulikdruck, Drehmoment-Spitzen, Öltemperatur).
- **Animationen**: Flywheel pro Kunde und globaler „Fleet Intelligence"-Kreislauf.
- **Meri-CI**: blau-dominant mit grünem Akzent, passend zum Logo.

## Starten

Einfach `index.html` im Browser öffnen. Für die Präsentation **F11** (Vollbild), mit den Pfeiltasten **←/→** navigieren, **Pos1** springt auf die erste Folie.

### Login

Leichtgewichtiges Demo-Login-Gate:

- Benutzername: `meri`
- Passwort: `meri2026`

Änderbar in `index.html` unter `const CREDS`.

## Optional: als Website veröffentlichen (GitHub Pages)

Repo-Settings → **Pages** → Branch `main`, Ordner `/root`. Da die Datei `index.html` heißt, wird sie automatisch ausgeliefert.

## Hinweis

Alle Telemetrie- und Service-Daten in der Demo sind **geskriptet** und dienen nur zur Veranschaulichung.
