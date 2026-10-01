# Kinder & Jugend News

Editor und Einbettung für die News im Kinder- und Jugendbereich der Gemeinde in der Konkordia.

- `ankuendigungen-editor.html` – Editor (JSONBin + GitHub-Upload für Bilder)
- `ankuendigungen.html` – Einbettung (Karten-Grid)
- `aktuelles-startseite.html` – Startseiten-Widget (Einträge mit „Auf Startseite zeigen")
- `.github/workflows/fetch-ankuendigungen.yml` – holt alle 2 Stunden das JSONBin nach `data/ankuendigungen.json`

Benötigt: GitHub Pages (Branch `main`, Root), Secrets `JSONBIN_API_KEY` und `JSONBIN_BIN_ID`.
