# Arbeitszeit – Web-App für den iPhone-Home-Bildschirm

Rechnet aus Beginn, Ende und Pause die Arbeitszeit aus, als Dezimalstunden (7,75) und in Stunden und Minuten. Gespeicherte Tage stehen in einer Liste mit Summe.

Die Dateien müssen einmal im Internet liegen (nur dann lässt Safari die Seite als App speichern). Danach läuft die App auch ohne Verbindung.

## 1. Ordner online stellen

Du brauchst keinen Mac. Zwei einfache Wege:

- **Netlify Drop:** Die Seite app.netlify.com/drop öffnen und den entpackten Ordner `Arbeitszeit-Web` hineinziehen. Netlify zeigt danach einen Link an.
- **GitHub Pages:** Ein neues Repository anlegen, alle Dateien aus dem Ordner hochladen und unter Settings > Pages die Veröffentlichung einschalten.

Der Link ist öffentlich, die App enthält aber keine persönlichen Daten. Deine Tage werden nur auf deinem iPhone gespeichert.

## 2. Auf dem iPhone als App ablegen

1. Den Link in **Safari** öffnen.
2. Auf das Teilen-Symbol tippen (Quadrat mit Pfeil nach oben).
3. „Zum Home-Bildschirm“ wählen und mit „Hinzufügen“ bestätigen.

Die App öffnet sich danach im Vollbild, ohne Safari-Leiste.

## Gut zu wissen

- Die Liste der Tage liegt getrennt für Safari und für die App vom Home-Bildschirm. Trage Tage deshalb nur in der App ein.
- Wenn du die Dateien später änderst, zähle in `sw.js` die Zahl bei `arbeitszeit-v1` hoch, damit das iPhone die neue Fassung lädt.
