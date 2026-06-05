#Befehle-Übersicht

## Git-Befehle

| Befehle | Was er macht |
|---------|--------------|
| `git init`| Erstelle ein neues lokales Repository |
| `git status`| Zeigt was sich geändert hat |
| `git add datei.md | Einzelne Datei vormerken | 
| `git add .` | Alle Änderungen vormerken |
| `git commit -m "..."` | Schnappschuss mit Nachricht erstellen |
| `git push` | Commits zu GitHub schieben |
| `git push -u origin main` | Erster Push mit Tracking-Verknüpfung |
| `git push -u origin name` | Branch erstmalig zu GitHub pushen |
| `git push --set-upstream origin name` | Dasselbe, ausgeschrieben |
| `git pull` | Änderungen von GitHub holen |
| `git clone URL` | Repo von GitHub auf Festplatte kopieren |
| `git remote add origin URL` | GitHub-Repo verknüpfen |
| `git remote set-url origin URL` | Remote-URL korrigieren |
| `git remote -v` | Verknüpfte Remote-URLs anzeigen |
| `git log --oneline` | Kurze Commit-Historie anzeigen |
| `git diff` | Ungespeicherte Änderungen anzeigen |
| `git branch` | Alle Branches anzeigen |
| `git branch -a` | Alle Branches anzeigen (lokal + remote) |
| `git branch name` | Neuen Branch erstellen |
| `git branch -d name` | Branch lokal löschen |
| `git checkout name` | In einen Branch wechseln |
| `git checkout -b name` | Branch erstellen und direkt reinwechseln |
| `git merge name` | Branch in aktuellen Branch mergen |
| `git rm --cached datei` | Datei aus Git entfernen ohne sie von der Festplatte zu löschen |
| `git config --global user.name "..."` | Namen für Git-Commits setzen |
| `git config --global user.email "..."` | E-Mail für Git-Commits setzen |


## GitHub CLI

| Befehl | Was er macht |
|--------|-------------|
| `gh auth login` | Bei GitHub einloggen |
| `gh repo create name` | Neues Repo auf GitHub erstellen |

## Terminal-Befehle

| Befehl | Was er macht |
|--------|-------------|
| `ls` | Dateien im aktuellen Ordner anzeigen |
| `ls -la` | Auch versteckte Dateien anzeigen |
| `pwd` | Aktuellen Pfad anzeigen |
| `touch datei.md` | Leere Datei erstellen |
| `cat > datei.md << 'EOF'` | Datei mit Inhalt erstellen |
| `code datei.md` | Datei in VS Code öffnen |
| `mkdir name` | Neuen Ordner erstellen |
| `cd ordner` | In einen Ordner wechseln |
| `cd ..` | Einen Ordner zurück |
| `rm datei` | Datei löschen |
| `mv alt.md neu.md` | Datei umbenennen oder verschieben |
| `open .` | Ordner im Finder öffnen |
| `history` | Zuletzt eingetippte Befehle anzeigen |
| `brew install name` | Software installieren (Mac) |

## Markdown-Elemente

| Syntax | Was es macht |
|--------|-------------|
| `# Titel` | H1 Überschrift |
| `## Abschnitt` | H2 Überschrift |
| `### Unterabschnitt` | H3 Überschrift |
| `**fett**` | Fetter Text |
| `*kursiv*` | Kursiver Text |
| \`code\` | Inline-Code |
| \`\`\`bash | Codeblock mit Highlighting |
| `- Punkt` | Aufzählungspunkt |
| `  - Unterpunkt` | Eingerückter Unterpunkt |
| `- [x] Erledigt` | Checkbox angehakt |
| `- [ ] Offen` | Checkbox offen |
| `[Text](datei.md)` | Link |
| `> Zitat` | Zitatblock |
| `---` | Horizontale Linie |
| `\| Spalte \| Spalte \|` | Tabelle |