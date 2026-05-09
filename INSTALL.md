# INSTALL

## Voraussetzungen

- aktueller Browser
- Internetzugang
- Webcam und optional Mikrofon
- GitHub-Repository für die Veröffentlichung

## Lokal testen

1. Repository klonen oder herunterladen.
2. Im Projektordner einen lokalen Server starten:

```bash
python -m http.server 8000
```

3. Im Browser öffnen: `http://localhost:8000/`

## GitHub Pages aktivieren

1. Repository auf GitHub öffnen.
2. **Settings → Pages** aufrufen.
3. **Deploy from a branch** wählen.
4. Branch `main`, Ordner `/ (root)` auswählen.
5. Speichern.

## Modelle einbinden

Exportierte Teachable-Machine-Modelle können in die Unterordner in `examples/` gelegt und später in eigene HTML-Beispielseiten eingebunden werden.
