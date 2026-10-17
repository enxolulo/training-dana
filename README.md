# Trainingsfreund

Trainings-App mit einem kleinen Tier, das mit dem Training wächst. Läuft ohne Server, alle Einträge bleiben auf dem Handy.

## Einrichten
1. Auf github.com ein neues Repository anlegen, Name `trainingsfreund`, Sichtbarkeit Public.
2. Alle Dateien aus diesem Ordner hochladen (die Dateien selbst, nicht den Ordner) und mit Commit changes bestätigen.
3. Settings, Pages: Deploy from a branch, Branch `main`, Ordner `/ (root)`, Save.
4. Nach ein bis zwei Minuten läuft die App unter `https://NAME.github.io/trainingsfreund/`.

## Auf den Home-Bildschirm
In Safari öffnen, Teilen, Zum Home-Bildschirm. Einträge immer in der Home-Bildschirm-App machen, sie hat einen eigenen Speicher.

## Aktualisieren
`index.html` ersetzen und in `sw.js` die Nummer in `const V=` erhöhen.
