# VYREL – Vorführung

Die Tablet-Seiten des Pi mit erfundener Fahrt bei Bayerstetten. Nur Beispieldaten, keine Projektunterlagen, mit keiner Maschine verbunden.

Start: https://martldahuim.github.io/vyrel-feldkarte-demo/

- **Anzeige Häcksler** (`/haecksler/`): Kette, Abfahrer neben dem Häcksler, RTK, Längslage, Draufsicht, Maßband, Prüfliste. Alle 5 Minuten eine Runde: Abfahrer kommt, fährt nebenher (kurz nur FLOAT), zieht voll ab, der nächste kommt.
- **Anzeige Abfahrer** (`/abfahrer/`): dasselbe aus Sicht des Fendt.
- **Auftrag** (`/auftrag/`): Aufträge anlegen (Felder auf der Karte antippen), wählen, löschen; Start/Pause/Ende, Stunden je Maschine, Abfahrer ohne Pi. Rolle oben umschaltbar. Was man anlegt, bleibt im eigenen Browser („Von vorn“ setzt zurück).
- **Feldkarte** (`/feldkarte/`): Felder markieren, unten „Für den Pi“ als Auftrag ausgeben.

Quellen:
- Luftbild: Bayerische Vermessungsverwaltung – www.geodaten.bayern.de (DOP20); in der Feldkarte Ersatz: Esri World Imagery
- Feldgrenzen: InVeKoS-Feldstücke Bayern; Ersatz: OpenStreetMap-Mitwirkende
- Feldnamen, Kunden, Fahrten und Stunden sind erfunden.

Gebaut aus dem Projekt mit `rtk/vorfuehrung/bauen.py` (Anzeige und Auftrag sind unveränderte Dateien des Pi; davor hängt nur der Ersatz für die Antworten des Pi).
