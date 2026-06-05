# Tag 6 — Befehle und Rueckblick

**Datum:** 2026-06-05

## Was habe ich heute gelernt?

- befehle.md als Referenz fuer alle Git- und Markdown-Befehle angelegt

- git rm --cached entfernt Dateien aus Git ohne sie lokal zu loeschen

- git config --global setzt Name und E-Mail fuer alle Repos einmalig

- git branch -a zeigt lokale und remote Branches gleichzeitig

- git push --set-upstream nur beim ersten Push eines neuen Branches noetig

## Welches Problem hatte ich?

.DS_Store war bereits committed bevor die .gitignore existierte.

gitignore verhindert nur neue Commits - bereits getrackte Dateien bleiben.

## Wie habe ich es geloest?

git rm --cached .DS_Store entfernt die Datei aus Git.

Danach committen und pushen - auf GitHub ist sie dann weg.

