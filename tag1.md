# Tag 1 — Git & GitHub Grundlagen

**Datum:** 2026-06-02

## Was habe ich heute gelernt?

- Git lokal initialisiert mit `git init`
- GitHub-Repository über das Terminal erstellt mit `gh repo create`
- Lokales Repo mit GitHub verknüpft via `git remote add origin`
- Ersten Commit gemacht und gepusht:
```bash
git commit -m "mein nicht mehr ganz erstes repo"  
git push -u origin main "-u, weil es die initiale erste Verbindung zu github ist. Danach wird es nicht mehr benötigt"
```

## Welches Problem hatte ich?

Der Remote-URL zeigte auf den falschen GitHub-Username (`svenkunkel` statt `skunkelfree`).

## Wie habe ich es gelöst?

Mit `git remote set-url` die URL korrigiert:

```bash
git remote set-url origin git@github.com:skunkelfree/mein-lerntagebuch.git
```
