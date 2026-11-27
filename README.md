# **SOLIA – System für Operation, Lageführung, Information und Auftragskommunikation**



## Funktionen

### 1. Zentrale & Systemfunktionen
- Einsatzleit-Zentrale (Dashboard): Verwaltung beliebig vieler Einsätze mit strikter Datentrennung, einsatzspezifischem Setup (Einsatz, Umzug, BR), Divera-24/7-Alarmübernahme, dauerhafter Stammdatenspeicherung und komplettem JSON-Backup.
- Einsatztagebuch (ETB / Fb Fü 2): Einsatzspezifisches, revisionssicheres Tagebuch mit automatischen Modul-Einträgen, Storno-Funktion, PDF-Archivierung und SHA-256-Integritätskette.
- Offline-Hotspot & Tablet-Sync: Lokaler Server für Einsatztablets mit Zufalls-PIN, QR-Login, feingranularer Rechte- und Rollenverwaltung (Betrachter/Bearbeiter/Gesperrt) sowie integriertem Einsatz-Kurzchat.
- Offline-Karten: Gebietsspezifischer Download von Straßen- und Satellitenkarten für den 100-%-Offline-Betrieb auf Host und verbundenen Tablets.
- Sicherheit & PIN-Schutz: Einstellbare Sicherheits-PIN für den Programmstart (Sperrbildschirm) sowie zur Absicherung kritischer Einstellungen und Handlungen.
- Übergabepaket & Lizenzsystem: 1-Klick-Export eines vollständigen PDF-Übergabepakets (ETB, Funkplan, ASÜ, Lagebericht, Komplettsicherung), gestaffelte Lizenzstufen (Basis, Pro mit 1 Tablet, OV mit unbegrenzten Tablets) und integrierter Auto-Updater.

### 2. Einsatzarten
- Realeinsatz / Technische Hilfe: Zentrale Lageführung mit ETB, interaktiver Lagekarte (inkl. Zeichenwerkzeugen und Gefahrenzonen-Overlay), Schadenskonten, Kräfte-/FMS-Status- und Helferverwaltung, Kommunikation, ASÜ, Lagebericht und Vordrucken.
- Umzüge & Streckendienst: Strecken- und Sperrstellenverwaltung auf der Karte, Zeitplan-Überwachung (Postenbezug, Vollsperrung, Freigabe), Kräfte-, Fahrzeug- und Logistikkoordination.
- Bereitstellungsraum (BR): Meldekopf-Erfassung mit strukturiertem BOS-Funkrufnamen-Generator, Satelliten- und Parkplatz-/Stellplatzkoordination, Infrastruktur-Planung und Laufzettel-Erstellung.

### 3. Fachmodule
- Kommunikation & Kontaktverzeichnis: Dauerhaftes Stamm- und einsatzbezogenes Kontaktverzeichnis, Funkplan (Fb Fü 45 inkl. Word-/PDF-Export) sowie visuelle Kommunikationsskizze mit eigenen Ebenen und offline-fähigem Mermaid-Diagramm-Editor/-Export.
- Atemschutz (AGT / ASÜ): Live-Truppüberwachung mit Zeit- und Druckkontrolle, Totmannwarner-Check, Regenerationszeiten, Flaschen-/Materialpool und ASÜ-PDF-Export.
- Vordrucke & Erfassungsbögen: Digitale THW-Führungsvordrucke, Einheiten-Formulare und EBB-Erfassungsbögen mit automatischer Datenübernahme und Word-/PDF-Export.
- Materialverwaltung: Bestands-, Ausgabe- und Rücknahmenachweis für Geräte und Einsatzmittel.
- Wettererfassung: Protokollierung von Temperatur, Windrichtung/-stärke, Niederschlag und Unwetterwarnungen mit direkter Übernahme in das Gefahrenzonen-Modul.
- Nachschlagewerk & Objektpläne: Offline-Sammlung für Vorschriften, Melde-/Stärkeschemata sowie eigene Gebäude- und Objektpläne.
- Stabsarbeit (S1–S6): Strukturierte Verwaltung von Sachgebieten, Lagefeststellungen, Stabsaufträgen und Schichtbesetzungen.

### 4. Werkzeuge · Führung & Lage
- Koordinaten (UTM / MGRS / GPS): Umrechnung zwischen WGS84 (Dezimalgrad/DMS), UTM und MGRS mit direkter Übernahme in die Lagekarte.
- Schicht & Verpflegung (Fb Fü 42): Berechnung von Personalbedarf (6h/8h/12h), Schichtwechselzeiten und Verpflegungsrationen.
- Marschverband & LKW-Routenplaner: Kolonnenberechnung (Marschlänge, Durchlaufzeit, Halte, Kraftstoff, Marschbefehl) kombiniert mit einem LKW-Routenplaner (Gewicht, Höhe, Breite, Länge, Achslast, ADR) auf interaktiver Karte.
- Gefahrenzonen & Wind: Berechnung und Darstellung von 3 Schutzzonen (Gefahr, Dekon, Absperrung) und Wind-Ausbreitungssektor mit integrierter ERICards-Gefahrstoffsuche, direktem Lagekarten-Sprung und PDF-Export inklusive Lagekarten-Hintergrund.
- Hochwasser-Pegeltrend: Protokollierung von Pegelständen mit Steig-/Fallrate (cm/h) und Alarm-Prognose.
- QR-Code-Generator: Erstellung druckbarer QR-Schilder für Tablet-Hotspot, WLAN, BR-Stellplätze und Material.

### 5. Werkzeuge · Fachtechnik
- Betriebsstoff & Laufzeiten: Kraftstoffbedarfsrechner, Verbrauchs-Tracker und Laufzeitprognose für Fahrzeuge und Aggregate.
- Pumpen & Schlauchstrecken: Berechnung von Förderhöhe, Schlauch-Reibungsverlusten (F/A/B/C) und Verstärkerpumpen für FGr WP / Bergung.
- Stromerzeuger & Phasenlast: Auslastungs-, Schieflast- und Anlaufstrom-Prüfung (L1–L3) für NEA / FGr E.
- Greifzug & Anschlagmittel: Zugkraftberechnung (MZ 16 / MZ 32), Flaschenzug-Umlenkrollen und Anschlagwinkel.
- Abstütz- & Trümmerlast: Berechnung von Bauteil-/Trümmergewichten, Deckenabstützung, Stützenanzahl und Rastermaß (ASH / EGS).
- Sandsack-Rechner: Bedarfsberechnung für Sandsäcke und Sandmenge (in Tonnen) nach Bauweise, Länge und Dammhöhe.
- Beleuchtungsplaner: Flächen- und Lichtstromberechnung mit Presets oder eigener Lux-Eingabe inklusive LED-Leistung, Strahler-/Powermoon-Richtwerten und Aggregatgröße (kVA).
- Gefahrgut / ERICards: Komplette Offline-Datenbank für UN-Nummern, ADR-Stoffe, Kemler-Zahlen und ERICards-Einsatzmaßnahmen.


## Lizenzmodell

| **Gerätebindung** | 1 PC | 1 PC | OV-weit (keine Bindung) |
| **Offline-Betrieb & Offline-Karten** | Ja | Ja | Ja |
| **PIN-Schutz (Start & kritische Aktionen)** | Ja | Ja | Ja |
| **Realeinsatz (ETB, Lagekarte, Schadenskonten, Kräfte)** | Ja | Ja | Ja |
| **Kontakte, Funkplan & Vordrucke** | Ja | Ja | Ja |
| **Umzüge / Streckendienst & Bereitstellungsraum (BR)** | – | Ja | Ja |
| **Weitere Fachmodule (AGT/ASÜ, Material, Wetter, Stab, Nachschlagewerk)** | – | Ja | Ja |
| **Alle Werkzeuge (Führung & Lage + Fachtechnik)** | – | Ja | Ja |
| **Übergabepaket (PDF-Komplettexport)** | – | Ja | Ja |
| **Hotspot-Sync & Einsatztablets** | – | Bis zu **1 Tablet** | **Unbegrenzt** |


## **Roadmap**

### In Arbeit
- **Wettererfassung:** Erfassung, Dokumentation und Überwachung von lokalen Wetterdaten und Witterungsbedingungen im Einsatzbereich.
- **Stabsarbeit:** Unterstützung, Koordination und strukturierte Dokumentation der Arbeit des Einsatzleiterstabes und der einzelnen Stabsfunktionen (S1–S6) im Einsatz.
- **Modul Nachschlagewerk**: Verwaltung und Koordination von Atemschutzkräften und -geräten an einer zentralen Sammelstelle


### Geplant
Raspberry-Pi basierte Serveranwendung

---

## Lizenz

Copyright (c) 2026 Hannes Reuter

**ALLE RECHTE VORBEHALTEN / ALL RIGHTS RESERVED**

Es ist ausdrücklich untersagt, diese Software, Dateien oder Teile davon ohne vorherige schriftliche Genehmigung desr Urheber:

- herunterzuladen, zu besitzen oder zu speichern,
- zu vervielfältigen, zu kopieren oder zu spiegeln,
- zu verändern, zu dekompilieren oder abgeleitete Werke zu erstellen,
- zu verbreiten, zu veröffentlichen, zu unterlizenzieren oder zu verkaufen,
- für private, schulische, wissenschaftliche oder kommerzielle Zwecke auszuführen oder zu nutzen.

Zuwiderhandlungen stellen eine Verletzung des Urheberrechts dar und werden **zivil- und strafrechtlich** verfolgt.



Mit ❤️ erschaffen von HannesTeuter