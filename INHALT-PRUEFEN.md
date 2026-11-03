# INHALT-PRUEFEN – offene Punkte zur alten Website leharts.ch

Stand: 03.11.2026 · Grundlage: [INHALT.md](INHALT.md) · Der Abgleich selbst hat nichts korrigiert, umbenannt oder gelöscht. Beim Umsetzen (Schritt C) wurden die 10 verwendeten Gemälde aus `images\Gemälde\` unverändert in `images\` kopiert (siehe 3.8).

**Lokaler Vergleichsordner:** lokaler Bilderordner inklusive der Unterordner `Gemälde\` und `AusstellungsFlyer\` (155 Dateien: 150 Bilder, 5 PDF). Im Projekt gibt es noch keinen Ordner `/images`.

> **Offen, mit der Künstlerin klären:** Punkt 3.1 (unten) – Slideshow Nr. 23: Datei umbenannt zu painting-23.jpg, wird nicht verwendet.

## Überblick

| | Anzahl |
|---|---|
| Bildverwendungen auf der alten Website (inkl. Logo und Kopfbilder) | 87 |
| davon verschiedene Dateien | 82 |
| … lokal mit exakt gleichem Dateinamen vorhanden | 76 |
| … lokal nur unter abweichendem Namen vorhanden (ohne „_1“) | 6 |
| … lokal gar nicht vorhanden | 0 |
| Lokale Duplikate von verwendeten Bildern (inhaltsgleich) | 6 |
| Lokale Bilder ohne Zuordnung | 62 |
| Lokale PDF-Dateien (keine Bilder) | 5 |

---

## 1. Bilder auf der alten Website, die lokal fehlen

**Ergebnis:** Inhaltlich fehlt kein Bild. Aber **6 Dateien gibt es lokal nicht unter dem Original-Dateinamen** der alten Website: Lokal fehlt jeweils das „_1“ am Ende des Namens. Die Pixelmasse sind identisch, es ist also sehr wahrscheinlich dasselbe Bild.

| Dateiname auf der alten Website | lokal vorhanden als | Pixel | verwendet auf |
|---|---|---|---|
| `14 sorpresa, mixed media, 100x100cm_1.jpg` | `Gemälde\14 sorpresa, mixed media, 100x100cm.jpg` | 2712 × 2713 | paintings (Kopfbild und Werk „Sorpresa“) |
| `4 esperanza, mixed media, 100x100_1.JPG` | `Gemälde\4 esperanza, mixed media, 100x100.JPG` | 3488 × 3537 | paintings |
| `6 submarino, mixed media, 70x100cm _1.JPG` | `Gemälde\6 submarino, mixed media, 70x100cm .JPG` | 4854 × 3377 | paintings |
| `9 feliz, mixed media, 80x120 _1.JPG` | `Gemälde\9 feliz, mixed media, 80x120 .JPG` | 4977 × 3288 | paintings |
| `12 Africa, mixed media, 60x50cm _1.JPG` | `Gemälde\12 Africa, mixed media, 60x50cm .JPG` | 2327 × 3459 | paintings |
| `15 japanese spring, mixed media, 60x60cm_1.jpg` | `Gemälde\15 japanese spring, mixed media, 60x60cm.jpg` | 3024 × 4032 | paintings |

→ **Zu entscheiden:** Laut Projektregel liegen die Bilder in `/images` mit den Original-Dateinamen der alten Website. Diese 6 Dateien müssten dafür beim Befüllen von `/images` unter dem Namen mit „_1“ abgelegt werden.

**Gleicher Name, aber anderer Ordner (zur Info, nichts fehlt):**

- Auf der alten Website im Unterordner `aktuelle/`, lokal direkt im Hauptordner: `bild2.jpg`, `bild3.jpg`, `bild4.jpg`, `bild5.jpg`, `bild6.jpg`, `bild7.jpg`, `bild8.jpg`, `bild9.jpg`, `bild10.jpg`, `bild11.jpg`, `bilg1.jpg`. → Entscheiden, ob `/images` flach bleibt oder einen Unterordner `aktuelle/` bekommt.
- Lokal im Unterordner `Gemälde\`, auf der alten Website ohne Unterordner: `1 power, mixed media, 80x100cm.JPG`, `2 Weitsicht, mixed media, 100x100.JPG`, `3 tierra, mixed media, 50x150cm .JPG`, `8 alegria, mixed media auf Holz, 80x80cm.JPG` (sowie die 6 Dateien aus der Tabelle oben).

**Technische Hinweise für `/images`:**

- Viele Namen enthalten Leerzeichen und Kommas, einige ein Leerzeichen direkt vor der Endung (z. B. `3 tierra, mixed media, 50x150cm .JPG`, `9 feliz, mixed media, 80x120 _1.JPG`). Das funktioniert, muss im HTML aber korrekt kodiert werden.
- Die Endungen sind gemischt (`.jpg`, `.JPG`, `.png`). GitHub Pages unterscheidet Gross-/Kleinschreibung – die Namen müssen exakt stimmen.

**Grenzen des Abgleichs:** Verglichen wurden Dateinamen und die Pixelmasse, die die alte Website im HTML angibt. Alle 79 vorhandenen Pixelangaben stimmen mit den lokalen Dateien überein. Für die Kopfbilder `IMG_3849.jpg`, `IMG_0379_1.JPG` und `otherproje10.jpg` nennt die alte Website keine Masse (nur Namensabgleich). Beim Logo `1 power, mixed media, 80x100cm.JPG` stimmt sogar die Dateigrösse (4 623 755 Bytes) überein. Die Originaldateien selbst wurden nicht heruntergeladen.

---

## 2. Lokale Bilder ohne Zuordnung

### 2.1 Duplikate von Bildern, die auf der alten Website vorkommen

Inhaltlich identisch (Prüfsumme MD5 gleich) mit einer verwendeten Datei – werden also nicht zusätzlich gebraucht.

| Lokale Datei | identisch mit (Name auf alter Website) | verwendet auf |
|---|---|---|
| `IMG_0379.JPG` | `IMG_0379_1.JPG` | Photography (Kopfbild) |
| `BE81EB86-40C6-4E8B-8BF4-5EBAB2C50619.jpg` | `BE81EB86-40C6-4E8B-8BF4-5EBAB2C50619_1.jpg` | Photography |
| `Skulpturen.jpg` | `Skulpturen_1.jpg` | More Projects |
| `JahresaustellungEinsiedelnLeharts(1).png` | `JahresaustellungEinsiedelnLeharts.png` | PAST EXHIBITIONS |
| `AusstellungsFlyer\JahresaustellungEinsiedelnLeharts.png` | `JahresaustellungEinsiedelnLeharts.png` | PAST EXHIBITIONS |
| `AusstellungsFlyer\AusstellungNatürlichKunst_Bäch.png` | `Screenshot 2024-03-26 200940.png` | PAST EXHIBITIONS („Natürlich Kunst“, November 2022) |

### 2.2 Gemälde ohne Zuordnung (Unterordner `Gemälde\`)

Die Werke auf „paintings“ tragen die Nummern 1, 2, 3, 4, 6, 8, 9, 12, 14 und 15. Die fehlenden Nummern 5, 7, 10, 11 und 13 sowie die Nummer 16 liegen nur lokal vor:

| Lokale Datei | Pixel | Grösse | Hinweis |
|---|---|---|---|
| `Gemälde\5 sentirse, mixed media, 80x180 .JPG` | 1514 × 3586 | 1.3 MB | |
| `Gemälde\7 la vida, mixed media, 80x120cm .JPG` | 3104 × 3095 | 3.0 MB | |
| `Gemälde\10 Fronalpstock GL, mixed media, .JPG` | 4757 × 3187 | 4.7 MB | Masse fehlen im Namen |
| `Gemälde\11 disfruta la vida, mixed media, 80x120cm .JPG` | 2238 × 3502 | 1.9 MB | |
| `Gemälde\13 corazon verde, in Acryl, 100x70cm.jpg` | 2396 × 2397 | 3.1 MB | |
| `Gemälde\16 west eclipse mixed media, 80x60cm.jpg` | 3024 × 4032 | 3.8 MB | |

### 2.3 Weitere Bilder ohne Zuordnung (56)

**a) Aus Serien, von denen andere Teile verwendet werden**

| Lokale Datei | Pixel | Grösse | Hinweis |
|---|---|---|---|
| `Digitalart.jpg` | 701 × 733 | 142 KB | verwendet wird nur `digitalart8.jpg` (Photography) |
| `digitalart2.jpg` | 2559 × 3910 | 3.7 MB | |
| `digitalart3.jpg` | 475 × 808 | 74 KB | |
| `digitalart5.jpg` | 1810 × 2421 | 1.2 MB | |
| `digitalart6.jpg` | 3363 × 3320 | 1.7 MB | |
| `digitalart7.jpg` | 550 × 550 | 73 KB | |
| `otherproject4.jpg` | 578 × 754 | 182 KB | verwendet: `otherproject3.jpg`, `otherproject8.jpg`, `otherproje10.jpg` |
| `otherproject5.jpg` | 2906 × 3901 | 1.6 MB | |
| `otherproject6.jpg` | 4032 × 3024 | 4.0 MB | |
| `otherproject7.jpg` | 3970 × 2965 | 2.0 MB | |
| `sunprint5.jpg` | 2942 × 3677 | 3.3 MB | verwendet: `sunprint3.jpg`, `sunprint8.jpg` |
| `sunprint7.jpg` | 3024 × 4032 | 2.5 MB | |
| `sunprint9.jpg` | 2896 × 3918 | 2.1 MB | |
| `sunprint10.jpg` | 3024 × 4032 | 2.2 MB | |
| `sunprint11.jpg` | 2167 × 3855 | 2.8 MB | |
| `pencildrawing2.jpg` | 3633 × 2994 | 995 KB | verwendet: `pencildrawing.jpg` |

**b) Ausstellung, Logo, Titelblatt**

| Lokale Datei | Pixel | Grösse | Hinweis |
|---|---|---|---|
| `Flyer_Ausstellung_2022_Kistler_Cantieni.jpg` | 2481 × 3508 | 838 KB | identisch mit `…_1.jpg`; Name passt zu „Natürlich Kunst“ (November 2022, Kistler/Cantieni) |
| `Flyer_Ausstellung_2022_Kistler_Cantieni_1.jpg` | 2481 × 3508 | 838 KB | identisch mit der Datei ohne `_1` |
| `logo_1.png` | 489 × 231 | 5 KB | möglicherweise ein Logo; die alte Website nutzt stattdessen das Gemälde „power“ und den Text „lehARTs“ |
| `Titelblatt.jpg` | 3024 × 4032 | 2.3 MB | |

**c) Sonstige mit sprechendem Namen**

| Lokale Datei | Pixel | Grösse | Hinweis |
|---|---|---|---|
| `AfterlightImage.JPG` | 1280 × 720 | 193 KB | |
| `fotograf-bild-frau.jpg` | 1000 × 664 | 150 KB | Herkunft/Verwendung klären |
| `fotograf-bild-maedchen.jpg` | 1000 × 667 | 168 KB | Herkunft/Verwendung klären |
| `fotograf-trompeter.jpg` | 1000 × 667 | 97 KB | Herkunft/Verwendung klären |
| `unnamed.jpg` | 3465 × 3465 | 1.2 MB | |

**d) Kamera- bzw. Systemnamen**

| Lokale Datei | Pixel | Grösse | Hinweis |
|---|---|---|---|
| `5805D9DF-F802-437C-A047-C0D20E34ADAC.JPG` | 750 × 729 | 351 KB | |
| `66B9E543-C8FC-4713-9E86-81D991CADD6F.jpg` | 1240 × 692 | 342 KB | identisch mit `…_1.jpg` |
| `66B9E543-C8FC-4713-9E86-81D991CADD6F_1.jpg` | 1240 × 692 | 342 KB | identisch mit der Datei ohne `_1` |
| `720CA22F-C767-418F-947C-492ED45FEBB6.JPG` | 1228 × 694 | 136 KB | identisch mit `…_1.JPG` |
| `720CA22F-C767-418F-947C-492ED45FEBB6_1.JPG` | 1228 × 694 | 136 KB | identisch mit der Datei ohne `_1` |
| `C71A96DB-FA92-432F-8D8E-A9A3B9A5A9BC.JPG` | 750 × 750 | 130 KB | |
| `IMG_0553.jpg` | 310 × 640 | 138 KB | |
| `IMG_1920.jpg` | 640 × 640 | 261 KB | |
| `IMG_4182.jpg` | 2857 × 3809 | 5.6 MB | |
| `IMG_4277.jpg` | 4032 × 3024 | 3.8 MB | |
| `IMG_4640.jpg` | 750 × 417 | 430 KB | |
| `IMG_4642.jpg` | 750 × 707 | 271 KB | |
| `IMG_4758.jpg` | 740 × 740 | 373 KB | |
| `IMG_4771.JPG` | 1280 × 720 | 212 KB | |
| `IMG_5010.JPG` | 3024 × 4032 | 3.8 MB | |
| `IMG_5103.jpg` | 659 × 659 | 46 KB | |
| `IMG_5182.jpg` | 704 × 704 | 210 KB | |
| `IMG_5205.jpg` | 705 × 705 | 227 KB | |
| `IMG_5228.jpg` | 625 × 625 | 172 KB | |
| `IMG_5254.jpg` | 660 × 660 | 237 KB | |
| `IMG_5299.jpg` | 714 × 714 | 106 KB | |
| `IMG_5300.jpg` | 750 × 750 | 113 KB | |
| `IMG_5305.jpg` | 634 × 634 | 143 KB | |
| `IMG_5319.jpg` | 720 × 720 | 235 KB | |
| `IMG_5346.jpg` | 744 × 744 | 182 KB | |
| `IMG_5488.jpg` | 2688 × 3584 | 3.9 MB | |
| `IMG_5489.jpg` | 3024 × 4032 | 2.0 MB | |
| `IMG_5535.JPG` | 1280 × 720 | 132 KB | |
| `IMG_5564.jpg` | 750 × 750 | 318 KB | |
| `IMG_5585.jpg` | 750 × 750 | 92 KB | |
| `IMG_7866.JPG` | 640 × 640 | 232 KB | |

### 2.4 Keine Bilder (PDF) – auf der alten Website nirgends verlinkt

| Lokale Datei | Grösse | Hinweis |
|---|---|---|
| `Kistler_Rahel_Kunstbuch_gzd.pdf` | 3.7 MB | `_1`, `_2`, `_3` sind identische Kopien |
| `Kistler_Rahel_Kunstbuch_gzd_1.pdf` | 3.7 MB | Kopie |
| `Kistler_Rahel_Kunstbuch_gzd_2.pdf` | 3.7 MB | Kopie |
| `Kistler_Rahel_Kunstbuch_gzd_3.pdf` | 3.7 MB | Kopie |
| `Kistler_Rahel_VK_gzd.pdf` | 1.9 MB | |

---

## 3. Inhaltliche Unstimmigkeiten (nicht korrigiert)

### 3.1 Slideshow Nr. 23 (paintings)

- Slideshow Nr. 23: Datei umbenannt zu painting-23.jpg, wird nicht verwendet (Entscheidung offen, mit der Künstlerin klären).

### 3.2 Aktualität und Verweise

1. **About:** „Zukünftige Ausstellungen [Abstand] !!!“ mit „(für mehr Infos, auf News klicken)“ – auf **News** steht aber nur „Es gibt bald Neuigkeiten. Seid gespannt! :)“, also keine Ausstellungsinfos. Die jüngste Ausstellung auf PAST EXHIBITIONS (März 2026 - Mai 2026, Morschach) ist vorbei (Stand 03.11.2026); eine künftige Ausstellung wird nirgends genannt.
2. **Button „Hier geht's zur Kunstschwyz Seite“** → `http://kunstschwyz.ch`: wird auf `https://kunstschwyz.ch/` umgeleitet (Link noch mit http). Beim Abruf am 03.11.2026 zeigt die Seite eine Ausstellung anderer Künstlerinnen (Ursula Conz, Regula Gysin) – der Bezug zu „Zukünftige Ausstellungen“ ist unklar.
3. **Datenschutzerklärung:** Der Cookie-Hinweis verweist auf eine „Datenschutzerklärung“, die es auf der Website nicht gibt (kein Link, keine Seite; auch kein Impressum). Die Cookie-Texte stammen von der Plattform und passen nicht zur neuen Website ohne Cookies – übernehmen ja/nein entscheiden (Texte siehe INHALT.md, Anhang A).
4. **Startseite / About:** `https://leharts.ch/` zeigt die Seite „About“. Der Fusszeilen-Link heisst „Startseite“, der Menüpunkt „About“ – zwei Namen für dieselbe Seite.

### 3.3 PAST EXHIBITIONS

1. Die Hauptüberschrift (H1) „\*Kuratierte Ausstellungen“ wirkt wie die Erklärung des Sternchens (\* bei Morschach, Pfäffikon 2022, Swissphotoclub und Artbox), steht aber als Titel über der ganzen Liste. Die Seite selbst heisst „PAST EXHIBITIONS“.
2. „„Natürlich Kunst“ im Bahnhof Bäch vom“ – der Satz bricht nach „vom“ ab, das Datum fehlt (im Fliesstext: „vom 25. November bis 10. Dezember“).
3. Tippfehler „Sparziergang“ im zweiten Absatz (im ersten Absatz richtig: „Spaziergang“).
4. „11. Mai 2024 - 26 . Mai 2024“: Leerzeichen vor dem Punkt („26 .“); als einzige Datumszeile ohne Doppelpunkt.
5. Reihenfolge: sonst neueste zuerst, innerhalb 2024 aber aufsteigend (März 2024 → Mai 2024 → Oktober 2024).
6. Vereinsname uneinheitlich: „Verein Kunst Schwyz Morschach\*“, „Verein Kunst Schwyz/Pfäffikon“, „Verein Kunst Schwyz, Pfäffikon\*“, „Verein Kunst Schwyz, Siebnen“.
7. Struktur uneinheitlich: Datum und Ausstellung stehen teils als Überschriften (H2, kursiv), teils als fett-kursive Absätze; „„Natürlich Kunst“ …“ ist eine H2, das Datum davor ein Absatz.
8. Dateiname `JahresaustellungEinsiedelnLeharts.png` mit nur einem „s“ in „Jahresaustellung“ (im Text: „Jahresausstellung“). Betrifft nur den Dateinamen.
9. Zur Info, keine Unstimmigkeit: `Screenshot 2024-03-26 200940.png` beim Eintrag November 2022 ist inhaltlich identisch mit dem lokalen Flyer `AusstellungsFlyer\AusstellungNatürlichKunst_Bäch.png` – die Zuordnung passt, nur der Dateiname ist nichtssagend.

### 3.4 paintings

1. Zwei Bilder direkt hintereinander (`DD5995C3-086F-4C83-B417-40284BF2FF25.JPG`, `C428B35D-4A85-47E1-B2DB-97A8C013179D.JPG`), danach nur ein Bildtext („Vibes, Öl und Acryl auf Leinwand, 2024, 30x30cm“). Unklar, zu welchem Bild er gehört; das andere hat keinen Bildtext. Dazwischen steht ein leerer Link (kein Text, kein Ziel).
2. Das letzte Bild (`aktuelle/bild7.jpg`) hat keinen Bildtext.
3. Slideshow (23 Bilder): Die angezeigten Titel sind Dateinamen („acryl“, „aquarell2“, „IMG_4086“, „B02646BD-5D0A-4010-8CE2-297C9A3F7DAE“ usw.), keine Werktitel; Technik, Jahr und Masse fehlen.
4. Dateiname und Bildtext widersprechen sich:
   - `1 power, mixed media, 80x100cm.JPG` ↔ „Power, Öl auf Acryl, 2017, 80x100cm“ (Technik: mixed media ↔ Öl auf Acryl)
   - `12 Africa, mixed media, 60x50cm _1.JPG` ↔ „Africa, mixed media, 60x65cm“ (Masse: 60x50cm ↔ 60x65cm)
5. Technik-Angaben uneinheitlich bzw. ungewöhnlich: „Öl auf Acryl“ (Freedom in Connection, Nebula, Power), „Öl und Acryl auf Leinwand“ (Vibes), „Acryl auf Mixed Media auf Leinwand“ (Furry news), „mixed media in Acryl“ (High on Speed, Funky Muh 1, Funky Muh 2, Aries). Schreibweise „Mixed Media“ (Furry news, Love) neben „mixed media“ (alle übrigen).
6. Fehlende Angaben (bleiben leer): kein Jahr bei Tierra, Esperanza, Submarino, Alegria, Feliz, Africa, Sorpresa und Japanese spring; keine Masse bei Love.
7. „Funky Muh 1, mixed media in Acryl, 2023 80x80cm“ – das Komma zwischen Jahr und Massen fehlt (bei allen anderen vorhanden).
8. „sold out“ ist bei Sorpresa normal geschrieben, bei Furry news, Love, Funky cow, Nebula und Aries fett und kursiv.
9. Nur Hinweis (unsicher): Das Fotoformat passt nicht zum angegebenen Werkformat bei „Japanese spring, mixed media, 60x60cm“ (Foto 3:4 hoch statt quadratisch) und „Africa, mixed media, 60x65cm“ (Foto etwa 2:3 hoch). Vielleicht zeigt das Foto mehr als nur das Werk.
10. Zur Info: Einige Bilder sind mehrfach verwendet – `14 sorpresa, mixed media, 100x100cm_1.jpg` (Kopfbild und Werk), `1 power, mixed media, 80x100cm.JPG` (Logo und Werk), `aquarell7.jpg` und `IMG_4560.jpg` (paintings-Slideshow und More Projects).

### 3.5 Photography

1. Keine Bildtexte. Die Titel werden nicht angezeigt, die alt-Texte sind Dateinamen (z. B. „bild dreck“, „IMG_4191“, „B829EF0E-C1A8-4975-8ACA-5F9D75505B9E“).
2. Zuordnung prüfen: `aktuelle/bilg1.jpg`, `aktuelle/bild8.jpg` und `aktuelle/bild5.jpg` stammen aus demselben Ordner wie die Gemälde `bild2`–`bild11` auf paintings bzw. More Projects; `digitalart8.jpg` heisst „digitalart“. Alle vier stehen in der Photography-Galerie.
3. Dateiname `bilg1.jpg` – vermutlich Tippfehler für „bild1“ (Reihe bild2–bild11; ein „bild1“ gibt es weder online noch lokal). Betrifft nur den Dateinamen.
4. Über der Galerie steht eine leere Hauptüberschrift (H1 ohne Text).

### 3.6 More Projects

1. Die einzige Überschrift (H1) "Kunst für unterwegs - immer dabei, immer einzigartig." steht zwischen dem 1. und 2. Bild. Ohne Bildtexte ist unklar, worauf sie sich bezieht. Sie hat gerade Anführungszeichen ("…"), sonst verwendet die Website „…“.
2. Keine Bildtexte zu Skulpturen, Zeichnung, Sunprints usw. – nicht erkennbar, was die einzelnen Projekte sind.
3. Auffällige Dateinamen: `irgend ein bildE.jpg` (wirkt wie ein Platzhaltername), `otherproje10.jpg` (Kopfbild; wirkt neben `otherproject3.jpg`/`otherproject8.jpg` abgeschnitten).

### 3.7 Seitenübergreifend und Konflikte mit den Projektregeln

1. Menü: Schreibweise uneinheitlich („About“, „News“, „PAST EXHIBITIONS“, „paintings“, „Photography“, „More Projects“). Menü auf Englisch, Inhalte auf Deutsch.
2. Meta-Description auf allen Seiten gleich („Bilder sagen mehr als tausend Worte“), kein og:image, keine og:description. Die Projektregeln verlangen eine Meta-Description und Open-Graph-Tags pro Seite, verbieten aber, etwas zu erfinden → Texte müssen von der Künstlerin kommen (oder bewusst überall dieselbe Description).
3. alt-Texte: Einzelbilder haben leere alt-Texte, Galerie und Slideshow Dateinamen. Die Projektregeln verlangen „sinnvolle“ alt-Texte, verbieten aber Erfundenes → Vorgaben nötig, besonders für Bilder ohne Bildtext.
4. Kontaktblock: Telefon, E-Mail und Website sind auf der alten Website reiner Text, keine Links (nur Info).

### 3.8 Beim Umsetzen aufgefallen (Schritt C)

1. **Keine Hauptüberschrift (H1)** auf About, News und paintings (auch auf der alten Website nicht). Der Website-Titel „lehARTs“ ist nur ein Absatz. Für Screenreader wäre eine H1 pro Seite besser; dafür bräuchte es eine Entscheidung (z. B. visuell versteckte H1 mit dem Seitennamen wie bei Photography).
2. **alt-Text About-Bild** (`schlusswort.jpg`): Die Regeln nennen keinen Text dafür; vorläufig „Bild“. Das Bild zeigt eine Person; ein sinnvoller alt-Text müsste von der Künstlerin kommen.
3. **PAST EXHIBITIONS:** alt-Texte vorläufig „Ausstellung, Bild 1 von 2“ und „Ausstellung, Bild 2 von 2“ (Regel „neutral nach Bereich und Position“).
4. **„Vibes“:** Der Bildtext steht nach beiden Bildern. Vorläufig trägt das Bild `C428B35D…` (stand direkt über dem Text) den alt-Text „Vibes“, das Bild `DD5995C3…` den alt-Text „Gemälde“. Ob das stimmt, ist offen (siehe 3.4, Punkt 1).
5. **404.html:** Die alte Website hat keine 404-Seite, also gibt es keinen Originaltext. Die Überschrift „Seite nicht gefunden“ ist von mir und muss bestätigt oder ersetzt werden. Ausserdem funktionieren die relativen Pfade nur, wenn die 404-Seite im Hauptverzeichnis aufgerufen wird (bei verschachtelten Adressen wie `/a/b` fehlen CSS und Bilder).
6. **Dateigrösse:** Das Logo (`1 power, mixed media, 80x100cm.JPG`) ist 2744 × 3564 px gross (ca. 4,6 MB) und wird als kleines Bild von 72 px Breite angezeigt. Viele Galeriebilder sind 3000–5000 px breit und mehrere MB gross. Verkleinerte Fassungen wären später sinnvoll (Umbenennen/Ändern der Dateien war ausdrücklich nicht Teil dieses Schritts).
7. **Pfade:** `images\` war nicht flach – die 10 verwendeten Gemälde lagen nur in `images\Gemälde\`. Sie wurden unter gleichem Namen nach `images\` kopiert (die 6 mit „_1“ im Namen der alten Website heissen lokal ohne „_1“). Die Originale in `Gemälde\` und `AusstellungsFlyer\` sowie die nicht verwendeten Dateien sind unverändert; der Aufräumschritt bleibt offen.

---

## 4. Was #fetch nicht (direkt) lesen konnte

1. **Markdown-Modus unbrauchbar:** #fetch lieferte bei News, Photography und More Projects nur den Cookie-Hinweis. Bei allen Seiten fehlten Menü, Kontaktblock, Bilder und Links. → **Gelöst:** Die Seiten wurden als HTML-Quelltext in Abschnitten zu je 20 000 Zeichen gelesen (About 2, News 2, PAST EXHIBITIONS 4, paintings 6, Photography 3, More Projects 3 Abrufe).
2. **Photography, Link „mehr...“:** Der Link hat kein Ziel (`href="#"`) und lädt die Bilder 16–21 per JavaScript (AJAX) nach. Sie stehen nicht im Seiten-HTML (Galerie-Einstellung: `imagesCount: 21`, `imagesLeft: 6`). → **Gelöst:** Die Nachlade-Adresse wurde aus den Plattform-Skripten (`beng-proxy.js`, `show.min.js`) rekonstruiert und mit #fetch gelesen:
   `https://leharts.ch/Photography/index.php/;focus=HSTPTP_com_cm4all_wdn_PhotoGallery_8339412&frame=HSTPTP_com_cm4all_wdn_PhotoGallery_8339412&path=photos?offset=15&length=10` → 6 Bilder. Gegenprobe mit `offset=21` → leer, also vollständig.
3. **paintings, Slideshow:** Auch hier stehen nur 15 von 23 Bildern im HTML (`imagesCount: 23`, `imagesLeft: 8`), der Rest wird beim Durchblättern nachgeladen. → **Gelöst** auf dieselbe Weise (`…PhotoSlideshow_8338556&frame=…&path=photos?offset=15&length=10`) → 8 Bilder; Gegenprobe `offset=23` → leer.
4. **Logo und Kopfbilder** sind CSS-Hintergrundbilder, in der Markdown-Ansicht unsichtbar. → **Gelöst:** aus dem CSS im HTML-Quelltext gelesen.
5. **Nicht lesbar bzw. nicht geprüft:**
   - **Bildinhalte:** #fetch sieht keine Bilder. Ob ein Bildtext zum richtigen Bild gehört (z. B. „Vibes“), was Bilder ohne Text zeigen und welche alt-Texte passen, lässt sich nur durch Ansehen bzw. Nachfragen klären.
   - **Instagram-Profil** (https://www.instagram.com/leharts.ch/): liefert nur eine JavaScript-App bzw. Login-Seite, kein Inhalt lesbar.
   - **Darstellung im Browser** (Layout, Farben, Schriften, Mobilansicht, Verhalten von Slideshow und Lightbox): #fetch liest nur den Quelltext und stellt nichts dar.
   - **„Bild vergrössern“** bei `1 power, mixed media, 80x100cm.JPG` (Link `javascript:;`) und die Lightboxen: reine JavaScript-Funktionen. Zusätzlicher Text ist dort laut Konfiguration nicht zu erwarten (die Slideshow-Lightbox zeigt nur die Titel).
   - **Originaldateien** (Bytes, EXIF-Daten) wurden nicht heruntergeladen; der Abgleich beruht auf Namen und Pixelmassen (siehe Abschnitt 1).
6. **Vollständigkeit geprüft:** `https://leharts.ch/sitemap.xml` listet genau die 6 Seiten. Es gibt keine weiteren Seiten, keine PDF- oder Download-Links, keine Videos und keine eingebetteten Fremdinhalte (iframes).

---

## Offene Entscheidungen (Kurzliste)

1. Slideshow Nr. 23: Datei umbenannt zu painting-23.jpg, wird nicht verwendet (Entscheidung offen, mit der Künstlerin klären). Siehe Punkt 3.1.
2. ~~Die 6 Dateien ohne „_1“ / `/images` flach?~~ Entschieden: lokale Namen verwenden, `/images` flach, ohne Unterordner `aktuelle/` und `Gemälde/`.
3. ~~Plattform-Texte (Cookie-Hinweis)~~ Entschieden: nicht übernehmen, kein Impressum und keine Datenschutzseite in diesem Schritt (später klären, ob nötig).
4. ~~Woher kommen alt-Texte, Meta-Descriptions und Open-Graph-Texte?~~ Entschieden (neutrale alt-Texte, einheitliche Description). Offen bleiben die Punkte aus 3.8 (Punkte 1–4).
5. ~~Lokale, bisher nicht verwendete Bilder?~~ Entschieden: nicht verwenden (auch nicht die 6 Gemälde aus 2.2).
