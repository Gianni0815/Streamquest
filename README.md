# StreamQuest – PWA MVP

StreamQuest ist ein responsiver Web-App-Prototyp für iPhone und Windows 11.

## Enthalten
- Dashboard mit XP und Leveln
- Quests für Streaming und Social Media
- Wochenziel und Streaming-Kalender
- Freischaltbare Erfolgs-Abzeichen
- Speicherung im lokalen Browser
- PWA-Manifest und Service Worker für Installation/Offline-Grundfunktionen

## Wichtig
Lokale Speicherung wird nicht zwischen iPhone und PC synchronisiert. Dafür brauchen wir später einen Backend-/Cloud-Dienst und Nutzerkonten. Push-Benachrichtigungen und Twitch-Anbindung sind noch nicht enthalten.

## So testest du es auf Windows 11
1. Entpacke das ZIP.
2. Lade die Dateien auf einen statischen HTTPS-Host hoch (zum Beispiel GitHub Pages oder Netlify).
3. Öffne die veröffentlichte HTTPS-Adresse in Microsoft Edge oder Chrome.
4. Wähle im Browser-Menü „App installieren“ bzw. „Diese Website als App installieren“.

## So installierst du es auf dem iPhone
1. Öffne die veröffentlichte HTTPS-Adresse in Safari.
2. Tippe auf „Teilen“.
3. Wähle „Zum Home-Bildschirm“ und bestätige.
4. Starte StreamQuest über das neue Symbol.

## Lokaler Test
Die Datei `index.html` lässt sich direkt öffnen, um die Oberfläche zu testen. PWA-Installation und Service Worker funktionieren aber regulär nur über HTTPS oder localhost.

## Nächster Entwicklungsschritt
Cloud-Synchronisierung, Benutzerkonto und optional Twitch-Integration ergänzen.
