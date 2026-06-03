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
| `git pull` | Änderungen von GitHub holen |
| `git clone URL` | Repo von GitHub auf Festplatte kopieren |
| `git remote add origin URL` | GitHub-Repo verknüpfen |
| `git remote set-url origin URL` | Remote-URL korrigieren |
| `git remote -v` | Verknüpfte Remote-URLs anzeigen |
| `git log --oneline` | Kurze Commit-Historie anzeigen |
| `git diff` | Ungespeicherte Änderungen anzeigen |
| `git branch` | Alle Branches anzeigen |
| `git branch name` | Neuen Branch erstellen |
| `git branch -d name` | Branch löschen |
| `git checkout name` | In einen Branch wechseln |
| `git checkout -b name` | Branch erstellen und direkt reinwechseln |
| `git merge name` | Branch in aktuellen Branch mergen |


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