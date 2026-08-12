# 📝 Memory Journal -- Changelog

Alle wichtigen Änderungen und Entwicklungsschritte von **Memory Journal**.

> Memory Journal wird iterativ zu einer persönlichen digitalen Erinnerungsbibliothek weiterentwickelt.
> Der Changelog dokumentiert Funktionen, Verbesserungen und Fehlerbehebungen, ohne interne Implementierungsdetails offenzulegen.

---

## v0.12.0

### 📚 Bücherregal

- Die Startseite wurde vollständig als persönliches Bücherregal neu gestaltet.
- Erinnerungsbücher erscheinen als unterschiedlich gestaltete Bücher auf mehreren Regalreihen.
- Neue Bücher können direkt aus dem Regal angelegt und beschriftet werden.
- Das Bücherregal bildet ab sofort den zentralen Ausgangspunkt von Memory Journal.

### 📖 Erinnerungsbücher

- Bücher öffnen sich jetzt als aufgeschlagene Doppelseite.
- Innerhalb eines Buches kann vorwärts und rückwärts durch die Seiten geblättert werden.
- Neue Seiten können direkt innerhalb des geöffneten Buches ergänzt werden.
- Der bestehende Seiteneditor wurde in die neue Buchstruktur integriert.

### 🔄 Produktrichtung

- Tagebuch, Fotoalbum und Scrapbook werden nicht mehr als voneinander getrennte Bereiche betrachtet.
- Das Erinnerungsbuch bildet künftig die gemeinsame Grundlage für Fotos, Texte und kreative Seiten.
- Kalender, Chronik und Tagesansichten bleiben als ergänzende Archivfunktionen erhalten.
- Die neue Struktur bereitet automatische Rückblicke, Zusammenfassungen und Statistiken vor.

### 🛡️ Datensicherheit

- Die bestehende lokale Archiv-, Backup- und Wiederherstellungsstruktur bleibt vollständig erhalten.
- Bücher und Seiten verwenden weiterhin die bereits archivierten Originalmedien.
- Fotos werden bei Verwendung in Büchern nicht dupliziert.

---

## v0.11.1

### 🖥️ Start

- Windows-Startdateien wurden direkt im Hauptordner ergänzt.
- `START_MEMORY_JOURNAL.cmd` ermöglicht den normalen Start der Anwendung.
- `INSTALLIEREN_UND_STARTEN.cmd` übernimmt die erstmalige Einrichtung und den ersten Start.
- Die lokale Projektstruktur muss zum Starten nicht mehr manuell durchsucht werden.

### 📖 Dokumentation

- Die README wurde auf den aktuellen Stand der Desktop-Anwendung gebracht.
- Start und lokale Nutzung werden verständlicher erklärt.

---

## v0.11.0

### 📖 Fotobuch-Editor

- Eigene Fotoalben besitzen jetzt dauerhaft gespeicherte Albumseiten.
- Bestehende Alben werden automatisch in die neue Seitenstruktur übernommen.
- Jede Albumseite kann individuell gestaltet werden.
- Neue Albumseiten können jederzeit ergänzt werden.

### 🖼️ Seitenlayouts

- Mehrere Layouts für Albumseiten ergänzt:
  - Klassisch
  - Hero-Foto
  - Collage
  - Polaroid-Seite
  - Frei
- Albumseiten können unterschiedliche Papierstile verwenden.
- Verfügbare Papierstile:
  - Creme
  - Leinen
  - Altrosa
  - Salbei
  - Mauve

### 📸 Inhalte

- Fotos eines Albums können gezielt einzelnen Albumseiten zugeordnet werden.
- Freie Textfelder können auf Albumseiten ergänzt werden.
- Bildunterschriften können direkt an Fotos hinterlegt werden.
- Elemente können im freien Layout individuell positioniert werden.

### 🛡️ Datensicherheit

- Albumseiten referenzieren ausschließlich bereits vorhandene Originalfotos.
- Die Gestaltung einer Albumseite erzeugt keine zusätzlichen Kopien der Bilder.
- Seiteninhalte werden automatisch in vollständigen Backups berücksichtigt.

---

## v0.10.0

### 📚 Fotoalben

- Eigene Fotoalben können unabhängig von der automatischen Chronik angelegt werden.
- Alben können Titel, Beschreibung und Zeitraum erhalten.
- Fotos aus unterschiedlichen Tagen können gemeinsam in einem Album gesammelt werden.
- Ein eigenes Foto kann als Albumcover festgelegt werden.

### 📖 Albumansicht

- Alben werden in einem eigenen Albumregal dargestellt.
- Fotos eines Albums erscheinen auf aufgeschlagenen Doppelseiten.
- Von einem Albumfoto kann direkt zum ursprünglichen Tagebucheintrag gesprungen werden.

### 🗓️ Chronik

- Die automatische chronologische Fotoansicht bleibt parallel zu eigenen Fotoalben erhalten.
- Chronik und selbst zusammengestellte Fotoalben erfüllen damit unterschiedliche Aufgaben.

### 🐛 Behoben

- Ein Fehler beim Speichern von Scrapbook-Blöcken wurde korrigiert.

---

## v0.9.0

### 🎨 Seitengestaltung

- Neuer Gestaltungsbereich für Scrapbook-Seiten.
- Unterschiedliche Papierhintergründe ergänzt:
  - Punktraster
  - Creme
  - Leinen
  - Altrosa
  - Salbei
  - Mauve
- Mehrere Schriftstimmungen für Scrapbook-Texte ergänzt.

### 📸 Fotos

- Zusätzliche Fotorahmen ergänzt.
- Fotos können mit unterschiedlichen Schatten dargestellt werden.
- Gestaltungseffekte verändern ausschließlich die Darstellung und nicht das Originalbild.

### 🎀 Dekoration

- Sticker-Auswahl erweitert.
- Sticker können in mehreren Farbstimmungen verwendet werden.
- Zusätzliche Washi-Farben und -Muster ergänzt.
- Neue Muster umfassen unter anderem Blümchen, Herzen und Karo.

---

## v0.8.0

### ✨ Freie Seite

- Neuer Modus für vollständig frei gestaltbare Scrapbook-Seiten.
- Elemente können frei auf der Seite verschoben werden.
- Blöcke können individuell vergrößert und verkleinert werden.
- Die Ebene einzelner Elemente kann verändert werden.
- Fotos, Sticker, Washi und Notizzettel können sich überlagern.

### 🔄 Layoutwechsel

- Freie Positionen bleiben erhalten, wenn zwischen freier Seite und automatischen Layouts gewechselt wird.
- Bereits vorhandene Blöcke erhalten beim ersten Wechsel automatisch eine sinnvolle Ausgangsposition.

### 🛡️ Daten

- Freie Positionen und Größen werden als Layoutinformationen gespeichert.
- Originalfotos bleiben von sämtlichen Gestaltungsänderungen unberührt.

---

## v0.7.0

### 📖 Seitenlayouts

- Mehrere vorbereitete Layouts für Scrapbook-Seiten ergänzt:
  - Albumseite
  - Doppelseite
  - Hero-Foto
  - 3 Fotos + Notiz
  - Polaroid-Wand
  - Minimal Journal
- Das gewünschte Layout kann direkt auf der Journal-Seite ausgewählt werden.
- Das gewählte Layout wird individuell pro Tag gespeichert.

### 🔄 Flexibilität

- Layoutwechsel verändern ausschließlich die Darstellung.
- Vorhandene Fotos, Texte und Scrapbook-Blöcke bleiben unverändert.
- Bestehende Inhalte können jederzeit in einem anderen Layout dargestellt werden.

---

## v0.6.0

### 📸 Scrapbook-Fotos

- Fotos können direkt als eigene Elemente auf Journal-Seiten verwendet werden.
- Mehrere Foto-Darstellungen ergänzt:
  - Polaroid
  - Clean
  - abgerundeter Fotoabzug
  - Filmrahmen
- Bildunterschriften können ergänzt werden.
- Fotoabzüge können leicht gedreht dargestellt werden.
- Washi Tape kann direkt an Fotos verwendet werden.

### 🖼️ Collagen

- Mehrere Fotos können gemeinsam als Collage verwendet werden.
- Verfügbare Collage-Layouts:
  - Raster
  - Mosaik
  - Filmstreifen
- Collagen können eigene Bildunterschriften erhalten.

### 🎀 Dekoration

- Sticker-Blöcke ergänzt.
- Verschiedene Sticker-Motive und Größen verfügbar.
- Eigenständige Washi-Tape-Blöcke ergänzt.
- Washi kann unterschiedliche Farben und Muster besitzen.

### 🛡️ Medien

- Scrapbook-Seiten speichern ausschließlich Verknüpfungen auf vorhandene Fotos.
- Originalbilder werden durch die Gestaltung weder kopiert noch verändert.

---

## v0.5.0

### 🌷 Bullet Journal

- Erstes flexibles Bullet-Journal-/Scrapbook-System ergänzt.
- Journal-Seiten können aus unterschiedlichen Blöcken aufgebaut werden.

### ✍️ Blöcke

- Verfügbare Elemente:
  - Überschrift
  - freier Text
  - Highlight des Tages
  - Notiz
  - Zitat
  - Checkliste
- Blöcke können neu angeordnet oder entfernt werden.
- Checklisten unterstützen mehrere einzeln abhakbare Punkte.

### 🎨 Design

- Gepunktete Papierfläche im Stil eines Bullet Journals ergänzt.
- Highlights, Notizzettel und Zitate besitzen unterschiedliche Papierstile.
- Der klassische lange Tagebuchtext bleibt parallel zum kreativen Editor erhalten.

---

## v0.4.0

### 🗓️ Kalender

- Navigation zwischen einzelnen Journal-Tagen ergänzt.
- Direkter Sprung zum heutigen Tag.
- Neue Monatsansicht als visueller Erinnerungskalender.
- Tage mit Erinnerungen können Foto, Titel, Stimmung, Wortzahl und Fotoanzahl anzeigen.
- Kalendertage führen direkt zum jeweiligen Eintrag.

### 📸 Fotochronik

- Erste visuelle Fotoalbum-Ansicht ergänzt.
- Erinnerungen werden automatisch nach Monaten gruppiert.
- Fotos erscheinen als albumartige Karten statt als klassische Dateiliste.
- Direkter Sprung vom Foto zurück zum zugehörigen Tagebucheintrag.

### 🎨 Design

- Tagesgalerien stärker an eingeklebte Fotoabzüge angelehnt.
- Polaroid-Stil und dezentes Washi Tape ergänzt.
- Monatsansichten verwenden warme Papierflächen und albumartige Gestaltung.

### 💾 Speichern

- Beim Wechsel zwischen Tagen und Ansichten werden noch ausstehende Änderungen zuerst gespeichert.

---

## v0.3.0

### ↶ Versionshistorie

- Automatische Text-Versionshistorie für Tagebucheinträge ergänzt.
- Frühere Versionen speichern Titel, Text und Stimmung.
- Wiederherstellungspunkte werden automatisch in sinnvollen Abständen erzeugt.
- Frühere Versionen können mit Datum, Wortzahl und Vorschau angesehen werden.

### 🛡️ Recovery

- Frühere Textstände können gezielt wiederhergestellt werden.
- Vor einer Wiederherstellung wird der aktuelle Stand zusätzlich als eigener Recovery-Punkt gespeichert.
- Dadurch kann auch eine versehentliche Wiederherstellung wieder rückgängig gemacht werden.
- Textversionen werden automatisch in vollständige Backups aufgenommen.

---

## v0.2.0

### 💾 Backup

- Vollständige manuelle Backups des persönlichen Archivs ergänzt.
- Backups enthalten Datenbank und alle registrierten Originalbilder.
- Für jedes Backup wird ein Manifest erstellt.
- Dateigrößen und SHA-256-Prüfsummen werden zur Validierung verwendet.

### 🔍 Backup-Prüfung

- Backups werden nach ihrer Erstellung automatisch geprüft.
- Bereits vorhandene Backups können erneut validiert werden.
- Beschädigte oder veränderte Dateien werden erkannt.

### ♻️ Wiederherstellung

- Vollständige Archive können aus einem geprüften Backup wiederhergestellt werden.
- Vor jeder Wiederherstellung wird automatisch eine zusätzliche Sicherheitskopie des aktuellen Zustands erstellt.
- Die Wiederherstellung wird vor dem Austausch des aktiven Archivs geprüft.

### 📊 Status

- Letztes erfolgreiches Backup wird in der Anwendung angezeigt.
- Backup-Historie ergänzt.

---

## v0.1.0

### ✨ Erste Version

- Grundgerüst als lokale Desktop-Anwendung erstellt.
- Erste Tagesansicht im warmen, pastelligen Memory-Journal-Design.
- Tagebucheinträge mit Titel, Text und Stimmung.
- Automatisches Speichern während des Schreibens.
- Fotoimport und erste Galerie ergänzt.

### 📸 Medienarchiv

- Originalbilder werden als eigenständige Dateien im lokalen Archiv gespeichert.
- Fotos werden nicht als große eingebettete Bilddaten innerhalb der Tagebucheinträge gespeichert.
- SHA-256-Prüfsummen werden beim Bildimport erzeugt und geprüft.

### 🛡️ Archiv

- Lokale Datenbank für Tagebuch- und Medieninformationen.
- Integritätsprüfung für das persönliche Archiv.
- Fehlende oder veränderte Mediendateien können erkannt werden.
- Erste Archivstatistik für Einträge, Fotos und Wörter ergänzt.

### 🎨 Design

- Grundlegende Farbwelt mit Creme, Altrosa, Salbei, Mauve und warmen Brauntönen.
- Ruhige, papierartige Oberfläche als Ausgangspunkt für das spätere Erinnerungsbuch.
