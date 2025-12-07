# Changelog

Alle relevanten Änderungen an diesem Projekt werden in diesem Dokument festgehalten.

## [1.1.0] - 2025-05-09
### Hinzugefügt
- Speichert eingegebene Werte für Gewicht und Größe im `localStorage` und lädt sie automatisch beim nächsten Besuch.
- Schaltfläche **„Eingaben zurücksetzen“**, die Felder leert, lokale Daten entfernt und den Hinweistext zurücksetzt.
- Farblich hervorgehobene BMI-Klassifikation (Untergewicht, Normalgewicht, Übergewicht, Adipositas) inklusive Validierung mit Fehlermeldung bei ungültigen Werten.

### Geändert
- Modernisierte Oberfläche mit Tailwind-CSS, responsiver Kartenansicht und klaren Call-to-Action-Buttons.
- Klarere Ergebnisdarstellung mit getrenntem BMI-Wert und Klassifikation.

## [1.0.0] - Erster Release
### Hinzugefügt
- Basisfunktion zur BMI-Berechnung aus Gewicht und Körpergröße.
- Anzeige des berechneten BMI-Werts im Browser.
