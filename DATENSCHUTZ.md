# Datenschutz

Diese Erklärung steht auch in der App unter „?“ → „Datenschutz“.

**Kurz gesagt:**

- Textsachen hat keinen Server. Alles läuft lokal in deinem Browser.
- Deine Aufgaben werden nur auf deinem Gerät gespeichert.
- Keine Anmeldung, keine Cookies, kein Tracking, keine Analyse, keine Werbung.
- Verbindungen ins Internet gibt es nur, wenn du die Bildsuche (ARASAAC, BildWort, Wikimedia Commons) benutzt, Bilder automatisch suchen lässt oder eine Bildadresse (URL) einfügst – siehe Punkt 4 –, und wenn du eine KI über eine API-Schnittstelle nutzt – siehe Punkt 7.

### 1. Alles läuft lokal in deinem Browser

Textsachen ist eine einzelne HTML-Datei. Alles, was du tust – Texte schreiben, Bilder einfügen, Aufgaben exportieren –, berechnet dein Browser selbst auf deinem Gerät. Es gibt **keinen Server von Textsachen**, an den Daten geschickt werden. Wir sehen weder deine Aufgaben noch deine Bilder.

Wenn du Textsachen von einer Webseite aus aufrufst, ruft dein Browser die Datei von dem Webserver ab, auf dem sie liegt. Dabei verarbeitet der Betreiber dieses Webservers technisch notwendige Daten (z. B. IP-Adresse, Zeitpunkt). Dafür gilt die Datenschutzerklärung der jeweiligen Webseite. Öffnest du die heruntergeladene Datei direkt von deinem Rechner, entfällt auch das.

### 2. Speicherung nur auf deinem Gerät

Damit nichts verloren geht, speichert Textsachen die aktuelle Aufgabe automatisch im Speicher deines Browsers (IndexedDB) – nur auf diesem Gerät, nur in diesem Browser. Niemand sonst hat Zugriff darauf. Du löschst diese Daten, indem du eine „Neue Aufgabe“ beginnst oder in deinem Browser die Website-Daten löschst.

Öffnest du Textsachen im Lernsachen-Heft, liegt der Entwurf getrennt davon und wird gelöscht, sobald die Aufgabe im Heft ist oder du abbrichst. Die Aufgabe gibt Textsachen dabei nur an das Heft in deinem Browser weiter – sie verlässt dein Gerät nicht.

Außerdem merkt sich Textsachen im lokalen Speicher deines Browsers (localStorage) die **Einstellungen des KI-Dialogs** (Thema, Zielgruppe usw. – den API-Schlüssel nur, wenn du das einschaltest, siehe Punkt 7), ob die **automatische Bildersuche** an ist, und – für die Bildersuche, bis zu 30 Tage – die öffentliche **Stichwortliste von ARASAAC** (keine Daten von dir). Du löschst das, indem du in deinem Browser die Website-Daten löschst.

Dateien wie HTML, SCORM-Pakete oder PDF entstehen ebenfalls nur lokal und werden in deinem Download-Ordner gespeichert. Was du damit machst (z. B. in mebis hochladen), entscheidest du.

### 3. Keine Cookies, kein Tracking

Textsachen setzt keine Cookies, verwendet keine Analyse- oder Statistikdienste, keine Werbung und keine Social-Media-Plugins. Alle Programmteile und Schriften sind in der Datei enthalten; es wird nichts aus dem Internet nachgeladen.

### 4. Externe Verbindungen: nur bei Bildsuche und Bildadresse

Nur wenn du im Bild-Dialog **selbst** eine Suche startest oder ein Suchergebnis übernimmst, verbindet sich dein Browser direkt mit dem jeweiligen Dienst:

| Dienst | Adressen | Datenschutz |
|---|---|---|
| **ARASAAC** (Regierung von Aragón, Spanien) | `api.arasaac.org`, `static.arasaac.org` | [Datenschutzerklärung von ARASAAC](https://arasaac.org/privacy-policy) |
| **BildWort** (Christian Urff) | `symbole.urff.app` | [Datenschutzhinweise von BildWort](https://symbole.urff.app/hilfe#datenschutz) |
| **Wikimedia Commons** (Wikimedia Foundation, USA) | `commons.wikimedia.org`, `upload.wikimedia.org`, `thumb.wikimedia.org` | [Datenschutzrichtlinie der Wikimedia Foundation](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy/de) |

Dabei werden **deine IP-Adresse**, der **Suchbegriff** und übliche technische Angaben deines Browsers (z. B. Browsertyp, Sprache) an diesen Dienst übermittelt – so wie beim Besuch der jeweiligen Webseite. Textsachen schickt keine weiteren Daten mit, insbesondere nicht deine Aufgabe. Gib deshalb keine personenbezogenen Daten als Suchbegriff ein. Die Wikimedia Foundation sitzt in den USA; Daten können dorthin übertragen werden. BildWort zählt die Suchwörter (ohne IP-Adresse, höchstens 90 Tage), damit seine Redaktion sieht, welche Bilder noch fehlen. Außerdem merkt sich dein Browser (localStorage), in welcher Reihenfolge die Bildquellen gefragt werden und welches Bild du zuletzt für ein Wort gewählt hast (Wort, Bildadresse, Bildnachweis) – das gilt für alle vier Lernsachen-Apps auf diesem Gerät.

**Automatische Bildersuche:** Gibst du Wörter oder einen Text ein, sucht dein Browser kurz darauf von selbst bei ARASAAC und BildWort (in der Reihenfolge, die du unter „Quellen“ im Bild-Dialog einstellst; Wikimedia nie) nach Bildern zu diesen Wörtern (bei Texten zu den abbildbaren Wörtern, in ihrer Grundform). Dabei gilt dasselbe wie bei der Bildsuche: der Dienst erfährt die Suchwörter und deine IP-Adresse. Einmal lädt dein Browser dafür auch die öffentliche Stichwortliste von ARASAAC. Möchtest du das nicht, schalte im Schritt „Bilder“ „Bilder automatisch suchen“ aus – schreibe dann keine Wörter, bevor du die Suche ausgeschaltet hast.

Fügst du unter „Oder Bildadresse (URL) einfügen“ eine Adresse ein oder ziehst ein Bild aus einer anderen Webseite hinein, lädt dein Browser das Bild von dieser Webseite – auch dabei erfährt deren Betreiber deine IP-Adresse.

Links in Bildnachweisen, in dieser Hilfe oder zu Lizenzen öffnen sich erst, wenn du sie anklickst, in einem neuen Tab.

### 5. Sprachausgabe (Vorlesen)### 6. Sprachausgabe (Vorlesen)

Die Vorlese-Funktion nutzt die Sprachausgabe deines Geräts bzw. Browsers. Textsachen schickt dafür selbst nichts ins Internet. **Hinweis:** Manche Browser (z. B. Google Chrome oder Microsoft Edge) bieten zusätzlich Online-Stimmen an. Wird eine solche Stimme verwendet, übermittelt der Browser den vorzulesenden Text an den Anbieter der Stimme (z. B. Google oder Microsoft). Darauf hat Textsachen keinen Einfluss. Wenn du das vermeiden möchtest, nutze einen Browser mit lokalen Stimmen (z. B. Safari oder Firefox).

### 6. Exportierte Aufgaben

Exportierte Aufgaben (HTML-Datei – auch eingebettet per iframe –, SCORM-Paket, PDF) enthalten alles, was sie brauchen – Bilder, Schriften und das Programm. Sie **laden nichts aus dem Internet nach**, setzen keine Cookies und enthalten keine Tracker. Für das Vorlesen gilt Punkt 5 auf dem Gerät der Lernenden.

Ein **SCORM-Paket** meldet Punkte, Fortschritt, die Eingaben zu jedem Wort, „bestanden“/„nicht bestanden“ und den Bearbeitungsstand (zum Fortsetzen) ausschließlich an die Lernplattform, in die du es hochgeladen hast (z. B. mebis). Dort gelten die Datenschutzbestimmungen dieser Plattform bzw. deiner Schule.

### 7. Personenbezogene Daten und KI

Du entscheidest, was in einer Aufgabe steht. Bitte verwende **keine personenbezogenen Daten von Schülerinnen und Schülern** (z. B. Namen, Noten, Fotos) ohne Einwilligung bzw. ohne Rechtsgrundlage. Das gilt besonders, wenn du Aufgaben weitergibst oder veröffentlichst. Beachte auch Urheber- und Persönlichkeitsrechte bei Bildern.

**KI-Chat:** Beim Weg „Über einen KI-Chat“ (im Schritt „Inhalt“ → „Mit KI erstellen …“) schickt Textsachen selbst nichts an eine KI – du kopierst nur einen Text (den Prompt) in die Zwischenablage und fügst ihn selbst in eine KI-Anwendung deiner Wahl ein. Dort gelten die Bedingungen dieses Anbieters.

**API-Schnittstelle:** Nur wenn du „Über eine API-Schnittstelle“ wählst und auf „Aufgabe erzeugen“ klickst, schickt dein Browser den Prompt (Thema, Material, deine Auswahl) direkt an den eingestellten Dienst – an Anthropic, an den gewählten Anbieter oder an eine lokale KI auf deinem Rechner bzw. im Schulnetz. Dabei erfährt der Dienst auch deine IP-Adresse. Es gelten die Bedingungen des Anbieters; die Kosten richten sich nach deinem Vertrag. Den API-Schlüssel speichert Textsachen nur in deinem Browser und nur, wenn du „Schlüssel in diesem Browser speichern“ einschaltest. In exportierte Aufgaben gelangen weder Schlüssel noch Einstellungen.

Gib in keine KI personenbezogene Daten von Schülerinnen und Schülern ein.

### 8. Verantwortlich

Textsachen wird von [Lernsachen.blog](https://lernsachen.blog) bereitgestellt. Da das Werkzeug selbst keinen Server hat, werden durch Textsachen keine personenbezogenen Daten an Lernsachen.blog übermittelt oder dort gespeichert. Für Fragen zum Datenschutz erreichst du uns über [lernsachen.blog](https://lernsachen.blog); dort findest du auch das Impressum.
