# Dungeon Village — PWA Prototype

Ein installierbarer, offlinefähiger Vertical-Slice-Prototyp für **Dungeon Village**.

## Enthalten
- Höhlendorf im Querformat
- Desktop: WASD, E, Leertaste, Q, Shift
- Mobile: virtueller Joystick + Action-Buttons
- Taverne mit zufälligen Gefährten
- Party mit bis zu 3 Gefährten
- Dungeon-Run mit 3 Kammern
- Angriff, Runen-Skill und Dash
- normale und Elite-Gegner
- Loot, Rucksack und sichere Bank
- Party-/Loot-Verlust bei Wipe; Bank bleibt bestehen
- lokaler Fortschritt via LocalStorage
- PWA-Manifest, Offline-Service-Worker, App-Icons

## Lokal starten
Service Worker benötigen HTTP/HTTPS. Im entpackten Ordner:

```bash
python -m http.server 8080
```

Dann `http://localhost:8080` öffnen.

## PWA installieren
- Chrome/Edge: Installationssymbol bzw. App-Menü
- iPhone/iPad: **Teilen → Zum Home-Bildschirm**

## Hinweis
Das ist ein spielbarer Web-Vertical-Slice, kein finales Produktionsspiel. Die Systeme sind bewusst kompakt gehalten, damit wir danach gezielt Architektur, Art, Kampf und Content weiterentwickeln können.
