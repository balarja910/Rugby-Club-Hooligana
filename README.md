# 🏉 Rugby-Club Hooligana – Webseite

Eine responsive Webseite für den Rugby-Club **Hooligana** aus Tiflis (Georgien). Das Projekt habe ich mit reinem HTML, CSS und JavaScript umgesetzt – ganz ohne Frameworks – um die Grundlagen der Webentwicklung zu festigen.

🔗 **Live-Demo:** (https://balarja910.github.io/Rugby-Club-Hooligana/)

## Über das Projekt

Der Club wurde 1996 gegründet und hat heute rund 150 Spieler in sechs Altersgruppen. Die Seite stellt den Verein vor und enthält Informationen zu Geschichte, Trainer, kommenden Spielen und Kontakt. Die Inhalte sind auf Georgisch (`lang="ka"`).

## Funktionen

- **Responsives Design** – angepasst für Desktop, Tablet und Smartphone (Media Queries für 768 px, 480 px und 320 px)
- **Sticky-Navigation** mit **Burger-Menü** für mobile Geräte
- **Bildergalerie als Slider** mit Vor-/Zurück-Pfeilen und Endlosschleife
- **Spielplan** als Karten mit Hover-Effekt
- **Kontaktformular** mit Validierung (Pflichtfelder, E-Mail-Prüfung per regulärem Ausdruck)
- **Cookie-Hinweis** mit Bestätigungsbutton
- **Footer** mit Social-Media-Links (Facebook, Instagram) und Kontaktdaten

## Verwendete Technologien

| Bereich | Technologie |
|---|---|
| Struktur | HTML5 (semantische Elemente) |
| Gestaltung | CSS3 (Flexbox, Transitions, Media Queries) |
| Logik | JavaScript (Vanilla, DOM-Manipulation, Event Listener) |
| Schrift & Icons | Google Fonts (Roboto), Font Awesome |
| Hosting | GitHub Pages |

## Projektstruktur

```
Rugby-Club-Hooligana/
├── index.html      # Struktur und Inhalte
├── styles.css      # Layout und Responsive Design
├── script.js       # Slider, Menü, Formular, Cookie-Hinweis
└── Photos/         # Bilder und Logo
```

## Lokal starten

```bash
git clone https://github.com/balarja910/Rugby-Club-Hooligana.git
cd Rugby-Club-Hooligana
```

Anschließend `index.html` im Browser öffnen – eine Installation ist nicht nötig.

## Was ich dabei gelernt habe

- Aufbau einer mehrteiligen Seite mit Anker-Navigation
- Responsive Layouts mit Flexbox und Media Queries
- Arbeiten mit dem DOM: Slider, Menü und Formularvalidierung in JavaScript
- Veröffentlichung einer Webseite über GitHub Pages
- Versionsverwaltung mit Git und GitHub

## Bekannte Einschränkungen und geplante Verbesserungen

- [ ] Das Kontaktformular prüft die Eingaben nur im Browser und versendet noch keine Nachrichten (Anbindung z. B. an Formspree oder EmailJS geplant)
- [ ] Cookie-Auswahl dauerhaft speichern (`localStorage`), damit der Hinweis nicht bei jedem Besuch erscheint
- [ ] Bilder in WebP umwandeln, um die Ladezeit zu verbessern
- [ ] Spielplan aus einer JSON-Datei laden, damit er leichter zu aktualisieren ist
- [ ] Barrierefreiheit verbessern (Alt-Texte auf Georgisch, Tastaturbedienung des Sliders)

## Autor

**balarja910** – [GitHub-Profil](https://github.com/balarja910)

---

*Hinweis: Dies ist ein Lernprojekt. Logo, Fotos und Vereinsinformationen gehören dem Rugby-Club Hooligana.*
