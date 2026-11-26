# **FOKUS: Führungs- Operations- Koordinations- Unterstützungs-System**



## Funktionen

- **Kommunikationsskizze:** Erstellung und Darstellung der Funk und Kommunikationsstruktur im Einsatz
- **Kontakt:** Bereitstellung und Durchsuchung von Dokumenten, Vorschriften, Merkblättern und Fachinformationen für den Einsatz
- **BR Einsatzauftrag:** Echtzeit Kommunikation und Austausch von Nachrichten zwischen Einsatzkräften und der Einsatzleitung
- **BR Karte:** Kartendarstellung und geografische Übersicht des Bereitstellungsraums + Parkplatzkoordinationssystem/zuweisung
- **BR:** Erfassung und Organisation von Anrufern, Einsatzkräften und Fahrzeugen im Bereitstellungsraum
- **Einsatztagebuch:** Chronologische Erfassung und Dokumentation aller relevanten Vorkommnisse, Meldungen und Entscheidungen im Einsatzverlauf
- **Atemschutzsammelstelle:** Verwaltung und Koordination von Atemschutzkräften und geräten an einer zentralen Sammelstelle
- **Atemschutzüberwachung:** Berechnung und Verwaltung des Betriebsstoff und Kraftstoffbedarfs für Einsatzfahrzeuge und Geräte
- **Laufzeiten / Spritverbrauch:** Verwaltung und Anzeige von Feuerwehr und Gebäudeobjektplänen zur Unterstützung im Einsatz
- **GAMS:** Handlungsschema und Merkregel für Gefahrguteinsätze (Gefahren erkennen, Absperren, Menschenrettung, Spezialkräfte)
- **Einsatzauftrag:** Erstellung, Zuweisung und Dokumentation von konkreten Einsatzaufträgen an Einheiten und Kräfte
- **Lagekarte:** Visuelle Darstellung und grafische Übersicht der aktuellen Einsatzlage, von Einheiten, Gefahren und Ressourcen auf einer Karte
- **Sandsackrechner:** Berechnung des Bedarfs an Sandsäcken, Füllmaterial und Transportkapazitäten für Hochwassereinsätze



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

1. Fahrzeugverwaltung:
   - Erfassung, Verwaltung und Statusübersicht von Einsatzfahrzeugen und deren Ausstattung
2. Kräfteverwaltung:
   - Erfassung, Organisation und Verwaltung von Einsatzkräften sowie deren Verfügbarkeit und Zuweisung im Einsatz
3. Modul Betriebsstoffrechner:
   - Erstellung und Darstellung der Funk- und Kommunikationsstruktur im Einsatz

### Geplant

1. Syncronisation über Hotspot:
   - Automatische Syncronisation meherere Geräte über einen Hotspot des Haupgeräts + verschiedene Rollen (Betrachter, Bearbeiter): , später mit Accounts und Server auf einem Raspberry Pi Aber keine verbindung ins Internet
2. Modul Materialverwaltung:
   - Berechnung und Überwachung von Laufzeiten sowie des Kraftstoffverbrauchs von Aggregaten und Fahrzeugen im Einsatz
3. Modul Nachschlagewerk:
   - Verwaltung und Koordination von Atemschutzkräften und -geräten an einer zentralen Sammelstelle
4. Modul Objektpläne:
   - Verwaltung und Anzeige von Feuerwehr- und Gebäudeobjektplänen zur Unterstützung im Einsatz
5. Modul Stabsarbeit:
   - Unterstützung, Koordination und Dokumentation der Arbeit des Einsatzleiterstabes und der Stabsfunktionen im Einsatz
6. Modul Nachrichten (Messenger):
   - Erstellung und Darstellung der Funk- und Kommunikationsstruktur im Einsatz
7. Tableteinbindung:
   - Software in Webbrowser nutzbar machen Für Einsatztablets (ohne extra instalation):
8. Wettererfassung:
   - Erfassung, Dokumentation und Überwachung von Wetterdaten und Witterungsbedingungen im Einsatzbereich 



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
