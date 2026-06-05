# Tag 4 — Git Workflow festigt sich

**Datum:** 2026-06-05

## Was habe ich heute gelernt?

- Neuen Branch immer mit -b erstellen: git checkout -b Tag4

- Ohne -b sucht git einen bestehenden Branch und findet keinen

- Beim ersten Push eines neuen Branches immer -u: git push -u origin Tag4

- git pull aktualisiert den lokalen Branch mit dem Stand von GitHub

- Fast-forward bedeutet: keine Konflikte, GitHub konnte einfach vorspulen

## Welches Problem hatte ich?

git checkout Tag4 schlaegt fehl wenn der Branch noch nicht existiert.

git push schlaegt fehl wenn der Branch GitHub noch nicht kennt.

## Wie habe ich es geloest?

git checkout -b Tag4 erstellt und wechselt gleichzeitig.

git push -u origin Tag4 beim ersten Push des neuen Branches.

## Was bedeutet Fast-forward?

Wenn keine parallelen Aenderungen existieren spult GitHub einfach vor.

Kein Merge-Konflikt, keine Rueckfragen - der sauberste Fall.

