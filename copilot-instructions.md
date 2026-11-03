# Projekt: Portfolio-Website der Künstlerin Rahel Kistler (leharts.ch)

## Ziel

Ich will mit diesem Projekt Frontend-Entwicklung lernen, schreibe aber selbst keinen Code.
Du schreibst den gesamten Code. Erkläre nach jeder grösseren Änderung kurz:

- was du gebaut hast und warum so
- welche neuen Konzepte (HTML, CSS, JS) dabei vorkommen
  Schreibe lesbaren, gut kommentierten Code statt cleverer Abkürzungen.

## Technik

- Nur HTML5, CSS3 und Vanilla JavaScript (ES-Module). KEINE Frameworks, KEINE Libraries, KEIN Build-Schritt,
  kein npm nötig, um die Seite anzusehen.
- Läuft direkt auf GitHub Pages und später auf jedem Webserver: nur relative Pfade verwenden.
- CSS: Custom Properties für Farben/Abstände/Schriften, Flexbox und Grid, mobile-first mit min-width Media Queries.
  Klassen nach einer einheitlichen Konvention benennen (z. B. BEM).
- JS: ein Modul pro Funktion, mit `defer` oder `type="module"` laden. Die Seite muss auch ohne JS lesbar sein
  (Progressive Enhancement).
- Schriften lokal in /fonts hosten (woff2), nicht von Google Fonts laden. Keine Tracker, keine Cookies,
  keine eingebetteten Drittanbieter-Inhalte.

## Inhalte, oberste Regel

- Alle Texte WORTGETREU von der alten Website übernehmen: Schreibweise, Gross-/Kleinschreibung, Satzzeichen,
  Emojis, auch offensichtliche Fehler. NICHTS umformulieren, kürzen, übersetzen oder ergänzen.
- Nichts erfinden. Fehlt eine Angabe, bleibt sie leer.
- Unstimmigkeiten nicht korrigieren, sondern in INHALT-PRUEFEN.md auflisten.

## Bilder

- Liegen in /images mit den Original-Dateinamen der alten Website.
- Immer mit width/height (gegen Layout-Sprünge), loading="lazy" (ausser beim ersten Bild) und sinnvollem alt-Text.
- Fehlt eine Datei, ersetzt js/placeholder.js das Bild durch einen eleganten Platzhalter mit dem Dateinamen.

## Design

- Modern, aber klassisch: wie eine hochwertige Galerie, viel Weissraum, die Kunst steht im Zentrum.
- Spürbar kreativ und lebendig (Motto: "Farbige Lebendigkeit"): z. B. Pinselstrich-Akzente als SVG,
  Akzentfarben aus den Werken, subtile organische Formen.
- Ausdrucksstarke Serifenschrift für Titel, ruhige Sans-Serif für Text.
- Dezente Animationen (Einblenden, Hover), prefers-reduced-motion respektieren.

## Qualität

- Funktioniert von 320px bis Grossbildschirm, Touch-Bedienung (Wischen in Lightbox/Slider).
- Barrierefrei: semantisches HTML, Tastaturbedienung, sichtbarer Fokus, genügend Kontrast, ARIA nur wo nötig.
- Valides HTML, lang="de", Meta-Description und Open-Graph-Tags pro Seite.
