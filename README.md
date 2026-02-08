# myTime.site

Diese Seite wird über **GitHub Pages** (GitHub Actions Workflow) aus dem `main`-Branch veröffentlicht.

## Deployment

1. Im GitHub-Repo unter **Settings → Pages** als *Build and deployment* die Option **GitHub Actions** wählen.
2. Änderungen nach `main` pushen – der Workflow `Deploy to GitHub Pages` veröffentlicht automatisch.
3. Die veröffentlichte URL steht im Workflow-Run unter dem Schritt **Deploy to GitHub Pages**.

## Lokale Vorschau

Die Dateien sind statisch. Öffne `index.html` direkt im Browser oder starte einen simplen Server, z. B.:

```bash
python3 -m http.server
```
