# INHALT – alte Website leharts.ch

Gelesen am 03.11.2026 mit #fetch (HTML-Quelltext). Laut `sitemap.xml` besteht die Website aus genau diesen 6 Seiten (letzte Änderung jeweils 2026-09-30).
Offene Punkte, Unstimmigkeiten und der Bildabgleich stehen in [INHALT-PRUEFEN.md](INHALT-PRUEFEN.md).

## Lesehilfe

- Alles **ausserhalb** von eckigen Klammern ist Text der alten Website, zeichengenau übernommen (Schreibweise, Gross-/Kleinschreibung, Satzzeichen, Tippfehler). Die Originaltexte selbst enthalten keine eckigen Klammern.
- **[In eckigen Klammern]** stehen meine Beschreibungen: Elementtyp, Formatierung, Link-Ziel, Hinweise.
- **[Abstand]** = Leerraum, den die alte Seite mit vielen (geschützten) Leerzeichen erzeugt (meist vor „sold out“). Einzelne Leerzeichen am Anfang/Ende eines Textes sowie leere Absätze und Zeilenumbrüche, die nur Abstand erzeugen, sind weggelassen.
- Ein `*` aus dem Original steht im Markdown-Quelltext als `\*`, damit es nicht als Formatierung gelesen wird.
- Bilder: `Dateiname` aus der Bild-URL (URL-Kodierung aufgelöst, z. B. `%20` → Leerzeichen, `%2C` → Komma), dazu die Pixelmasse laut alter Website (Breite × Höhe). `aktuelle/` ist ein Unterordner auf dem alten Server; der Dateiname ist der Teil danach.
- Steht bei einem Bild nichts zum alt-Text, ist er auf der alten Website leer.

---

## Auf allen Seiten gleich

### Aufbau (Reihenfolge im HTML)

Menü → Kopfbereich (Website-Titel, Logo) → Kopfbild (je Seite verschieden, auf News keins) → Inhalt → Seitenleiste (Kontaktblock, darunter ein seitenspezifischer Bereich, der nur auf About Inhalt hat) → Fusszeile

### Meta-Angaben

- [Meta-Description, auf allen Seiten gleich] Bilder sagen mehr als tausend Worte
- [Meta-Keywords, auf allen Seiten gleich] Kultur, Kunst
- [Open Graph: nur og:title (= Seitentitel), og:type und og:url; kein og:image, keine og:description]
- [Favicon: keins (leeres Platzhalter-Icon)]
- [Seitentitel (Browser-Tab): siehe jeweilige Seite]

### Menü

1. About [→ /About/]
2. News [→ /News/]
3. PAST EXHIBITIONS [→ /PAST-EXHIBITIONS/]
4. paintings [→ /paintings/]
5. Photography [→ /Photography/]
6. More Projects [→ /More-Projects/]

[Das Menü steht zweimal im HTML (mobil und Desktop), beide identisch. Der Linktitel (title-Attribut) entspricht jeweils dem Menütext. Dazu ein Menü-Schalter, nur Symbol, kein Text.]

### Kopfbereich

- [Website-Titel] lehARTs
- [Untertitel: leer]
- [Logo, ohne Text, als CSS-Hintergrundbild] `1 power, mixed media, 80x100cm.JPG` [2744 × 3564 px; dasselbe Bild steht auf „paintings“ als Werk „Power“]

### Kontaktblock [Seitenleiste, auf allen Seiten]

- Rahel Kistler [fett]
- Zopfstrasse 10
- 8855 Wangen SZ
- Tel: 079 756 72 57 [reiner Text, kein Link]
- info@leharts.ch [reiner Text, kein Link]
- www.lehARTs.ch [reiner Text, kein Link]
- [Instagram-Symbol ohne sichtbaren Text → https://www.instagram.com/leharts.ch/, Linktitel „Instagram“, öffnet in neuem Fenster]

### Fusszeile

- Startseite [Link → /About/]

### Weitere Bedienelemente

- [„Nach oben“-Pfeil, nur Symbol, kein Text]

---

## Seite 1: About (Startseite)

- [URL] https://leharts.ch/ [zeigt dieselbe Seite wie https://leharts.ch/About/, die als Hauptadresse (canonical) angegeben ist]
- [Seitentitel] lehARTs - About
- [Aktiver Menüpunkt: About; Menü, Kopfbereich, Kontaktblock, Fusszeile wie oben]
- [Kopfbild, CSS-Hintergrund] `IMG_3849.jpg` [Pixelmasse auf der alten Site nicht angegeben]

### Inhalt

1. [Absatz, fett] Farbige Lebendigkeit
2. [Absatz]
   > Die Ideen für Kistlers kreatives Tun entstehen beim bewussten Beobachten der Umgebung. „In der Natur finde ich die schönsten Kunstwerke“, sagt sie. Durch diese wird sie beflügelt, ihre Ideen in Farbe zu tauchen. Kistler malt, fotografiert und gestaltet Skulpturen. Sie lässt sich thematisch und technisch nicht einschränken. Im Vordergrund sind meist Tier und Mensch, denen sie mit Farbe und Strich Lebendigkeit verleiht. „Offen, spontan, experimentierfreudig“ sind die Attribute, welche das Wesen und das Schaffen von Kistler am besten beschreiben. Ihre Kreativität scheint grenzenlos. Als Sekundarlehrerin in Buttikon unterrichtet sie das Fach „Bildnerisches Gestalten“ und setzt so ihr grosses Talent auch beruflich ein.
3. [Bild] `schlusswort.jpg` [750 × 932 px, kein Bildtext]

### Seitenleiste [nur auf dieser Seite, unter dem Kontaktblock]

1. [gross (28 px), fett, blau #0029ff] Zukünftige Ausstellungen [Abstand] !!!
2. [klein (14 px), fett, kursiv, blau #0029ff] (für mehr Infos, auf News klicken)
3. [Button] Hier geht's zur Kunstschwyz Seite [→ http://kunstschwyz.ch, öffnet in neuem Fenster]

---

## Seite 2: News

- [URL] https://leharts.ch/News/
- [Seitentitel] lehARTs - News
- [Aktiver Menüpunkt: News; Menü, Kopfbereich, Kontaktblock, Fusszeile wie oben]
- [Kopfbild: keins]

### Inhalt

1. [Absatz, fett] Es gibt bald Neuigkeiten. Seid gespannt! :)

[Keine Bilder, keine Links im Inhalt.]

---

## Seite 3: PAST EXHIBITIONS

- [URL] https://leharts.ch/PAST-EXHIBITIONS/
- [Seitentitel] lehARTs - PAST EXHIBITIONS
- [Aktiver Menüpunkt: PAST EXHIBITIONS; Menü, Kopfbereich, Kontaktblock, Fusszeile wie oben]
- [Kopfbild, CSS-Hintergrund] `IMG_3849.jpg` [wie auf About]

### Inhalt

1. [Überschrift H1] \*Kuratierte Ausstellungen
2. [Überschrift H2, kursiv] März 2026 - Mai 2026:
3. [Überschrift H2, kursiv] Jahresausstellung Verein Kunst Schwyz Morschach\*
4. [Trennlinie]
5. [Überschrift H2, kursiv] April 2025 - März 2026:
6. [Überschrift H2, kursiv] Jahresausstellung Einsiedeln
7. [Bild] `JahresaustellungEinsiedelnLeharts.png` [887 × 888 px, kein Bildtext]
8. [Trennlinie]
9. [Überschrift H2, kursiv] März 2024 - März 2025:
10. [Absatz, fett, kursiv] Jahresausstellung MedicoPlus art, Einsiedeln
11. [Trennlinie]
12. [Absatz, fett, kursiv] 11. Mai 2024 - 26 . Mai 2024
13. [Absatz, fett, kursiv] Ausstellung Verein Kunst Schwyz/Pfäffikon
14. [Trennlinie]
15. [Absatz, fett, kursiv] Oktober 2024 - Ende Jahr 2024:
16. [Absatz, fett, kursiv] Kunstausstellung GartenBISTRO Näfels
17. [Trennlinie]
18. [Absatz, fett, kursiv] November 2022:
19. [Überschrift H2] „Natürlich Kunst“ im Bahnhof Bäch vom
20. [Absatz, fett]
    > Die Kulturkommission Freienbach lädt zu einem surrealen Spaziergang durch die Natur ein. Die beiden Ausserschwyzer Künstler Rahel Kistler und Richard Cantieni präsentieren ihre Werke ab Freitag im Kulturhaus in Bäch.
21. [Absatz]
    > „Natürlich Kunst“: So schnörkellos wie der Titel der Kunstausstellung sind auch die Skulpturen und Bilder der Wangner Künstlerin Rahel Kistler und des Wiler Künstlers Richard Cantieni. Unter dem Patronat der Kulturkommission der Gemeinde Freienbach stellen die beiden eine Auswahl ihrer Werke vom 25. November bis 10. Dezember im Kulturhaus (Bahnhof) Bäch aus. Die Vernissage mit musikalischer Begleitung ist am Freitagabend von 18 bis 21 Uhr. Die Besucher der Ausstellung erwartet ein surrealer Sparziergang durch die Natur. Der Höfner Cantieni und die Märchlerin Kistler finden ihre Inspiration und die Materialien für ihre Kunst in der freien Natur – zumindest teilweise.
22. [Bild] `Screenshot 2024-03-26 200940.png` [348 × 481 px, kein Bildtext]
23. [Trennlinie]
24. [Absatz, fett, kursiv] Juni 2022:
25. [Absatz, fett] 3D Street Art in Zusammenarbeit mit Eduardo Relero in Lachen
26. [Trennlinie]
27. [Absatz, fett, kursiv] April 2022:
28. [Absatz, fett] Jahresausstellung Verein Kunst Schwyz, Pfäffikon\*
29. [Trennlinie]
30. [Absatz, fett, kursiv] Juni 2021:
31. [Absatz, fett] Jahresausstellung Verein Kunst Schwyz, Siebnen
32. [Trennlinie]
33. [Absatz, fett, kursiv] März 2021:
34. [Absatz, fett] Swissphotoclub, Zürich\*
35. [Trennlinie]
36. [Absatz, fett, kursiv] Oktober 2020:
37. [Absatz, fett] Arttalents Zürich
38. [Trennlinie]
39. [Absatz, fett, kursiv] August 2020:
40. [Absatz, fett] Artbox/Project Zürich 2.0\*

---

## Seite 4: paintings

- [URL] https://leharts.ch/paintings/
- [Seitentitel] lehARTs - paintings
- [Aktiver Menüpunkt: paintings; Menü, Kopfbereich, Kontaktblock, Fusszeile wie oben]
- [Kopfbild, CSS-Hintergrund] `14 sorpresa, mixed media, 100x100cm_1.jpg` [dasselbe Bild steht unten als Werk „Sorpresa“]
- [Kein Einleitungstext, keine Überschrift. Alle Bildtexte stehen zentriert unter dem Bild. alt-Texte der Einzelbilder sind leer.]

### Inhalt – Teil 1: Einzelbilder

1. [Bild] `IMG_0545.jpg` [626 × 640 px]
   - [Bildtext] Furry news, Acryl auf Mixed Media auf Leinwand, 2024, 80x80cm [Abstand] sold out [„sold out“ fett, kursiv]
2. [Bild] `IMG_4092.jpg` [640 × 640 px]
   - [Bildtext] Love, Mixed Media auf Leinwand, 2023 [Abstand] sold out [„sold out“ fett, kursiv]
3. [Bild] `IMG_0964.jpg` [640 × 640 px]
   - [Bildtext] Funky cow, Acryl auf Leinwand, 2022, 80x80cm [Abstand] sold out [„sold out“ fett, kursiv]
4. [Bild] `DD5995C3-086F-4C83-B417-40284BF2FF25.JPG` [640 × 640 px]
   - [kein Bildtext direkt darunter]
5. [Bild] `C428B35D-4A85-47E1-B2DB-97A8C013179D.JPG` [640 × 640 px]
   - [leerer Link: kein Text, kein Ziel, öffnet neues Fenster]
   - [Bildtext] Vibes, Öl und Acryl auf Leinwand, 2024, 30x30cm
6. [Bild] `aktuelle/bild11.jpg` [640 × 640 px]
   - [Bildtext] Freedom in Connection, Öl auf Acryl, 2024, 80x80cm
7. [Bild] `aktuelle/bild10.jpg` [640 × 640 px]
   - [Bildtext] Nebula, Öl auf Acryl, 2024, 80x80cm [Abstand] sold out [„sold out“ fett, kursiv]
8. [Bild] `aktuelle/bild6.jpg` [510 × 640 px]
   - [Bildtext] High on Speed, mixed media in Acryl, 2023, 60x80cm
9. [Bild] `aktuelle/bild3.jpg` [636 × 640 px]
   - [Bildtext] Funky Muh 2, mixed media in Acryl, 2023, 80x80cm
10. [Bild] `aktuelle/bild4.jpg` [634 × 640 px]
    - [Bildtext] Aries, mixed media in Acryl auf Holz, 2024, 40x40cm [Abstand] sold out [„sold out“ fett, kursiv]
11. [Bild] `aktuelle/bild2.jpg` [620 × 640 px]
    - [Bildtext] Funky Muh 1, mixed media in Acryl, 2023 80x80cm

### Inhalt – Teil 2: Slideshow

[23 Bilder mit Pfeilen, Vorschaubildern (horizontal) und Lightbox; kein automatischer Bildwechsel. Der Titel jedes Bildes wird angezeigt (in der Slideshow und in der Lightbox) und entspricht dem Dateinamen ohne Endung; der alt-Text ist derselbe. Bilder 16–23 stehen nicht im Seiten-HTML, sondern werden per JavaScript nachgeladen (siehe INHALT-PRUEFEN.md, Abschnitt 4).]

| Nr. | Datei | Pixel | [angezeigter Titel] |
|---|---|---|---|
| 1 | `acryl.jpg` | 2667 × 2667 | acryl |
| 2 | `aquarell.jpg` | 3024 × 4032 | aquarell |
| 3 | `acryl7.jpg` | 2828 × 2119 | acryl7 |
| 4 | `acryl6.jpg` | 3803 × 1828 | acryl6 |
| 5 | `acryl3.jpg` | 3941 × 2930 | acryl3 |
| 6 | `aquarell2.jpg` | 2890 × 1717 | aquarell2 |
| 7 | `aquarell4.jpg` | 2893 × 1743 | aquarell4 |
| 8 | `aquarell5.jpg` | 3024 × 4032 | aquarell5 |
| 9 | `aquarell6.jpg` | 2873 × 3960 | aquarell6 |
| 10 | `aquarell7.jpg` | 750 × 984 | aquarell7 |
| 11 | `aquarell8.jpg` | 3024 × 4032 | aquarell8 |
| 12 | `B02646BD-5D0A-4010-8CE2-297C9A3F7DAE.JPG` | 3024 × 3024 | B02646BD-5D0A-4010-8CE2-297C9A3F7DAE |
| 13 | `IMG_4086.jpg` | 2882 × 3842 | IMG_4086 |
| 14 | `IMG_4248.jpg` | 3024 × 4032 | IMG_4248 |
| 15 | `IMG_4266.jpg` | 3024 × 4032 | IMG_4266 |
| 16 | `IMG_4267.jpg` [nachgeladen] | 3024 × 4032 | IMG_4267 |
| 17 | `IMG_4286.jpg` [nachgeladen] | 3795 × 2846 | IMG_4286 |
| 18 | `IMG_4406.jpg` [nachgeladen] | 3024 × 4032 | IMG_4406 |
| 19 | `IMG_4334.jpg` [nachgeladen] | 3024 × 4032 | IMG_4334 |
| 20 | `IMG_4456.jpg` [nachgeladen] | 3858 × 2893 | IMG_4456 |
| 21 | `IMG_4560.jpg` [nachgeladen] | 2882 × 3844 | IMG_4560 |
| 22 | `IMG_5447.jpg` [nachgeladen] | 750 × 750 | IMG_5447 |
| 23 | `leharts_juden_n***a.jpg` [nachgeladen; ⚠️ Name hier bewusst gekürzt, siehe Hinweis unten] | 3024 × 4032 | [⚠️ = Dateiname ohne Endung; nicht übernehmen] |

> ⚠️ **Hinweis zu Nr. 23:** Der Dateiname – und damit der öffentlich angezeigte Titel und alt-Text – enthält eine rassistische Beleidigung (N-Wort). Er ist hier absichtlich gekürzt, damit er nicht versehentlich auf die neue Website oder in ein öffentliches Repository gelangt. Exakter Name: die einzige Datei in `C:\Users\taakijo2\Documents\leharts\Bilder`, die mit `leharts_juden_` beginnt. Details: [INHALT-PRUEFEN.md](INHALT-PRUEFEN.md), Punkt 3.1.

### Inhalt – Teil 3: Einzelbilder [Bildtexte in kleiner Schrift]

12. [Bild; Klick vergrössert das Bild] `1 power, mixed media, 80x100cm.JPG` [2744 × 3564 px]
    - [Bildtext] Power, Öl auf Acryl, 2017, 80x100cm
13. [Bild] `2 Weitsicht, mixed media, 100x100.JPG` [3470 × 3467 px]
    - [Bildtext] Weitsicht, mixed media, 2017, 100x100cm
14. [Bild] `3 tierra, mixed media, 50x150cm .JPG` [5323 × 1752 px]
    - [Bildtext] Tierra, mixed media, 50x150cm
15. [Bild] `4 esperanza, mixed media, 100x100_1.JPG` [3488 × 3537 px]
    - [Bildtext] Esperanza, mixed media, 100x100cm
16. [Bild] `6 submarino, mixed media, 70x100cm _1.JPG` [4854 × 3377 px]
    - [Bildtext] Submarino, mixed media, 70x100cm
17. [Bild] `8 alegria, mixed media auf Holz, 80x80cm.JPG` [3097 × 3100 px]
    - [Bildtext] Alegria, mixed media auf Holz, 80x80cm
18. [Bild] `9 feliz, mixed media, 80x120 _1.JPG` [4977 × 3288 px]
    - [Bildtext] Feliz, mixed media, 80x120cm
19. [Bild] `12 Africa, mixed media, 60x50cm _1.JPG` [2327 × 3459 px]
    - [Bildtext] Africa, mixed media, 60x65cm
20. [Bild] `14 sorpresa, mixed media, 100x100cm_1.jpg` [2712 × 2713 px]
    - [Bildtext] Sorpresa, mixed media, 100x100cm [Abstand] sold out [„sold out“ hier nicht fett/kursiv]
21. [Bild] `15 japanese spring, mixed media, 60x60cm_1.jpg` [3024 × 4032 px]
    - [Bildtext] Japanese spring, mixed media, 60x60cm
22. [Bild] `aktuelle/bild7.jpg` [584 × 640 px]
    - [kein Bildtext]

---

## Seite 5: Photography

- [URL] https://leharts.ch/Photography/
- [Seitentitel] lehARTs - Photography
- [Aktiver Menüpunkt: Photography; Menü, Kopfbereich, Kontaktblock, Fusszeile wie oben]
- [Kopfbild, CSS-Hintergrund] `IMG_0379_1.JPG` [Pixelmasse auf der alten Site nicht angegeben]

### Inhalt

1. [Überschrift H1 ohne Text (leer)]
2. [Bildergalerie mit 21 Bildern, Raster mit Lightbox. Keine Bildtexte, Titel werden nicht angezeigt; alt-Text = Dateiname ohne Endung. Im Seiten-HTML stehen nur die Bilder 1–15.]

| Nr. | Datei | Pixel |
|---|---|---|
| 1 | `B829EF0E-C1A8-4975-8ACA-5F9D75505B9E.JPG` | 1280 × 720 |
| 2 | `BE81EB86-40C6-4E8B-8BF4-5EBAB2C50619_1.jpg` | 1242 × 699 |
| 3 | `bild dreck.jpg` | 1253 × 683 |
| 4 | `blume.jpg` | 1150 × 704 |
| 5 | `IMG_4191.jpg` | 2081 × 3699 |
| 6 | `IMG_4753.jpg` | 4032 × 3024 |
| 7 | `IMG_5262.jpg` | 3024 × 4032 |
| 8 | `IMG_5386.jpg` | 3024 × 4032 |
| 9 | `IMG_5407.jpg` | 673 × 1197 |
| 10 | `IMG_4619.JPG` | 1280 × 720 |
| 11 | `photography13.jpg` | 1280 × 720 |
| 12 | `photography15.jpg` | 2913 × 3924 |
| 13 | `photography17.jpg` | 2924 × 2193 |
| 14 | `photography12.jpg` | 2823 × 2233 |
| 15 | `digitalart8.jpg` | 572 × 572 |

3. mehr... [Link unter der Galerie, Ziel `#`; lädt per JavaScript die Bilder 16–21 nach (auch automatisch beim Scrollen) und verschwindet danach]

| Nr. | Datei [nachgeladen] | Pixel |
|---|---|---|
| 16 | `photography10.jpg` | 1301 × 1301 |
| 17 | `photography38.jpg` | 2448 × 3060 |
| 18 | `photography16.jpg` | 2523 × 2523 |
| 19 | `aktuelle/bilg1.jpg` | 586 × 640 |
| 20 | `aktuelle/bild8.jpg` | 480 × 640 |
| 21 | `aktuelle/bild5.jpg` | 467 × 467 |

---

## Seite 6: More Projects

- [URL] https://leharts.ch/More-Projects/
- [Seitentitel] lehARTs - More Projects
- [Aktiver Menüpunkt: More Projects; Menü, Kopfbereich, Kontaktblock, Fusszeile wie oben]
- [Kopfbild, CSS-Hintergrund] `otherproje10.jpg` [Pixelmasse auf der alten Site nicht angegeben]

### Inhalt [keine Bildtexte; alt-Texte leer]

1. [Bild] `aktuelle/bild9.jpg` [640 × 640 px]
2. [Überschrift H1, zentriert] "Kunst für unterwegs - immer dabei, immer einzigartig."
3. [Bild] `30D5B701-8D16-427F-AE42-7F316DAFE69C.jpg` [640 × 640 px]
4. [Bild] `skulpturen2.jpg` [4032 × 3024 px]
5. [Bild] `Skulpturen_1.jpg` [4032 × 3024 px]
6. [Bild] `otherproject8.jpg` [2936 × 3850 px]
7. [Bild] `pencildrawing.jpg` [750 × 550 px]
8. [Bild] `sunprint3.jpg` [3241 × 2205 px]
9. [Bild] `irgend ein bildE.jpg` [1242 × 698 px]
10. [Bild] `IMG_4560.jpg` [2882 × 3844 px; auch in der paintings-Slideshow, Nr. 21]
11. [Bild] `sunprint8.jpg` [3024 × 3024 px]
12. [Bild] `otherproject3.jpg` [3024 × 4032 px]
13. [Bild] `aquarell7.jpg` [750 × 984 px; auch in der paintings-Slideshow, Nr. 10]

---

## Anhang A: Texte der Plattform (Cookie-Hinweis)

[Von der Baukasten-Plattform (CM4all/Hostpoint) automatisch auf allen Seiten eingefügt, nicht von der Künstlerin verfasst. Beide Elemente sind im HTML vorhanden, aber zunächst versteckt.]

### Fenster „Cookie-Einstellungen“

1. [Überschrift] Cookie-Einstellungen
2. [Schliessen-Symbol, Tooltip] Schließen
3. [Text] Diese Webseite verwendet Cookies, um Besuchern ein optimales Nutzererlebnis zu bieten. Bestimmte Inhalte von Drittanbietern werden nur angezeigt, wenn die entsprechende Option aktiviert ist. Die Datenverarbeitung kann dann auch in einem Drittland erfolgen. Weitere Informationen hierzu in der Datenschutzerklärung. [„Datenschutzerklärung“ ist kein Link]
4. [Schalter] Technisch notwendige [Tooltip: Erweitern / Zuklappen]
   - [Text] Diese Cookies sind zum Betrieb der Webseite notwendig, z.B. zum Schutz vor Hackerangriffen und zur Gewährleistung eines konsistenten und der Nachfrage angepassten Erscheinungsbilds der Seite.
5. [Schalter] Analytische [Tooltip: Erweitern / Zuklappen]
   - [Text] Diese Cookies werden verwendet, um das Nutzererlebnis weiter zu optimieren. Hierunter fallen auch Statistiken, die dem Webseitenbetreiber von Drittanbietern zur Verfügung gestellt werden, sowie die Ausspielung von personalisierter Werbung durch die Nachverfolgung der Nutzeraktivität über verschiedene Webseiten.
6. [Schalter] Drittanbieter-Inhalte [Tooltip: Erweitern / Zuklappen]
   - [Text] Diese Webseite bietet möglicherweise Inhalte oder Funktionalitäten an, die von Drittanbietern eigenverantwortlich zur Verfügung gestellt werden. Diese Drittanbieter können eigene Cookies setzen, z.B. um die Nutzeraktivität zu verfolgen oder ihre Angebote zu personalisieren und zu optimieren.
7. [Schaltfläche] Ablehnen
8. [Schaltfläche] Alle akzeptieren
9. [Schaltfläche] Speichern

### Platzhalter „Externe Inhalte“ [Vorlage für blockierte Drittanbieter-Inhalte; auf den 6 Seiten gibt es keine solchen Inhalte]

1. [Überschrift] Externe Inhalte
2. [Text] Die an dieser Stelle vorgesehenen Inhalte können aufgrund Ihrer aktuellen Cookie-Einstellungen nicht angezeigt werden. [„Cookie-Einstellungen“ = Link, öffnet das Cookie-Fenster]
3. [Schalter] Drittanbieter-Inhalte
4. [Text] Diese Webseite bietet möglicherweise Inhalte oder Funktionalitäten an, die von Drittanbietern eigenverantwortlich zur Verfügung gestellt werden. Diese Drittanbieter können eigene Cookies setzen, z.B. um die Nutzeraktivität zu verfolgen oder ihre Angebote zu personalisieren und zu optimieren.

## Anhang B: Technische Elemente ohne Inhalt

- [Statistik-Pixel von Hostpoint (`https://sites.hostpoint.com/.cm4all/_pixel.img?...`) auf jeder Seite – ein Tracker, kein Inhalt]
- [Leere Seitenleisten-Bereiche, leere Absätze, Abstandhalter – nur Layout]

## Anhang C: Bildzählung

| Seite | Inhaltsbilder | Kopfbild |
|---|---|---|
| About | 1 | 1 (`IMG_3849.jpg`) |
| News | 0 | – |
| PAST EXHIBITIONS | 2 | 1 (`IMG_3849.jpg`) |
| paintings | 45 (22 Einzelbilder + 23 Slideshow) | 1 (`14 sorpresa, mixed media, 100x100cm_1.jpg`) |
| Photography | 21 | 1 (`IMG_0379_1.JPG`) |
| More Projects | 12 | 1 (`otherproje10.jpg`) |
| Logo (alle Seiten) | – | 1 (`1 power, mixed media, 80x100cm.JPG`) |

Insgesamt 87 Bildverwendungen, davon 82 verschiedene Dateien. Mehrfach verwendet: `IMG_3849.jpg` (2 Kopfbilder), `1 power, mixed media, 80x100cm.JPG` (Logo + Werk), `14 sorpresa, mixed media, 100x100cm_1.jpg` (Kopfbild + Werk), `aquarell7.jpg` und `IMG_4560.jpg` (paintings-Slideshow + More Projects).
