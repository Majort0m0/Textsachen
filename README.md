# Textsachen

**Lesen, Schreiben und Tippen üben** – ein Editor für Diktate, Blitzlesen, Leseübungen, Lückentexte und Abtipp-Übungen für den Unterricht (Grundschule, Förderschule, Deutsch als Zweitsprache), z. B. für ByCS mebis/Moodle.

**▶ Direkt im Browser starten:** https://majort0m0.github.io/Textsachen/

**⬇ Herunterladen:** [Textsachen.html](https://github.com/Majort0m0/Textsachen/releases/latest/download/Textsachen.html) (eine einzige Datei, läuft offline – einfach doppelklicken)

- Mit einer Wortliste: **Bilddiktat**, **Hördiktat**, **Wortdiktat** und **Blitzlesen**
- Mit einem Text: **Lesen** (Vorlesen mit mitleuchtenden Wörtern, danach ein Bilder-Quiz), **Lückentext**, **Abtippen** und **Blitzlesen**
- Höchstens ein **Lernwort** pro Satz – automatisch vorgeschlagen oder selbst angetippt; die Lernwörter sind Lücken, Quizfragen und Blitzwörter
- Erster und zweiter Versuch wie im TippTrainer: Fehleranzeige, „Korrigieren“, Auswertung Perfekt / Geübt / Nicht geschafft
- Bilder automatisch von ARASAAC oder selbst gewählt (ARASAAC, Wikimedia Commons, eigene Bilder)
- Wörter und Texte auf Wunsch von einer KI – über einen KI-Chat deiner Wahl oder eine API-Schnittstelle
- Export als HTML-Datei (auch zum Einbetten per iframe), SCORM-1.2-Paket mit Bewertung und Wort-Protokoll oder PDF-Arbeitsblatt (Grundlinie oder 4er-Lineatur)
- Im [Lernsachen-Heft](https://majort0m0.github.io/Lernsachen-Heft/) als Vorlage „Lesen & Schreiben“ (Interaktive Übungen)
- Keine Anmeldung, kein Server, keine Cookies – siehe [Datenschutz](DATENSCHUTZ.md)

## Lizenz

Textsachen – Lizenz: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de) Lernsachen.blog ([https://lernsachen.blog](https://lernsachen.blog))

Enthaltene Bausteine: [Preact](https://preactjs.com), [Immer](https://immerjs.github.io/immer/) (MIT-Lizenz); [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) für die KI-Schnittstelle ([Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)); Schriften Nunito, Atkinson Hyperlegible, Andika, Merriweather, Caveat (SIL Open Font License 1.1). Bilder aus der Suche behalten ihre eigenen Lizenzen (ARASAAC: Sergio Palao, Regierung von Aragón, CC BY-NC-SA 4.0).

---

# Anleitung

Diese Anleitung steht auch in der App unter „Anleitung“.

## Schnellstart

Mit Textsachen erstellst du Übungen zum Lesen, Schreiben und Tippen: Diktate zu einer Wortliste, Blitzlesen, Lesen mit Vorlesefunktion, Lückentexte und Abtipp-Übungen. Alles läuft direkt in deinem Browser, ohne Anmeldung.

### In 5 Schritten zur fertigen Aufgabe

1. **Übungsart wählen** – beim Start oder über das Ordner-Symbol → „Neue Aufgabe“: eine der vier Übungen mit einer Wortliste oder eine der vier Übungen mit einem Text.
2. **Inhalt schreiben** – im Schritt „Inhalt“ den Titel und die Wörter bzw. den Text eingeben, ein Beispiel einsetzen oder mit „Mit KI erstellen …“ vorschlagen lassen.
3. **Lernwörter und Bilder** – bei Texten im Schritt „Lernwörter“ höchstens ein Wort pro Satz antippen (oder „Automatisch“), dann im Schritt „Bilder“ mit „Bilder automatisch suchen“ Piktogramme einsetzen.
4. **Ablauf einstellen** – im Schritt „Ablauf“ Schrift und Größe, Hilfen (Vorlesen, Zeigen), Vorlese-Tempo und Bestehensgrenze. Die Checkliste zeigt, ob noch etwas fehlt.
5. **Testen und exportieren** – rechts siehst du die Vorschau, oben „Testen“ zeigt die Aufgabe groß. Dann „Exportieren“: als HTML-Datei (auch zum Einbetten in mebis), als SCORM-Paket für mebis mit Bewertung oder als PDF-Arbeitsblatt.

> **Tipp:** Die Übungsart lässt sich jederzeit im Schritt „Übung“ wechseln – Wörter, Text, Lernwörter und Bilder bleiben erhalten. So wird aus demselben Text erst eine Leseübung, dann ein Lückentext und am Ende eine Abtipp-Übung.

## Die Übungsarten

### Mit einer Wortliste

| Übung | So geht sie |
| --- | --- |
| **Bilddiktat** | Ein Bild erscheint, die Lernenden schreiben das passende Wort. Nur Wörter mit Bild kommen vor. |
| **Hördiktat** | Das Wort wird vorgelesen (und lässt sich wiederholen), die Lernenden schreiben es auf. |
| **Wortdiktat** | Das Wort steht da und wird abgeschrieben – mit Bild, wenn eines gewählt ist. |
| **Blitzlesen** | Nach drei Sternchen blitzt das Wort kurz auf. Dann tippen die Lernenden unter drei Bildern das passende an. „Nochmal blitzen“ zeigt es noch einmal, „Wörter zeigen“ schreibt die Wörter unter die Bilder. Braucht mindestens 3 Wörter mit Bild. |

### Mit einem Text

| Übung | So geht sie |
| --- | --- |
| **Lesen** | Der Text wird Satz für Satz vorgelesen, das gelesene Wort leuchtet mit. Antippen eines Worts liest seinen Satz vor, „Bilder“ zeigt die Wortbilder über dem Text. Danach (einschaltbar) ein **Bilder-Quiz**: Zu jedem Bild eines Lernworts wird das Wort im Text angetippt. |
| **Lückentext** | Die Lernwörter fehlen im Text und werden in die Lücken geschrieben. |
| **Abtippen** | Der Text wird Wort für Wort abgetippt – Leertaste, Eingabetaste oder ein Satzzeichen bestätigen ein Wort. Mit „Vorlage anzeigen“ steht der Text darüber, sonst helfen nur Vorlesen und Zeigen (wie im TippTrainer). Am Ende stehen auch die Wörter pro Minute. |
| **Blitzlesen** | Wie bei der Wortliste – mit den Lernwörtern des Textes, die ein Bild haben. |

### Erster und zweiter Versuch

Beim Schreiben zeigt ein Fehler, was nicht stimmt: falsche Buchstaben rot durchgestrichen, fehlende grün. Mit „Korrigieren“ gibt es genau einen zweiten Versuch. Am Ende zählt jedes Wort als **Perfekt** (gleich richtig), **Geübt** (im zweiten Versuch richtig) oder **Nicht geschafft**. Ein Hinweis erscheint, wenn nur die Groß- und Kleinschreibung falsch ist oder die Feststelltaste an ist.

## Inhalt & KI

**Wortliste:** Ein Wort pro Zeile (oder durch Kommas getrennt). Artikel dürfen dazu: „der Hund“ wird mit Artikel geschrieben, das Bild wird aber nach „Hund“ gesucht. Mit „GROSSBUCHSTABEN“ schreibst du alles in Großbuchstaben – für Schreibanfänger.

**Text:** Schreibe oder füge den Text ein. Eine leere Zeile beginnt einen neuen Absatz. Sätze enden an Punkt, Ausrufe- und Fragezeichen – danach richten sich das Vorlesen, die Lernwörter und das Arbeitsblatt.

**Mit KI erstellen:** „Mit KI erstellen …“ öffnet denselben Dialog wie in den anderen Lernsachen-Apps: Thema, Klassenstufe bzw. Zielgruppe (auch Deutsch als Zweitsprache und Leichte Sprache), Länge, Textsorte, Rechtschreib-Schwerpunkt und eigene Wünsche. Bei Texten markiert die KI gleich ein Lernwort pro Satz.

- **Über einen KI-Chat:** Den Prompt kopieren, in einen KI-Chat deiner Wahl einfügen, die Antwort kopieren und bei „Antwort einfügen“ einsetzen. Textsachen selbst schickt dabei nichts ins Internet.
- **Über eine API-Schnittstelle:** Mit eigenem Schlüssel (Anthropic, OpenAI, Mistral, Gemini, OpenRouter) oder einer lokalen KI (Ollama) erzeugt Textsachen die Aufgabe direkt. Den Schlüssel speichert der Browser nur, wenn du das einschaltest.

> **Achtung:** Prüfe Texte einer KI immer selbst – auf Rechtschreibung, Inhalt und ob sie zu deiner Klasse passen.

## Lernwörter

Bei Texten bestimmen die **Lernwörter**, was geübt wird: Sie sind die Lücken im Lückentext, die Fragen im Bilder-Quiz beim Lesen und die Wörter beim Blitzlesen. Pro Satz gibt es **höchstens ein Lernwort** – so bleibt das Quiz kurz und jeder Satz kommt dran.

- Tippe im Schritt „Lernwörter“ ein Wort an: Es wird das Lernwort seines Satzes. Nochmal antippen entfernt es.
- „Automatisch“ schlägt in jedem Satz eines vor – bevorzugt Nomen und Wörter, die schon ein Bild haben. „Keine“ entfernt alle.
- Änderst du den Text, bleiben die Lernwörter erhalten, solange die Wörter noch da sind.

> **Tipp:** Für Bilder-Quiz und Blitzlesen braucht ein Lernwort ein Bild – das wählst du im nächsten Schritt.

## Bilder

Im Schritt „Bilder“ steht jedes Wort der Liste bzw. jedes Lernwort des Textes mit seinem Bild.

- „Bilder automatisch suchen“ setzt für alle Wörter ohne Bild das erste passende Piktogramm von ARASAAC ein (bei Texten auch mit der Grundform, z. B. „Häuser“ → „Haus“).
- Über die Lupe bzw. „Anderes Bild wählen“ suchst du selbst bei ARASAAC oder Wikimedia Commons, lädst ein eigenes Bild hoch oder fügst eine Bildadresse ein. Bildnachweise erscheinen automatisch in der Aufgabe und auf dem Arbeitsblatt.
- Bilder von Textwörtern gelten für jedes Vorkommen des Worts im Text.

ARASAAC-Piktogramme: Sergio Palao, Regierung von Aragón, Lizenz CC BY-NC-SA 4.0 – frei für den nicht-kommerziellen Unterricht.

## Ablauf & Hilfen

- **Schrift und Größe** der Übung – Andika mit einstöckigem a für Leseanfänger, Atkinson Hyperlegible besonders gut unterscheidbar.
- **Hilfen:** „Vorlesen“ (Lautsprecher) und „Zeigen“ (Auge, das Wort erscheint kurz). Die Abschlusskarte zählt mit, wie oft Hilfen benutzt wurden.
- **Reihenfolge mischen** (Wortlisten), **Vorlese-Tempo** mit „Probehören“ und die **Bestehensgrenze** für SCORM.
- Im Schritt „Übung“ stehen die Einstellungen der Übungsart, z. B. die Anzeigedauer beim Blitzlesen (auf Wunsch automatisch angepasst: nach Fehlern länger, nach schnellen richtigen Antworten kürzer), das Bilder-Quiz beim Lesen oder „Vorlage anzeigen“ beim Abtippen.

Vorgelesen wird mit der deutschen Stimme des Geräts – auf iPads und Computern klingt sie unterschiedlich.

## Testen

Die **Vorschau** neben den Einstellungen zeigt die Aufgabe so, wie sie die Lernenden sehen, und startet nach jeder Änderung neu. „Testen“ oben zeigt sie groß; „Neu starten“ beginnt von vorn.

## Exportieren

Klicke oben rechts auf „Exportieren“. Hast du noch Hinweise in der Checkliste, zeigt der Dialog sie an – exportieren kannst du trotzdem.

**Projektdatei (JSON):** Die Arbeitsdatei zum **Weiterbearbeiten** in Textsachen – mit allen Bildern (auch denen der anderen Inhaltsart, falls du zwischen Wortliste und Text gewechselt hast). Für Lernende ist sie nicht gedacht.

**HTML-Datei:** Eine einzelne Datei, die in jedem Browser läuft – auch ohne Internet. Zum Verschicken, für den Schulserver oder in mebis als Material „Datei“. Ergebnisse werden dabei nicht gespeichert. Eine exportierte HTML-Datei kannst du über „Öffnen …“ auch wieder in Textsachen laden.

### HTML-Datei in mebis/Moodle einbetten (iframe)

1. Bei „HTML-Datei (eigenständig)“ auf „Herunterladen“ klicken – der Dialog wechselt zu „In mebis/Moodle einbetten“.
2. Die Datei in mebis hochladen, z. B. als Material „Datei“ mit der Anzeige „Eingebettet“ (dann bist du fertig) oder im Texteditor eines Textfelds über „Link“ bzw. „Medien“ → „Datei hochladen“.
3. Mit der rechten Maustaste auf den Dateinamen → „Link-Adresse kopieren“ und den Link in das Feld „Link der HTML-Datei“ einfügen. Den fertigen „iframe-Code“ kopieren.
4. Im Texteditor auf die HTML-Ansicht umschalten, den Code einfügen und speichern.

### SCORM-Paket (mebis als „Lernpaket“)

1. Das SCORM-Paket (ZIP-Datei) herunterladen – nicht entpacken.
2. In mebis „Bearbeiten“ einschalten → „Aktivität oder Material anlegen“ → „Lernpaket (SCORM)“, die ZIP-Datei in „Paketdatei“ ziehen und speichern.

Punkte gibt es für jedes Wort, das im ersten oder zweiten Versuch richtig war; ab der Bestehensgrenze gilt die Aufgabe als bestanden. Jedes Wort erscheint mit den Eingaben in den Interaktionen. Eine angefangene Aufgabe geht beim nächsten Öffnen an derselben Stelle weiter.

### PDF-Arbeitsblatt

Ein A4-Arbeitsblatt zum Ausdrucken, aufgebaut wie im TippTrainer. Du wählst „Grundlinie“ oder „Lineatur (4 Linien)“ für Schreibanfänger und ob oben Linien für Name und Datum stehen.

- **Bild-, Hör- und Wortdiktat:** zwei Spalten mit Bild (oder Nummer) und Schreiblinie; nach höchstens sechs Wörtern ein Kasten mit den Lösungswörtern in zufälliger Reihenfolge. Artikel stehen schon vor der Linie.
- **Blitzlesen:** zu jedem Wort drei Bilder – das passende wird eingekreist.
- **Lesen:** der Text, auf Wunsch mit den Wortbildern über den Wörtern. Ohne Wortbilder folgt eine Suchaufgabe „Kannst du diese Wörter im Text finden?“ mit bis zu sechs Bildern.
- **Lückentext:** Schreiblinien statt der Lernwörter, nach höchstens sechs Sätzen ein Kasten mit den Lösungswörtern.
- **Abtippen:** der Text in Abschnitten von sechs Sätzen, nach jedem genug Linien zum Abschreiben.

## Speichern & Weiterbearbeiten

**Automatisch im Browser:** Jede Änderung wird nach kurzer Zeit automatisch in deinem Browser gespeichert (oben steht „Automatisch gespeichert“). Öffnest du Textsachen später im selben Browser wieder, ist deine Aufgabe noch da.

> **Achtung:** Der Browser-Speicher ist kein Archiv: Er gilt nur für diesen Browser auf diesem Gerät und geht verloren, wenn du die Browserdaten löschst oder im privaten Modus arbeitest. Es gibt immer nur **eine** aktuelle Aufgabe – sichere sie als JSON-Datei.

**Öffnen und neue Aufgabe:** Ordner-Symbol → „Öffnen …“ lädt eine JSON-Datei oder eine exportierte HTML-Aufgabe wieder in den Editor, „Neue Aufgabe“ beginnt mit einer neuen Übungsart. Die aktuelle Aufgabe wird dabei ersetzt.

**Im Lernsachen-Heft:** Im Lernsachen-Heft öffnet die Vorlage unter „Interaktive Übungen“ Textsachen direkt im Heft. Oben rechts stehen dann „Ins Heft übernehmen“ und „Abbrechen“. Bis die Aufgabe im Heft ist, speichert Textsachen sie als eigenen Entwurf.

**Rückgängig und Wiederholen:** Mit den Pfeilen oben oder Strg+Z machst du Schritte rückgängig, mit Strg+Umschalt+Z oder Strg+Y stellst du sie wieder her.

## Tipps & häufige Fragen

- **Das Bilddiktat oder Blitzlesen zeigt nicht alle Wörter.** Diese Übungen brauchen Bilder: Wörter ohne Bild werden übersprungen. Ergänze die Bilder im Schritt „Bilder“.
- **Im Lückentext oder Quiz kommen zu wenige Wörter dran.** Es gibt höchstens ein Lernwort pro Satz. Wähle im Schritt „Lernwörter“ mehr Wörter aus – oder teile lange Sätze im Text.
- **Die Vorlese-Stimme klingt seltsam oder fehlt.** Textsachen nutzt die Stimme des Geräts. Fehlt eine deutsche Stimme, kann sie in den Systemeinstellungen (Bedienungshilfen → Gesprochene Inhalte) nachgeladen werden.
- **Darf ich Aufgaben weitergeben?** Ja. Die Aufgaben gehören dir. Für die Bilder gelten deren Lizenzen – ARASAAC-Piktogramme nur nicht-kommerziell; die Bildnachweise stehen automatisch dabei.
