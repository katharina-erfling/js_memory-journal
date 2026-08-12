# 📚 Memory Journal

**Memory Journal** ist eine lokale Desktop-Anwendung für persönliche Erinnerungen, Fotos und kreative Journals.

Die Anwendung verbindet digitales **Fotoalbum, Scrapbook, Tagebuch und Bullet Journal** in einer gemeinsamen Umgebung. Im Mittelpunkt steht ein persönliches Bücherregal: Dort können eigene Erinnerungsbücher angelegt, gestaltet und anschließend Seite für Seite mit Fotos, Texten und dekorativen Elementen gefüllt werden.

Memory Journal ist für langfristige persönliche Archive gedacht. Deshalb gehören lokale Speicherung, Originaldateien, Integritätsprüfungen, Backups und Wiederherstellung von Anfang an zum technischen Fundament.

---

## ✨ Funktionen

### 📚 Persönliches Bücherregal

- Eigene Erinnerungsbücher anlegen und beschriften
- Visuelles Bücherregal als zentrale Startseite
- Unterschiedlich gestaltete Buchrücken
- Bücher direkt aus dem Regal öffnen
- Beliebig viele Bücher für Jahre, Reisen, Personen, Tiere, Ereignisse oder andere Themen
- Bücher als gemeinsame Grundlage für Tagebuch, Fotoalbum und Scrapbook

### 📖 Blätterbare Erinnerungsbücher

- Bücher öffnen sich als Doppelseiten
- Vorwärts und rückwärts durch die Seiten blättern
- Neue Seiten jederzeit ergänzen
- Unterschiedliche Seitenlayouts
- Individuelle Papierstile
- Freie Gestaltung einzelner Seiten
- Fotos und Texte innerhalb eines Buches miteinander kombinieren

### 📸 Fotos & Erinnerungen

- Originalfotos lokal archivieren
- Mehrere Fotos pro Tag und Seite
- Fotos in verschiedenen Büchern verwenden, ohne Originaldateien zu duplizieren
- Polaroid-, Clean-, Film- und weitere Foto-Darstellungen
- Bildunterschriften
- Fotocollagen
- Mosaik-, Raster- und Filmstreifen-Layouts
- Albumcover aus eigenen Fotos
- Chronologische Fotoübersicht
- Verknüpfung zwischen Fotos und den zugehörigen Erinnerungen

### ✍️ Tagebuch

- Freier Tagebuchtext
- Automatisches Speichern während des Schreibens
- Titel und Stimmung pro Eintrag
- Navigation zwischen einzelnen Tagen
- Frühere Textstände automatisch sichern
- Alte Versionen ansehen und wiederherstellen
- Aktuellen Stand vor einer Wiederherstellung zusätzlich sichern

### 🌷 Bullet Journal & Scrapbook

Journal-Seiten können aus unterschiedlichen Elementen aufgebaut werden:

- Überschriften
- freie Textblöcke
- Highlights des Tages
- Notizzettel
- Zitate und Gedanken
- Checklisten
- einzelne Fotos
- Fotocollagen
- Sticker
- Washi Tape

Die Elemente können miteinander kombiniert und individuell angeordnet werden.

### 🎨 Freie Seitengestaltung

- Elemente frei auf einer Journal-Seite positionieren
- Elemente vergrößern und verkleinern
- Ebenen verändern
- Fotos überlappen lassen
- Sticker und Washi frei platzieren
- Freie Gestaltung zusätzlich zu automatischen Seitenlayouts
- Individuelle Positionen bleiben beim Wechsel zwischen Layouts erhalten

### 🖼️ Seitenlayouts

Verschiedene vorbereitete Layouts unterstützen sowohl schnelles Journaling als auch aufwendigere Scrapbook-Seiten:

- Albumseite
- Doppelseite
- Hero-Foto
- 3 Fotos + Notiz
- Polaroid-Wand
- Minimal Journal
- freie Seite

### 🎀 Gestaltung

- warme, ruhige Pastellfarbwelt
- Creme
- Altrosa
- Salbei
- Mauve
- warme Brauntöne
- unterschiedliche Papierhintergründe
- Punktraster
- Leinenoptik
- verschiedene Schriftstimmungen
- unterschiedliche Fotorahmen
- Foto-Schatten
- verschiedene Washi-Farben und -Muster
- dekorative Sticker

### 🗓️ Kalender & Chronik

- Monatsübersicht der vorhandenen Erinnerungen
- Tage mit Fotos direkt visuell erkennen
- Anzeige von Stimmung, Titel, Wortzahl und Fotoanzahl
- Direkter Sprung vom Kalender zum jeweiligen Eintrag
- Automatische chronologische Fotoübersicht
- Erinnerungen nach Monaten gruppiert

### 📚 Eigene Fotoalben

- Eigene Alben unabhängig von der automatischen Chronik anlegen
- Titel und Beschreibung vergeben
- Zeitraum festlegen
- Fotos aus unterschiedlichen Tagen gemeinsam sammeln
- eigenes Albumcover wählen
- Albumseiten individuell gestalten
- Fotos und Texte auf Albumseiten kombinieren
- verschiedene Papier- und Seitenlayouts verwenden

### 🛡️ Datensicherheit

Memory Journal wurde von Anfang an für ein langfristiges persönliches Archiv konzipiert.

- lokale Speicherung
- SQLite-Datenbank für strukturierte Daten
- Originalbilder als eigenständige Dateien
- keine Speicherung großer Bilder als Base64 innerhalb von Tagebucheinträgen
- SHA-256-Prüfsummen für Mediendateien
- Integritätsprüfung des Archivs
- Erkennung fehlender oder veränderter Mediendateien
- automatische Text-Versionierung
- vollständige Backups
- Backup-Validierung
- Wiederherstellung vollständiger Archive
- zusätzliche Sicherheitskopie vor einer Wiederherstellung

---

## 💾 Datenhaltung

Die persönlichen Daten werden lokal gespeichert.

Das Archiv enthält unter anderem:

- SQLite-Datenbank
- Originalfotos
- Journal-Einträge
- Bücher
- Albumseiten
- Scrapbook-Elemente
- Layoutinformationen
- Textversionen
- Metadaten

Fotos werden nicht für jede Verwendung erneut gespeichert. Eine Seite oder ein Album referenziert das bereits vorhandene Original.

Dadurch kann dasselbe Foto beispielsweise gleichzeitig in einem Jahresjournal und einem thematischen Erinnerungsbuch verwendet werden, ohne mehrfach im Archiv zu liegen.

---

## 🔐 Backup & Wiederherstellung

Memory Journal verfügt über ein eigenes Backup-System.

Ein vollständiges Backup umfasst:

- Datenbank
- Originalmedien
- Bücher und Seiten
- Journal-Inhalte
- Layouts
- Scrapbook-Elemente
- Textversionen
- Metadaten

Backups besitzen ein Manifest mit Dateigrößen und SHA-256-Prüfsummen.

Vor einer Wiederherstellung wird das ausgewählte Backup geprüft. Zusätzlich wird der aktuelle Stand automatisch gesichert, bevor das bestehende Archiv ersetzt wird.

---

## 🧠 Geplante Entwicklung

Memory Journal wird schrittweise zu einer persönlichen Erinnerungsbibliothek ausgebaut.

Geplant sind unter anderem:

- weiterentwickelter Bücherregal-Editor
- individuell gestaltbare Einbände und Buchrücken
- Covergestaltung
- umfangreicherer Seiteneditor
- zusätzliche Bullet-Journal-Elemente
- weitere Sticker- und Washi-Sets
- Tracker
- Mood Tracker
- Collections
- Monats- und Jahresrückblicke
- automatische Fotocollagen
- visuelle Statistiken
- Erinnerungen wie „Heute vor einem Jahr“
- Favoriten
- Tags und Kategorien
- Personen- und Tierzuordnungen
- umfangreiche Archivsuche
- automatische Zusammenfassungen
- statistische Auswertungen über Bücher und Erinnerungen

Langfristig soll Memory Journal nicht nur Erinnerungen speichern, sondern vorhandene Inhalte auch neu aufbereiten können – beispielsweise als Monatsrückblick, Jahreszusammenfassung oder visuelle Fotoübersicht.

---

## 🧰 Technologie

- JavaScript
- HTML
- CSS
- Electron
- Node.js
- SQLite
- lokale Dateispeicherung
- SHA-256-Prüfsummen

---

## 🖥️ Lokale Nutzung

Memory Journal ist als lokale Desktop-Anwendung konzipiert.

Nach dem Entpacken stehen im Hauptordner Startdateien für Windows zur Verfügung.

Beim ersten Start:

```text
INSTALLIEREN_UND_STARTEN.cmd
```

Für spätere Starts:

```text
START_MEMORY_JOURNAL.cmd
```

Die persönlichen Archivdaten werden getrennt vom eigentlichen Programm gespeichert.

---

## 🚧 Entwicklungsstatus

Memory Journal befindet sich in aktiver Entwicklung.

Die grundlegende Architektur für lokale Datenhaltung, Medienarchiv, Backups, Wiederherstellung und frei gestaltbare Erinnerungsseiten ist bereits vorhanden.

Aktuell wird die Oberfläche grundlegend auf das zentrale Konzept einer persönlichen Bibliothek aus frei gestaltbaren Erinnerungsbüchern ausgerichtet.

---

## 📜 Lizenz

Dieses Projekt ist für die persönliche Nutzung entwickelt.

Eine weitergehende Lizenzierung oder Veröffentlichung kann zu einem späteren Zeitpunkt festgelegt werden.

---

## 💗 Hintergrund

Memory Journal entstand aus dem Wunsch nach einem digitalen Erinnerungsort, der sich nicht wie eine Datenbank oder klassische Tagebuch-App anfühlt.

Statt Erinnerungen lediglich chronologisch abzulegen, sollen sie wie in einem echten Fotoalbum, Scrapbook oder Bullet Journal gesammelt und gestaltet werden können – in persönlichen Büchern, die langfristig im eigenen digitalen Bücherregal wachsen.
