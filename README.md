# **SOLIA – System für Operation, Lageführung, Information und Auftragskommunikation**



## Funktionen

### 1. Einsatzführung & Lagedarstellung

- **Lagekarte:** Visuelle Darstellung und grafische Übersicht der aktuellen Einsatzlage, von Einheiten, Gefahren, Abschnitten und Ressourcen auf einer digitalen Karte.
- **Einsatztagebuch (ETB):** Revisionssichere, chronologische Erfassung und Dokumentation aller relevanten Vorkommnisse, Meldungen, Befehle und Entscheidungen im Einsatzverlauf.
- **Einsatzauftrag:** Erstellung, Zuweisung, Nachverfolgung und Dokumentation von konkreten Einsatzaufträgen an Einheiten und Taktische Verbände.
- **Stabsarbeit:** Unterstützung, Koordination und strukturierte Dokumentation der Arbeit des Einsatzleiterstabes und der einzelnen Stabsfunktionen (S1–S6) im Einsatz.
- **Wettererfassung:** Erfassung, Dokumentation und Überwachung von lokalen Wetterdaten und Witterungsbedingungen im Einsatzbereich.
- **Einsatz- & Abschnittsgliederung:** Strukturierte Abbildung der Führungsstruktur (Einsatzleitung, Einsatzabschnitte, Unterabschnitte und unterstellte Einheiten).
- **Schadens- & Gefahrenstellenverwaltung:** Erfassung, Priorisierung und Statusverfolgung einzelner Einsatzstellen oder Schadensobjekte (besonders wichtig bei Flächenlagen wie Unwetter oder Hochwasser).

### 2. Kommunikation & Informationsaustausch
- **Nachrichten (Messenger):** Echtzeit-Kommunikation und strukturierter Austausch von Textnachrichten, Lagemeldungen und Vierfach-Vordrucken zwischen Einsatzkräften und der Einsatzleitung.
- **Kommunikationsskizze:** Erstellung und grafische Darstellung der Funk-, Rufgruppen- und Kommunikationsstruktur im Einsatz.
- **Kontakte & Nachschlagewerke:** Zentrale Verwaltung von Ansprechpartnern sowie Bereitstellung und Durchsuchung von Dokumenten, Vorschriften, Merkblättern und Fachinformationen für den Einsatz.
- **Objektpläne:** Verwaltung, Durchsuchung und Anzeige von Feuerwehr-, Einsatz- und Gebäudeobjektplänen zur schnellen Orientierung vor Ort.

### 3. Kräfte- & Ressourcenmanagement (S1 / S4)
- **Kräfteverwaltung:** Erfassung, Organisation und Verwaltung von Einsatzkräften sowie deren Qualifikationen, Verfügbarkeit und Zuweisung im Einsatz.
- **Fahrzeugverwaltung:** Erfassung, Verwaltung und Statusübersicht (FMS-Status) von Einsatzfahrzeugen und deren taktischer Ausstattung.
- **Materialverwaltung:** Verwaltung, Ausgabe und Nachverfolgung von Einsatzmaterial, Gerätschaften und Verbrauchsgütern im Einsatz.
- **Verpflegungs- & Ablöseplanung:** Bedarfsberechnung und zeitliche Planung von Schichtwechseln, Ruhezeiten sowie Verpflegungs- und Unterbringungskapazitäten bei Langzeiteinsätzen.

### 4. Bereitstellungsraum (BR)
- **BR-Verwaltung:** Erfassung, Registrierung und Organisation von anrückenden Einheiten, Einsatzkräften und Fahrzeugen im Bereitstellungsraum.
- **BR-Karte:** Kartendarstellung und geografische Übersicht des Bereitstellungsraums inklusive Parkplatzkoordinationssystem und Stellplatzzuweisung.
- **BR-Einsatzauftrag:** Direkte Erstellung, Übermittlung und Abrufverwaltung von Einsatzaufträgen an im Bereitstellungsraum wartende Einheiten.

### 5. Atemschutz & Gefahrgut (CBRN)
- **Atemschutzüberwachung:** Digitale Zeit-, Druck- und Statusüberwachung von Atemschutztrupps im Einsatz inklusive automatischer Warn- und Rückzugsalarmierung.
- **Atemschutzsammelstelle:** Verwaltung und Koordination von Atemschutzkräften, Reservegeräten und Flaschenpools an einer zentralen Sammelstelle.
- **GAMS-Regel & Gefahrgut:** Interaktives Handlungsschema für Gefahrguteinsätze (**G**efahren erkennen, **A**bsperren, **M**enschenrettung, **S**pezialkräfte) inklusive Stoffdatenbank und Absperrradien.

### 6. Fachrechner & Logistik-Tools
- **Betriebsstoffrechner:** Berechnung und Verwaltung des Betriebsstoff- und Kraftstoffbedarfs für Einsatzfahrzeuge, Aggregate und Pumpen.
- **Laufzeiten / Spritverbrauch:** Echtzeit-Überwachung und Prognose von Restlaufzeiten sowie des aktuellen Kraftstoffverbrauchs laufender Aggregate und Fahrzeuge.
- **Sandsackrechner:** Berechnung des Bedarfs an Sandsäcken, Füllmaterial, Verbauzeit, Personal und Transportkapazitäten für Hochwassereinsätze.
- **Förderstrecken- & Pumpenrechner:** Berechnung von Druckverlusten, benötigten Pumpenabständen und Wassermengen über lange Wegstrecken (relevant für Feuerwehr und THW).

### 7. System, Vernetzung & Dokumentation
- **Synchronisation über Hotspot (Offline-Mesh):** Automatische lokale Synchronisation mehrerer Endgeräte über einen lokalen WLAN-Hotspot des Hauptgeräts inklusive Rollen- und Rechteverwaltung (Betrachter, Bearbeiter) – komplett ohne Internetverbindung; perspektivisch erweiterbar durch Benutzerkonten und lokalen Serverbetrieb (z. B. auf einem Raspberry Pi).
- **Tableteinbindung (Web-Client):** Bereitstellung der Benutzeroberfläche über einen lokalen Webserver im Browser, sodass Einsatztablets und mobile Endgeräte ohne zusätzliche App-Installation sofort arbeiten können.
-  **Einsatzabschluss & Export:** Automatisierte Erstellung eines gesamten Einsatzberichts (PDF/Excel/JSON) inklusive Einsatztagebuch, Lagekarten-Snapshots, Kräfteübersicht und Funkskizze für die Nachbereitung und Abrechnung.
- **Offline-Kartenmaterial:** Vorab-Download und lokale Speicherung von Kartenkacheln (inkl. Hydranten, Rettungspunkten und Topografie) für den vollwertigen Einsatz ohne Mobilfunknetz.




## Dateistruktur

```
FOKUS/
├── .github/
│   └── workflows/
│       └── build.yml
├── .gitignore
├── LICENSE.md
├── README.md
├── capacitor.config.json
├── logo.ico
├── main.js
├── package.json
├── preload.js
├── scripts/
│   └── generate-gemini-changelog.js
└── www/
    ├── app.js
    ├── assets/
    │   ├── intro.mp4
    │   └── logo.png
    ├── core/
    │   ├── BOS_Funkrufnamen.json
    │   ├── base.css
    │   ├── bos_parser.js
    │   ├── etb_core.js
    │   ├── etb_ui.js
    │   ├── focus_guard.js
    │   ├── handover_bundle.js
    │   ├── leaflet-custom.css
    │   ├── leaflet/
    │   │   ├── leaflet-geoman.css
    │   │   ├── leaflet-geoman.min.js
    │   │   ├── leaflet.css
    │   │   └── leaflet.js
    │   ├── mission_manager.js
    │   ├── offline_tiles.js
    │   ├── qrcode.min.js
    │   ├── sidebar.js
    │   └── sync_client.js
    ├── einsatzarten/
    │   ├── br/
    │   │   ├── br.css
    │   │   ├── br.html
    │   │   └── br.js
    │   ├── einsatz/
    │   │   ├── einsatz.css
    │   │   ├── einsatz.html
    │   │   └── einsatz.js
    │   └── umzug/
    │       ├── umzug.css
    │       ├── umzug.html
    │       └── umzug.js
    ├── fachmodule/
    │   ├── agt/
    │   │   ├── agt.css
    │   │   ├── agt.html
    │   │   └── agt.js
    │   ├── kontakt/
    │   │   ├── kontakt.css
    │   │   ├── kontakt.html
    │   │   └── kontakt.js
    │   ├── material/
    │   │   ├── material.html
    │   │   └── material.js
    │   ├── nachschlagewerk/
    │   │   ├── nachschlagewerk.html
    │   │   └── nachschlagewerk.js
    │   ├── stab/
    │   │   ├── stab.html
    │   │   └── stab.js
    │   ├── vordrucke/
    │   │   ├── templates/
    │   │   │   ├── ebb/
    │   │   │   │   ├── 06-B_ASH_Erfassungsbogen.docx
    │   │   │   │   ├── BT_Erfassungsbogen.docx
    │   │   │   │   ├── B_Erfassungsbogen.docx
    │   │   │   │   ├── BrB_Erfassungsbogen.docx
    │   │   │   │   └── E_Erfassungsbogen.docx
    │   │   │   ├── einheiten/
    │   │   │   │   ├── 39. uebersicht_angeforderte_kraefte.docx
    │   │   │   │   ├── 40_schadensmeldung(1).docx
    │   │   │   │   ├── 41_erkundung_infrastrukturschaeden_gebaude.docx
    │   │   │   │   ├── 42_anforderung_einsatzverpflegung.docx
    │   │   │   │   ├── 43_einsatzabschlussmeldung.docx
    │   │   │   │   ├── 44_technisches_betriebsbuch.docx
    │   │   │   │   ├── 45_funkplan(1).docx
    │   │   │   │   └── 46_gespraechsliste.docx
    │   │   │   └── fuehrung/
    │   │   │       ├── 01_allgemeiner_meldevordruck.doc (Fb Fu 1)(3).docx
    │   │   │       ├── 02_einsatztagebuch.doc (Fb Fu 2).docx
    │   │   │       ├── 03_einsatzauftrag.docx
    │   │   │       ├── 04_ueberwachungsliste.docx
    │   │   │       ├── 05_einsatzuebersicht.docx
    │   │   │       └── 38._nachrichtenvordruck.docx
    │   │   ├── vendor/
    │   │   │   ├── FileSaver.min.js
    │   │   │   ├── docxtemplater.js
    │   │   │   └── pizzip.min.js
    │   │   ├── vordrucke.css
    │   │   ├── vordrucke.html
    │   │   └── vordrucke.js
    │   └── wetter/
    │       ├── wetter.html
    │       └── wetter.js
    ├── hub.js
    ├── index.html
    ├── splash.html
    ├── style.css
    ├── sw.js
    └── werkzeuge/
        ├── betriebsstoff/
        │   ├── betriebsstoff.css
        │   ├── betriebsstoff.html
        │   └── betriebsstoff.js
        ├── ericards/
        │   ├── data/
        │   │   ├── adr_stoffe.json
        │   │   └── ericards.json
        │   ├── ericards.css
        │   ├── ericards.html
        │   └── ericards.js
        ├── licht/
        │   └── licht.html
        └── sandsack/
            └── sandsack.html

```


## **Roadmap**

### In Arbeit
- **Modul Nachschlagewerk**: Verwaltung und Koordination von Atemschutzkräften und -geräten an einer zentralen Sammelstelle


### Geplant

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
