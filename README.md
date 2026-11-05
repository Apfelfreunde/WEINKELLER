# Mein Weinkeller – Handy-Version

Statische PWA für GitHub Pages. Dateien `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg` ins Repository-Hauptverzeichnis laden. Bestehende `index.html` ersetzen. Andere alte Dateien dürfen bleiben.

## Funktionen
- Bestandsimport aus der privaten JSON-Datei (NICHT auf GitHub hochladen)
- Rot-, Weiß-, Süßwein; Bestand, Einkaufspreis, Händler, Trinkfenster
- Kamera-Etikettenfoto, lokal gespeichert und beim Wein angezeigt
- Optional experimentelle Browser-Texterkennung für Jahrgang, falls TextDetector unterstützt wird; sonst manuelle Eingabe
- +1 Flasche, Entnahme mit Datum, persönlicher Bewertung und Notiz
- Recherche-Links für Bewertungen, Trinkfenster und Marktpreise; Quellen und Prüfdatum manuell speichern
- Als App zum Startbildschirm hinzufügen, Grundfunktionen offline nach Erstaufruf

## Wichtige Grenzen
**Noch keine automatische Internet-Aktualisierung:** GitHub Pages allein kann keine geschützten Wein-Datenanbieter abfragen und keine regelmäßigen Hintergrundjobs ausführen. Für automatische Updates sind ein lizenzierter Datenanbieter/API, ein Backend und eine geplante Aktualisierung erforderlich. Die Quellen müssen nach Wein, Cuvée, Jahrgang und Flaschengröße abgeglichen werden.

**Daten sind geräte- und browserlokal**. Es gibt keine automatische Synchronisierung. Häufig JSON-Sicherungen exportieren. Etikettenfotos vergrößern die Sicherungsdatei und können Browser-Speichergrenzen erreichen. Öffentliche GitHub-Repositories niemals mit privatem Weinbestand oder Zugangsdaten befüllen.
