# Vokabeln-App

Karteikarten-App zum Vokabellernen. Eine einzige Datei (`index.html`), keine Installation nötig.

## Funktionen
- Sprache wählen (Englisch, Spanisch, Französisch, Italienisch, Latein, andere); jede Sprache hat eigene Karten
- Vokabeln einfügen: Text kopieren und einfügen, die App sucht Vokabeln heraus (ohne Nummern, Aussprache, Klammern, Beispielsätze, Uhrzeit)
- Bild hinzufügen: Texterkennung im Browser (Tesseract.js), braucht Internet
- Erkennungsmodi: automatisch, Wort und Übersetzung in einer Zeile, zwei Blöcke, abwechselnde Zeilen; Seiten tauschen
- Karteikarten zum Umdrehen; nach rechts wischen = richtig, nach links = falsch
- Einzelne Karten mit Bild, ändern und löschen
- Daten bleiben lokal im Browser (IndexedDB)

## Auf den Home-Bildschirm
1. `index.html` bei Netlify Drop (app.netlify.com/drop) hochladen oder per GitHub Pages veröffentlichen
2. Link in Safari öffnen, Teilen, „Zum Home-Bildschirm“
