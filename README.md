# BMI-Rechner (Web-App)

Eine einfache und intuitive Web-App zur Berechnung des **Body-Mass-Index (BMI)**.  
Die App ermöglicht die Eingabe von Körpergröße und Gewicht und liefert auf dieser Basis sowohl den BMI-Wert als auch eine Einordnung gemäß gängigen Gesundheitskategorien.

> **Hinweis:** Die berechneten Werte dienen zur Orientierung und ersetzen **keine medizinische Beratung**.

## Hintergrund

Der **Body-Mass-Index** ist ein verbreiteter Kennwert zur groben Einschätzung des Körpergewichts im Verhältnis zur Körpergröße.  
Er wird häufig verwendet, um mögliche Risiken in Bezug auf Über- oder Untergewicht zu erkennen.

Diese Web-App entstand im Rahmen des folgenden **Blogbeitrags:** https://www.cherware.de/reflect-it/807/

## Features

- Direkte Berechnung des BMI-Wertes auf Basis von Größe und Gewicht
- Automatische Einordnung in etablierte Kategorien (z. B. Normalgewicht, Übergewicht)
- Klar strukturierte und benutzerfreundliche Oberfläche
- Läuft vollständig im Browser (kein Server, kein Tracking)
- Speichert eingegebene Werte (Gewicht und Größe) lokal und stellt sie beim nächsten Aufruf automatisch wieder her
- Bietet einen "Eingaben zurücksetzen"-Button, der Felder leert, lokale Daten löscht und den Hinweistext zurücksetzt

## Bedienung

- Körpergröße in Zentimetern und Gewicht in Kilogramm eingeben.
- Der BMI-Wert und die Kategorie werden unmittelbar angezeigt.
- Beim erneuten Öffnen werden die letzten Eingaben automatisch geladen und neu berechnet.
- Mit dem Button "Eingaben zurücksetzen" lassen sich Felder und gespeicherte Daten in einem Schritt löschen.

## Technologie

- **HTML**
- **CSS** (Tailwind via CDN)
- **JavaScript (client-side only)**

Keine Installation notwendig.

## Kurzer Smoke-Test (lokal)

1. Repository klonen oder herunterladen und die `index.html` im Browser öffnen (kein Build nötig).
2. Gültige Werte eingeben (z. B. 180 cm, 75 kg) und prüfen, dass BMI-Wert und Kategorie angezeigt werden.
3. Seite neu laden und sicherstellen, dass die zuletzt eingegebenen Werte automatisch wiederhergestellt werden.
4. Auf **„Eingaben zurücksetzen“** klicken und kontrollieren, dass Felder, Anzeige und lokale Speicherung gelöscht werden.

## Hinweise

- Minimalistisches, kartenbasiertes UI mit modernen Buttons.
- Footer-Hinweis: "created by cherware.de, 2025".
