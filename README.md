# Midnight Society 真夜中の会

Website der **Midnight Society**, einer JDM-Tuning-Werkstatt in der Tokyo Street auf dem GTA-RP-Server Corleone City.

## Seiten

| Nr. | Seite | Inhalt |
| --- | --- | --- |
| 01 | Start | Intro, Öffnungszeiten, die vier Säulen |
| 02 | Über uns | Gründer, Team, Vision, Aktivität |
| 03 | Leistungen | Tuning nach Termin, Builds, VIP-Mitgliedschaften |
| 04 | Kunden & Events | Kundenakte, Build-Buch, Treffen und Ausfahrten |
| 05 | Team | Zwölf Ränge, Aufstieg, Kleiderordnung |
| 06 | Hoodie | Crew Hoodie (Orange Edition) als drehbares 3D-Modell |
| 07 | Standort | Halle, Mehrwert für CC, Aufbau in Phasen |

## Dateien

```
index.html    Hauptseite mit allen Unterseiten (Navigation über #start, #team, #hoodie …)
hoodie.html   3D-Ansicht des Crew Hoodies (WebGL 2), auch einzeln aufrufbar
img/          Hintergrundbilder der Unterseiten (bg1.jpg bis bg6.jpg)
```

Die Seite braucht keinen Build-Schritt und keine Abhängigkeiten. Schriften kommen von Google Fonts.

## Online stellen mit GitHub Pages

1. Im Repository auf **Settings → Pages** gehen.
2. Bei **Source** „Deploy from a branch“ wählen, Branch `main` und Ordner `/ (root)`, dann **Save**.
3. Nach ein bis zwei Minuten ist die Seite erreichbar unter
   `https://<github-name>.github.io/<repo-name>/`

Direktlink zum Hoodie: `…/#hoodie` (in der Website) oder `…/hoodie.html` (Vollbild).

## Lokal ansehen

Die 3D-Ansicht wird als eingebettete Seite geladen. Am zuverlässigsten läuft alles über einen kleinen lokalen Server:

```
python -m http.server 8000
```

Dann `http://localhost:8000` im Browser öffnen.
