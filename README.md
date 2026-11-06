# Textsachen

**Lesen, Schreiben und Tippen üben** – ein Editor für Diktate, Blitzlesen, Wortspiele und Rätsel (Memory, Maus & Käse, Kreuzworträtsel, Suchsel, Wordle), Leseübungen, Lückentexte und Abtipp-Übungen für den Unterricht (Grundschule, Förderschule, Deutsch als Zweitsprache), z. B. für ByCS mebis/Moodle.

**▶ Direkt im Browser starten:** https://majort0m0.github.io/Textsachen/

**⬇ Herunterladen:** [Textsachen.html](https://github.com/Majort0m0/Textsachen/releases/latest/download/Textsachen.html) (eine einzige Datei, läuft offline – einfach doppelklicken)

- Mit einer Wortliste: **Bilddiktat**, **Hördiktat**, **Wortdiktat** und **Blitzlesen**
- Spiele und Rätsel mit einer Wortliste: **Memory**, **Maus & Käse** (Buchstaben raten), **Kreuzworträtsel**, **Suchsel** und **Wordle**
- Mit einem Text: **Lesen** (Vorlesen mit mitleuchtenden Wörtern, danach ein Bilder-Quiz), **Lückentext**, **Abtippen** und **Blitzlesen**
- Höchstens ein **Lernwort** pro Satz – automatisch vorgeschlagen oder selbst angetippt; die Lernwörter sind Lücken, Quizfragen und Blitzwörter
- Wie im TippTrainer: Prüfen mit der Eingabetaste, Fehleranzeige im Eingabefeld, Korrigieren mit der Rücktaste, Shift-Animation bei Groß-/Kleinschreibung, Artikel steht schon da; Auswertung Perfekt / Geübt / Nicht geschafft
- Bilder automatisch gleich nach der Eingabe – ARASAAC-Piktogramme über die Grundform der Wörter (Häuser → Haus, läuft → laufen); bei Texten viele **Bildwörter** zum Leseverständnis, mit Archiv zum Ab- und Zuwählen; oder selbst gewählt (ARASAAC, Wikimedia Commons, eigene Bilder)
- Wörter und Texte auf Wunsch von einer KI – über einen KI-Chat deiner Wahl oder eine API-Schnittstelle
- Export als HTML-Datei (auch zum Einbetten per iframe), SCORM-1.2-Paket mit Bewertung und Wort-Protokoll oder PDF-Arbeitsblatt (Grundlinie oder 4er-Lineatur)
- Im [Lernsachen-Heft](https://majort0m0.github.io/Lernsachen-Heft/) als Vorlage „Lesen & Schreiben“ (Interaktive Übungen)
- Keine Anmeldung, kein Server, keine Cookies – siehe [Datenschutz](DATENSCHUTZ.md)

## Lizenz

Textsachen – Lizenz: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de) Lernsachen.blog ([https://lernsachen.blog](https://lernsachen.blog))

Du darfst Textsachen kopieren, weitergeben und verändern – auch in deiner Schule und im Kollegium –, solange du Lernsachen.blog als Urheber nennst, auf die Lizenz verweist, es nicht kommerziell nutzt und Veränderungen unter derselben Lizenz weitergibst. Die Aufgaben, die du damit erstellst, gehören dir; für darin verwendete Bilder gelten deren eigene Lizenzen.

Enthaltene Bausteine: [Preact](https://preactjs.com), [Immer](https://immerjs.github.io/immer/) (MIT-Lizenz); [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) für die KI-Schnittstelle ([Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)); Schriften Lexend, Nunito, Atkinson Hyperlegible, Andika, Merriweather, Caveat (SIL Open Font License 1.1). Bilder aus der Suche behalten ihre eigenen Lizenzen (ARASAAC: Sergio Palao, Regierung von Aragón, CC BY-NC-SA 4.0). Silbentrennung (Silben rot und blau): [Hypher](https://github.com/bramstein/hypher) (© 2011 Bram Stein, BSD-3-Clause) mit den deutschen TeX-Trennmustern dehyphn-x-2011-06-01 (© 2007–2011 Werner Lemberg, [LaTeX Project Public License 1.3c](https://www.latex-project.org/lppl/)), von Bram Stein ins Hypher-Format umgewandelt (npm-Paket hyphenation.de 0.2.1); die Silbenregeln für Sprechsilben kommen danach dazu. Die Autoren der Trennmuster sind für diese App nicht verantwortlich. Unverändertes Original: [tex-hyphen](https://github.com/hyphenation/tex-hyphen) (hyph-de-1996.tex, Stand 2011-06-01) bzw. CTAN (hyph-utf8).

<details><summary>Lizenztext von Hypher (BSD-3-Clause)</summary>

```
Copyright (c) 2011, Bram Stein
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

 1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.
 3. The name of the author may not be used to endorse or promote products
    derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR "AS IS" AND ANY EXPRESS OR IMPLIED
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT,
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY
OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

</details>

---

# Anleitung

Diese Anleitung steht auch in der App unter „Anleitung“.

## Schnellstart

Mit Textsachen erstellst du Übungen zum Lesen, Schreiben und Tippen: Diktate zu einer Wortliste, Blitzlesen, Wortspiele und Rätsel (Memory, Maus & Käse, Kreuzworträtsel, Suchsel, Wordle), Lesen mit Vorlesefunktion, Lückentexte und Abtipp-Übungen. Alles läuft direkt in deinem Browser, ohne Anmeldung.

### In 5 Schritten zur fertigen Aufgabe

1. **Übungsart wählen** – beim Start oder über das Ordner-Symbol → „Neue Aufgabe“: eine der vier Übungen mit einer Wortliste oder eine der vier Übungen mit einem Text.
2. **Inhalt schreiben** – im Schritt „Inhalt“ den Titel und die Wörter bzw. den Text eingeben, ein Beispiel einsetzen, mit „Aus Wortliste …“ aus den Listen von Lernsachen-Heft wählen (Erste Wörter, Grundwortschatz Bayern 1/2, Deutsch als Zweitsprache – jedes Wort mit seinem geprüften Piktogramm) oder mit „Mit KI erstellen …“ vorschlagen lassen.
3. **Bilder und Lernwörter** – die Bilder sucht Textsachen gleich nach der Eingabe von selbst; im Schritt „Bilder“ tauschst du sie aus oder legst Wörter ins Archiv. Bei Texten wählst du im Schritt „Lernwörter“ höchstens ein Wort pro Satz (oder „Automatisch“).
4. **Ablauf einstellen** – im Schritt „Ablauf“ Schrift und Größe, Hilfen (Vorlesen, Zeigen), Vorlese-Tempo und Bestehensgrenze. Die Checkliste zeigt, ob noch etwas fehlt.
5. **Testen und speichern** – rechts siehst du die Vorschau, oben „Testen“ zeigt die Aufgabe groß. Dann „Speichern“: als HTML-Datei (auch zum Einbetten in mebis), als SCORM-Paket für mebis mit Bewertung oder als PDF-Arbeitsblatt.

> **Tipp:** Die Übungsart lässt sich jederzeit im Schritt „Übung“ wechseln – Wörter, Text, Lernwörter und Bilder bleiben erhalten. So wird aus demselben Text erst eine Leseübung, dann ein Lückentext und am Ende eine Abtipp-Übung.

## Die Übungsarten

### Mit einer Wortliste

| Übung | So geht sie |
| --- | --- |
| **Bilddiktat** | Links das Bild, rechts das Eingabefeld – der Artikel steht schon im grauen Kästchen davor. Nur Wörter mit Bild kommen vor. |
| **Hördiktat** | Statt des Bildes ein Ohr: Das Wort wird vorgelesen (Ohr oder Lautsprecher = nochmal hören). Das Bild erscheint erst nach der Antwort. |
| **Wortdiktat** | Das Wort steht groß über dem Eingabefeld und wird vorgelesen, dann abgeschrieben – mit Bild, wenn eines gewählt ist. |
| **Blitzlesen** | Nach drei Sternchen blitzt das Wort kurz auf. Dann tippen die Lernenden unter drei Bildern das passende an. „Nochmal blitzen“ zeigt es noch einmal, „Wörter zeigen“ schreibt die Wörter unter die Bilder. Braucht mindestens 3 Wörter mit Bild. Mit automatischer Anzeigedauer (Standard) kommen vorher 5 einfache **Aufwärmwörter** (zufällig aus 20, z. B. Hund, Apfel, Haus): Aus der Reaktionszeit ergibt sich die Anzeigedauer; Punkte gibt es erst danach für die eigenen Wörter. |

### Mit einem Text

| Übung | So geht sie |
| --- | --- |
| **Lesen** | Der Text wird Satz für Satz vorgelesen, das gelesene Wort leuchtet mit. Antippen eines Worts liest seinen Satz vor, „Bilder“ zeigt die Wortbilder über dem Text. Danach (einschaltbar) ein **Bilder-Quiz**: Zu jedem Bild eines Lernworts wird das Wort im Text angetippt. Auf Wunsch stehen die Wörter in **Silben rot und blau** (Silbenmethode); die Lernenden schalten die Farben mit „Silben“ aus und ein. |
| **Lückentext** | Die Lernwörter fehlen im Text (blaue Kästchen). Antippen öffnet eine Lücke – in beliebiger Reihenfolge – mit Eingabefeld und den Hilfen direkt daneben: Lautsprecher (liest das Wort), Auge (zeigt es kurz im Feld), ✕ (schließen, Esc) und ✓ (prüfen, Enter). Ein Fehler erscheint rot an der Stelle der Lücke, der Stift (oder Antippen) startet den zweiten Versuch. Unten: „Vorlesen“ liest den ganzen Text (Lücken heißen „Wortlücke“), „Bilder“ zeigt die Bildwörter – auch über den Lücken. |
| **Abtippen** | Der Text wird Wort für Wort abgetippt – Leertaste, Eingabetaste oder ein Satzzeichen bestätigen ein Wort. Mit „Vorlage anzeigen“ steht der Text darüber, sonst helfen nur Vorlesen und Zeigen (wie im TippTrainer). Ein Fehler wird mit der Rücktaste (oder Antippen) korrigiert. Am Ende stehen auch die Wörter pro Minute. |
| **Blitzlesen** | Wie bei der Wortliste – mit den Lernwörtern des Textes, die ein Bild haben. |

### Spiele und Rätsel mit einer Wortliste

| Übung | So geht sie |
| --- | --- |
| **Memory** | Zu jedem Wort mit Bild ein Kartenpaar: Bild und Bild, Bild und Wort oder Bild und Ton (die Computerstimme spricht das Wort beim Aufdecken). Zwei Karten werden aufgedeckt; ein Paar bleibt offen und das Wort wird vorgelesen. Allein zählen die Züge, zu zweit wird abgewechselt – wer ein Paar findet, ist noch einmal dran. Gibt es mehr Wörter als Paare pro Spiel, kommt jedes Mal eine andere Auswahl. Für die Rückseite der Karten gibt es ein Muster (Punkte, Streifen, Karo, Wellen, Sterne oder einfarbig) und sechs ruhige Farben. |
| **Maus & Käse** | Statt Galgenmännchen: Das Wort steht als leere Kästchen da (der Artikel ist schon da), Buchstaben werden auf der Bildschirmtastatur oder der Tastatur geraten. Jeder falsche Buchstabe bringt die Maus einen Schritt näher zum Käse – kommt sie an, frisst sie ihn und das Wort wird gezeigt. Am Ende jedes Wortes – geschafft oder nicht – erscheint sein Bild; auf Wunsch steht es schon vorher als Hilfe da. Einstellbar sind auch die Schritte bis zum Käse. |
| **Kreuzworträtsel** | Die Bilder sind die Fragen (nummeriert, waagerecht und senkrecht), die Wörter werden ins Gitter getippt – der Cursor läuft weiter, ein zweites Antippen einer Kreuzung wechselt die Richtung. „Prüfen“ (Eingabetaste) prüft jedes fertige Wort mit zwei Versuchen. Mit der Einstellung „Stift“ bleiben die Kästchen leer: zum Schreiben mit dem Stift in Lernsachen-Heft oder auf dem Arbeitsblatt, „Lösung zeigen“ zeigt die Wörter. Großbuchstaben, ß wird SS. |
| **Suchsel** | Die Wörter verstecken sich in einem Buchstabengitter (→ ↓, auch schräg oder in alle Richtungen); die Bilder zeigen, was gesucht wird. Gefunden wird durch Wischen über die Buchstaben oder Antippen des ersten und letzten Buchstabens – das Wort bekommt ein farbiges Band und wird vorgelesen. „Wörter zeigen“ schreibt die Wörter kurz unter die Bilder. Mit „Stift“ wird nichts geprüft, „Lösung zeigen“ zeigt die Bänder. |
| **Wordle** | Ein Wort mit 4, 5 oder 6 Buchstaben in 6 Versuchen erraten: Grün = richtiger Buchstabe an der richtigen Stelle, Gelb (gestrichelt) = im Wort, aber woanders, Grau = nicht im Wort; auch die Tastatur färbt sich. Gespielt werden die Wörter der Liste mit der gewählten Länge – ohne solche eine eingebaute Liste einfacher Wörter. Hilfen: Bild zeigen, Vorlesen. |

### Erster und zweiter Versuch (wie im TippTrainer)

- Geprüft wird mit der **Eingabetaste** – auf der Tastatur oder mit dem Knopf, der wie die Eingabetaste aussieht.
- Bei einem Fehler steht im Eingabefeld, was nicht stimmt: falsche Buchstaben rot durchgestrichen, die richtigen grün daneben. Bei Groß- und Kleinschreibung zeigt eine kleine Animation, wie man mit der Umschalttaste den Großbuchstaben tippt; stehen fast nur Großbuchstaben da, erinnert die **Feststelltaste** daran, sie auszuschalten.
- Die **Rücktaste** (oder der rote Knopf, oder die Eingabetaste) startet den zweiten Versuch mit leerem Feld; wer auf die Fehleranzeige tippt, verbessert das Geschriebene. Im zweiten Versuch steht das richtige Wort darüber.
- Das **Auge** zeigt das Wort kurz in derselben Größe genau über dem Eingabefeld, der Lautsprecher liest es vor.

Am Ende zählt jedes Wort als **Perfekt** (gleich richtig), **Geübt** (im zweiten Versuch richtig) oder **Nicht geschafft**. Lückentext und Abtippen zeigen Fehler genauso an.

## Inhalt & KI

**Wortliste:** Ein Wort pro Zeile (oder durch Kommas getrennt). Artikel dürfen dazu: „der Hund“ wird mit Artikel geschrieben, das Bild wird aber nach „Hund“ gesucht. Mit „GROSSBUCHSTABEN“ schreibst du alles in Großbuchstaben – für Schreibanfänger.

**Text:** Schreibe oder füge den Text ein. Eine leere Zeile beginnt einen neuen Absatz. Sätze enden an Punkt, Ausrufe- und Fragezeichen – danach richten sich das Vorlesen, die Lernwörter und das Arbeitsblatt.

**Mit KI erstellen:** „Mit KI erstellen …“ öffnet denselben Dialog wie in den anderen Lernsachen-Apps: Thema, Klassenstufe bzw. Zielgruppe (auch Deutsch als Zweitsprache und Leichte Sprache), Länge, Textsorte, Rechtschreib-Schwerpunkt und eigene Wünsche. Bei Texten markiert die KI gleich ein Lernwort pro Satz und nennt die Bildwörter mit ihrer Grundform (z. B. „Würmer = Wurm“) – damit findet die Bildersuche bessere Piktogramme.

- **Über einen KI-Chat:** Den Prompt kopieren, in einen KI-Chat deiner Wahl einfügen, die Antwort kopieren und bei „Antwort einfügen“ einsetzen. Textsachen selbst schickt dabei nichts ins Internet.
- **Über eine API-Schnittstelle:** Mit eigenem Schlüssel (Anthropic, OpenAI, Mistral, Gemini, OpenRouter) oder einer lokalen KI (Ollama) erzeugt Textsachen die Aufgabe direkt. Den Schlüssel speichert der Browser nur, wenn du das einschaltest.

> **Achtung:** Prüfe Texte einer KI immer selbst – auf Rechtschreibung, Inhalt und ob sie zu deiner Klasse passen.

## Lernwörter

Bei Texten bestimmen die **Lernwörter**, was geübt wird: Sie sind die Lücken im Lückentext, die Fragen im Bilder-Quiz beim Lesen und die Wörter beim Blitzlesen. Pro Satz gibt es **höchstens ein Lernwort** – so bleibt das Quiz kurz und jeder Satz kommt dran.

- Tippe im Schritt „Lernwörter“ ein Wort an: Es wird das Lernwort seines Satzes. Nochmal antippen entfernt es.
- „Automatisch“ schlägt in jedem Satz eines vor – bevorzugt Nomen und Wörter, die schon ein Bild haben. „Keine“ entfernt alle.
- Änderst du den Text, bleiben die Lernwörter erhalten, solange die Wörter noch da sind.

> **Tipp:** Lernwörter und Bildwörter sind zweierlei: **Bildwörter** sind alle Wörter mit Bild (viele pro Satz, zum Verstehen beim Lesen), **Lernwörter** werden geübt. Für Bilder-Quiz und Blitzlesen braucht ein Lernwort ein Bild.

## Bilder & Bildwörter

### Automatische Bildersuche

Sobald du Wörter oder einen Text eingibst, sucht Textsachen von selbst passende Piktogramme bei ARASAAC – wie im TippTrainer über die **Grundform**: Einzahl, Infinitiv, nicht gesteigert („Häuser“ → „Haus“, „läuft“ → „laufen“, „größten“ → „groß“, „Apfelbaum“ → „Baum“). Bei Texten zählen nur sichere Treffer; Wörter, die sich nicht abbilden lassen (der, und, ist, sehr …, abstrakte Wörter wie „Freiheit“), werden gar nicht gesucht. Jedes Wort wird nur einmal gesucht – was du entfernst, kommt nicht von selbst zurück. Unter „Bilder automatisch suchen“ schaltest du die Suche aus.

### Wortlisten

Jedes Wort steht mit seinem Bild da; „gesucht:“ zeigt die Grundform, unter der es gefunden wurde. Mit der Lupe wählst du selbst (ARASAAC, Wikimedia Commons, eigenes Bild oder Bildadresse), der Papierkorb entfernt das Bild. „Fehlende suchen“ versucht es für Wörter ohne Bild noch einmal.

### Texte: Bildwörter und Archiv

- **Bildwörter** sind alle Wörter des Textes mit Bild – beim Lesen stehen die Bilder über den Wörtern (Knopf „Bilder“). Die Lernwörter unter ihnen sind mit einem Stern markiert; sie kommen im Bilder-Quiz und beim Blitzlesen dran.
- Das Archiv-Symbol legt ein Bildwort ins **Archiv**: Es bekommt kein Bild mehr, das Bild bleibt aber gespeichert und kommt mit ⊕ zurück.
- Im Archiv stehen auch die Wörter ohne Bild. Mit der Lupe bekommt ein Wort ein Bild und wird zum Bildwort; „Nochmal suchen“ sucht für alle Wörter ohne Bild noch einmal.
- Ein Bild gilt für jedes Vorkommen des Worts im Text.

ARASAAC-Piktogramme: Sergio Palao, Regierung von Aragón, Lizenz CC BY-NC-SA 4.0 – frei für den nicht-kommerziellen Unterricht. Die Bildnachweise erscheinen automatisch in der Aufgabe und auf dem Arbeitsblatt.

## Ablauf & Hilfen

- **Schrift und Größe** der Übung – Lexend (Standard) ist besonders leicht lesbar, Andika hat ein einstöckiges a für Leseanfänger, Atkinson Hyperlegible besonders gut unterscheidbare Buchstaben. Beim Lesen, im Lückentext und beim Abtippen stellen die Lernenden die Schrift mit „A−“ und „A+“ unten rechts selbst kleiner oder größer (bis 200 %).
- **Hilfen:** „Vorlesen“ (Lautsprecher) und „Zeigen“ (Auge, das Wort erscheint kurz). Die Abschlusskarte zählt mit, wie oft Hilfen benutzt wurden. „Aufgabenstellung vorlesen“ setzt einen Lautsprecher an die Aufgabe (z. B. „Welches Wort passt zum Bild?“).
- **Reihenfolge mischen** (Wortlisten), **Vorlese-Tempo** mit „Probehören“ und die **Bestehensgrenze** für SCORM.
- Im Schritt „Übung“ stehen die Einstellungen der Übungsart, z. B. die Anzeigedauer beim Blitzlesen (Standard: automatisch – erst mit 5 Aufwärmwörtern eingestellt, dann nach Fehlern und Hilfen länger, nach schnellen richtigen Antworten kürzer; sonst fest), das Bilder-Quiz beim Lesen oder „Vorlage anzeigen“ beim Abtippen.

Vorgelesen wird mit der deutschen Stimme des Geräts – auf iPads und Computern klingt sie unterschiedlich.

## Testen

Die **Vorschau** neben den Einstellungen zeigt die Aufgabe so, wie sie die Lernenden sehen, und startet nach jeder Änderung neu. „Testen“ oben zeigt sie groß; „Neu starten“ beginnt von vorn.

## Speichern und teilen

Klicke oben rechts auf „Speichern“. Hast du noch Hinweise in der Checkliste, zeigt der Dialog sie an – speichern kannst du trotzdem.

**HTML-Datei:** Eine einzelne Datei, die in jedem Browser läuft – auch ohne Internet. Zum Verschicken, für den Schulserver oder in mebis als Material „Datei“. Ergebnisse werden dabei nicht gespeichert. Dieselbe Datei ist auch deine Arbeitsdatei: Über „Öffnen …“ lädst du sie wieder in Textsachen und bearbeitest sie weiter – mit allen Bildern (auch denen der anderen Inhaltsart, falls du zwischen Wortliste und Text gewechselt hast).

### HTML-Datei in mebis/Moodle einbetten (iframe)

1. Bei „HTML-Datei (speichern und weitergeben)“ auf „Herunterladen“ klicken – der Dialog wechselt zu „In mebis/Moodle einbetten“.
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
- **Memory:** Karten zum Ausschneiden – zu jedem Wort ein Paar.
- **Maus & Käse, Wordle:** Bild (oder Nummer) und ein Kästchen pro Buchstabe, dazu Kästen mit den Lösungswörtern.
- **Kreuzworträtsel und Suchsel:** das Rätsel (genau wie in der Übung) mit den Bildern als Fragen, dazu eine Lösungsseite.
- **Lesen:** der Text, auf Wunsch mit den Wortbildern über den Wörtern. Ohne Wortbilder folgt eine Suchaufgabe „Kannst du diese Wörter im Text finden?“ mit bis zu sechs Bildern.
- **Lückentext:** Schreiblinien statt der Lernwörter, nach höchstens sechs Sätzen ein Kasten mit den Lösungswörtern.
- **Abtippen:** der Text in Abschnitten von sechs Sätzen, nach jedem genug Linien zum Abschreiben.

## Speichern & Weiterbearbeiten

**Automatisch im Browser:** Jede Änderung wird nach kurzer Zeit automatisch in deinem Browser gespeichert (oben steht „Automatisch gespeichert“). Öffnest du Textsachen später im selben Browser wieder, ist deine Aufgabe noch da.

> **Achtung:** Der Browser-Speicher ist kein Archiv: Er gilt nur für diesen Browser auf diesem Gerät und geht verloren, wenn du die Browserdaten löschst oder im privaten Modus arbeitest. Es gibt immer nur **eine** aktuelle Aufgabe – sichere sie als Datei.

**Als Datei sichern:** Ordner-Symbol → „Als HTML-Datei speichern“ lädt die Aufgabe als HTML-Datei herunter, z. B. „Tiere im Zoo (Textsachen).html“. Sie läuft in jedem Browser, lässt sich in Lernsachen-Heft einfügen und in Textsachen wieder öffnen. Am Namen erkennst du, aus welcher App eine Datei stammt: „(Textsachen)“, „(Quizsachen)“, „(Schiebesachen)“ oder „(Heft)“ für Lernsachen-Heft.

**Öffnen und neue Aufgabe:** Ordner-Symbol → „Öffnen …“ lädt eine gespeicherte oder exportierte HTML-Aufgabe wieder in den Editor (auch ältere JSON-Dateien), „Neue Aufgabe“ beginnt mit einer neuen Übungsart. Die aktuelle Aufgabe wird dabei ersetzt. Öffnest du die Datei einer anderen App, sagt dir Textsachen, wohin sie gehört.

**Im Lernsachen-Heft:** Im Lernsachen-Heft öffnet die Vorlage unter „Interaktive Übungen“ Textsachen direkt im Heft. Oben rechts stehen dann „Ins Heft übernehmen“ und „Abbrechen“. Bis die Aufgabe im Heft ist, speichert Textsachen sie als eigenen Entwurf.

**Rückgängig und Wiederholen:** Mit den Pfeilen oben oder Strg+Z machst du Schritte rückgängig, mit Strg+Umschalt+Z oder Strg+Y stellst du sie wieder her.

## Tipps & häufige Fragen

- **Das Bilddiktat oder Blitzlesen zeigt nicht alle Wörter.** Diese Übungen brauchen Bilder: Wörter ohne Bild werden übersprungen. Ergänze die Bilder im Schritt „Bilder“ mit der Lupe oder „Fehlende suchen“.
- **Ein Bild passt nicht zum Wort.** Tausche es mit der Lupe aus (dort kannst du auch ein anderes Suchwort eingeben). Bei Texten kannst du das Wort auch ins Archiv legen – dann bekommt es kein Bild.
- **Im Lückentext oder Quiz kommen zu wenige Wörter dran.** Es gibt höchstens ein Lernwort pro Satz. Wähle im Schritt „Lernwörter“ mehr Wörter aus – oder teile lange Sätze im Text.
- **Die Vorlese-Stimme klingt seltsam oder fehlt.** Textsachen nutzt die Stimme des Geräts. Fehlt eine deutsche Stimme, kann sie in den Systemeinstellungen (Bedienungshilfen → Gesprochene Inhalte) nachgeladen werden.
- **Darf ich Aufgaben weitergeben?** Ja. Die Aufgaben gehören dir. Für die Bilder gelten deren Lizenzen – ARASAAC-Piktogramme nur nicht-kommerziell; die Bildnachweise stehen automatisch dabei.
