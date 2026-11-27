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
- Einsatz / Technische Hilfe: Zentrale Lageführung mit ETB, interaktiver Lagekarte (inkl. Zeichenwerkzeugen und Gefahrenzonen-Overlay), Schadenskonten, Kräfte-/FMS-Status- und Helferverwaltung, Kommunikation, ASÜ, Lagebericht und Vordrucken.
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

| **#**  | **Modul / Funktion**                                                                            | **Basis** | **Pro**  | **OV-Lizenz** |
|--------|-------------------------------------------------------------------------------------------------|-----------|----------|---------------|
| **1**  | Zentrale, Lizenz &amp; Systemfunktionen                                                         |           |          |               |
| **2**  | Gerätebindung                                                                                   | 1 PC      | 1 PC     | OV-weit       |
| **3**  | Hotspot-Sync &amp; Einsatztablets (inkl. Rechteverwaltung &amp; Kurzchat)                       | –         | 1 Tablet | Unbegrenzt    |
| **4**  | 100 % Offline-Betrieb &amp; Offline-Karten-Download                                             | ✓         | ✓        | ✓             |
| **5**  | Einsatzleit-Zentrale (Multi-Einsatz-Verwaltung mit strikter Datentrennung)                      | ✓         | ✓        | ✓             |
| **6**  | Einstellbarer PIN-Schutz (Programmstart &amp; kritische Aktionen)                               | ✓         | ✓        | ✓             |
| **7**  | Divera 24/7 Alarm-Übernahme &amp; JSON-Gesamtbackup                                             | ✓         | ✓        | ✓             |
| **8**  | Übergabepaket (PDF-Komplettexport: ETB, Funkplan, ASÜ, Lagebericht)                             | –         | ✓        | ✓             |
| **9**  | Einsatzarten                                                                                    |           |          |               |
| **10** | Einsatz – Einsatztagebuch (ETB / Fb Fü 2, PDF &amp; SHA-256)                                | ✓         | ✓        | ✓             |
| **11** | Einsatz – Interaktive Lagekarte (inkl. Zeichenwerkzeuge)                                    | ✓         | ✓        | ✓             |
| **12** | Einsatz – Schadenskonten-Verwaltung                                                         | ✓         | ✓        | ✓             |
| **13** | Einsatz – Kräfte-, Fahrzeug-, FMS-Status- &amp; Helferverwaltung                            | ✓         | ✓        | ✓             |
| **14** | Einsatz – Lagebericht-Generator                                                             | –         | ✓        | ✓             |
| **15** | Umzüge &amp; Streckendienst (Sperrstellen, Zeitplan, Logistik)                                  | –         | ✓        | ✓             |
| **16** | Bereitstellungsraum (BR: Meldekopf, Satellitenkarte, Stellplätze, Laufzettel)                   | –         | ✓        | ✓             |
| **17** | Fachmodule                                                                                      |           |          |               |
| **18** | Kommunikation &amp; Kontaktverzeichnis (Stamm-/Einsatzkontakte, Fb Fü 45, Skizze &amp; Mermaid) | ✓         | ✓        | ✓             |
| **19** | Vordrucke &amp; Erfassungsbögen (THW-Führung, Einheiten, EBB, Word/PDF)                         | ✓         | ✓        | ✓             |
| **20** | Atemschutz (AGT / ASÜ: Truppüberwachung, Totmannwarner, Flaschenpool)                           | –         | ✓        | ✓             |
| **21** | Materialverwaltung (Bestand, Ausgabe &amp; Rücknahme)                                           | –         | ✓        | ✓             |
| **22** | Wettererfassung &amp; Lagebedingungen                                                           | –         | ✓        | ✓             |
| **23** | Nachschlagewerk &amp; Objektpläne                                                               | –         | ✓        | ✓             |
| **24** | Stabsarbeit (S1–S6: Lagefeststellungen, Aufträge, Schichtbesetzung)                             | –         | ✓        | ✓             |
| **25** | Werkzeuge · Führung &amp; Lage                                                                  |           |          |               |
| **26** | Koordinaten-Umrechner (WGS84 / DMS / UTM / MGRS)                                                | –         | ✓        | ✓             |
| **27** | Schicht-, Ablöse- &amp; Verpflegungsrechner (Fb Fü 42)                                          | –         | ✓        | ✓             |
| **28** | Marschverband-, Kolonnenrechner &amp; LKW-Routenplaner                                          | –         | ✓        | ✓             |
| **29** | Gefahrenzonen- &amp; Wind-Assistent (inkl. ERICards-Suche &amp; Karten-PDF)                     | –         | ✓        | ✓             |
| **30** | Hochwasser-Pegeltrendrechner                                                                    | –         | ✓        | ✓             |
| **31** | QR-Code-Generator (Hotspot, BR-Stellplätze &amp; Material)                                      | –         | ✓        | ✓             |
| **32** | Werkzeuge · Fachtechnik                                                                         |           |          |               |
| **33** | Betriebsstoff &amp; Laufzeiten (Verbrauchs-Tracker &amp; Tankprognose)                          | –         | ✓        | ✓             |
| **34** | Pumpen &amp; Schlauchstrecken (FGr WP / Bergung)                                                | –         | ✓        | ✓             |
| **35** | Stromerzeuger &amp; Phasenlast (NEA / L1–L3)                                                    | –         | ✓        | ✓             |
| **36** | Greifzug &amp; Anschlagmittel (MZ 16 / MZ 32)                                                   | –         | ✓        | ✓             |
| **37** | Abstütz- &amp; Trümmerlast-Rechner (ASH / EGS)                                                  | –         | ✓        | ✓             |
| **38** | Sandsack-Rechner (Deich- &amp; Hochwasserschutz)                                                | –         | ✓        | ✓             |
| **39** | Beleuchtungsplaner (Presets &amp; eigene Lux-Eingabe)                                           | –         | ✓        | ✓             |
| **40** | Gefahrgut / ERICards (Offline-ADR- &amp; Einsatzmaßnahmen-Datenbank)                            | –         | ✓        | ✓             |



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
