# Kursabgabe Wireframing: foodsharing Niddatal e.V.

Abgabe bis Donnerstag 01.10.2026, 9 Uhr, im Slack-Thread. Vier Teile (Kursvorlage S. 18).
Alles in eckigen Klammern [ ] musst du noch selbst ausfüllen oder prüfen.

Fall: A (Landingpage), angepasst auf einen foodsharing-Verein. Ziel der Seite: Partnerbetriebe gewinnen. Zielgruppe: Bäckereien, Märkte, Gastronomie. Größte Sorge: „Bei uns kommt doch schon die Tafel.“

---

## 1. Muster-Tabelle (5 Zeilen)

Stand 30.09.2026. Alle Beobachtungen stehen auf den genannten Seiten.

**Zeile 1: Klarheit**
Gesehen: foodsharing.de/fuer-unternehmen beginnt mit einer Begrüßung und langem Fließtext. Was der Betrieb davon hat („Das können wir Ihrem Betrieb bieten“) steht erst im zweiten Absatz, es gibt keinen Knopf. tafel.de/spenden/lebensmittel-spenden dagegen hat die H1 „Lebensmittel spenden“ und nennt Händler:innen im ersten Satz.
Hebel: Klarheit
Umsetzung: Meine H1 nennt Handlung, Zielgruppe und Ort („Lebensmittel retten in Niddatal, Wöllstadt und Reichelsheim: Werden Sie Partnerbetrieb“). Der Primär-Knopf steht im ersten Bildschirm.

**Zeile 2: Einwände (Tafel)**
Gesehen: foodsharing.de/fuer-unternehmen, dritter Absatz: foodsharing sieht sich als „Ergänzung und Unterstützung der über 900 Tafeln“. Bei Betrieben mit Tafel wird nur abgeholt, was die Tafel nicht verwenden kann. Die Antwort steht mitten im Text, nicht oben.
Hebel: Einwände
Umsetzung: Der häufigste Einwand meines Vereins („Bei uns kommt schon die Tafel“) steht im Hero-Untertitel („Die Tafel hat Vorrang“) und hat eine eigene Sektion („Die Tafel kommt schon? Perfekt.“).

**Zeile 3: Einwände (Kosten und Aufwand)**
Gesehen: foodsharing.de/fuer-unternehmen: „Mit uns sparen Sie Geld und Arbeitskraft“, darunter Einsparung der Müllentsorgungskosten und der Sortierarbeit. tafel.de nennt „Lager- und Entsorgungskosten“ als Vorteil weit oben.
Hebel: Einwände
Umsetzung: Sektion 2 sagt „Das spart Ihrem Betrieb Entsorgungsaufwand und Lebensmittelabfälle“. Die Frage „Welche Kosten entstehen?“ steht in der Fragen-Sektion.

**Zeile 4: Vertrauen**
Gesehen: foodsharing.de/fuer-unternehmen belegt mit Zahlen („über 17.000 Betriebe“, „über 180.000 engagierte Menschen“), Partnernamen (Bio Company, Alnatura) und dem Zitat eines Geschäftsführers. Rechtlich beruhigt die Rechtsvereinbarung, die alle Foodsaver unterschreiben.
Hebel: Vertrauen
Umsetzung: Mein Verein ist neu, deshalb keine erfundenen Zahlen. Die Vertrauenszeile lautet „Neu im August 2026 gegründet · Teil des bundesweiten foodsharing-Netzwerks“. Schritt 3 nennt Ausweis und Rechtsvereinbarung.

**Zeile 5: Wenig Reibung**
Gesehen: foodsharing.de/fuer-unternehmen: Kontakt nur über eine E-Mail-Adresse (unternehmen(at)foodsharing.de), am Ende des langen Textes, kein Knopf und kein Formular. tafel.de: E-Mail und Telefon.
Hebel: Wenig Reibung
Umsetzung: Der Primär-Knopf „Partnerbetrieb werden“ öffnet direkt eine E-Mail an den Vorstand, ohne Formular. Dazu ein QR-Code mit Mailto für Flyer.

[Vor dem Absenden: Zeilen 1, 4 und 5 am Handy auf den genannten Seiten nachsehen. Ich habe sie am Laptop-Text gelesen, nicht am Handy.]

---

## 2. Bauplan-Prompt (Version 4, in Stitch eingegeben)

```
SEITE: Landingpage für den foodsharing-Verein Niddatal Wöllstadt Reichelsheim (Wetterau)
ZIEL: genau eine Handlung: Partnerbetrieb werden (Kontakt aufnehmen)
ZIELGRUPPE: Inhaber:innen und Filialleitungen von Bäckereien, Supermärkten, Gastronomie und Hofläden in der Region. Größte Sorge laut Recherche: »Bei uns kommt doch schon die Tafel.«
NAVIGATION: [LOGO] links, Links »Für Betriebe«, »Mitmachen«, »Fairteiler«, rechts »Kontakt«
HERO: H1 »Lebensmittel retten in Niddatal, Wöllstadt und Reichelsheim: Werden Sie Partnerbetrieb«. Unterzeile als p-Text »Die Tafel hat Vorrang. Wir holen ab, was übrig bleibt, kostenlos und ehrenamtlich.« Primär-Knopf »Partnerbetrieb werden«. Sekundär-Knopf »Als Foodsaver:in mitmachen«. Vertrauenszeichen »Neu im August 2026 gegründet, Teil des bundesweiten foodsharing-Netzwerks«. Bild: Foodsaver:in holt Backwaren ab.
SEKTION 2: H2 »Die Tafel kommt schon? Perfekt.«, p-Text »foodsharing ersetzt die Tafel nicht, sondern ergänzt dort, wo Lebensmittel übrig bleiben.«, 3 Karten mit je H3 und p-Text: Die Tafel hat Vorrang, Wir ergänzen bei Resten und Mengen, Kurzfristig und regelmäßig
SEKTION 3: H2 »So funktioniert die Zusammenarbeit«, Ablauf in 3 Schritten: Kennenlernen, Abholzeiten festlegen, Lebensmittel werden abgeholt
SEKTION 4: H2 »Ihre Fragen, unsere Antworten«, 4 Fragen als Liste mit Antworten als [ANTWORT]: Kosten, Haftung, Aufwand, Abholzeiten
SEKTION 5: H2 »Sie möchten privat helfen?«, 2 Karten mit je H3, p-Text und Knopf: »Foodsaver:in werden« und »Fairteiler in der Nähe finden« mit p-Text »Zwei Fairteiler: [STANDORT 1], [STANDORT 2]«
SEKTION 6: H2 »Gemeinsam gegen Verschwendung«, Abschluss-Knopf »Partnerbetrieb werden«, darunter Einzugsgebiet als p-Text »Aktiv in Niddatal, Wöllstadt, Reichelsheim, Echzell, Wölfersheim, Berstadt und der Wetterau«
FOOTER: Kontakt vereinsvorstand.niddatal@foodsharing.network, Impressum, Datenschutz, Link zu foodsharing.de
REGELN: genau eine H1, H2 für Sektionen, H3 in Karten. Handy zuerst, eine Spalte, Laptop bis drei Spalten. Wireframe in Graustufen. Zahlen, Namen und Antworten nicht erfinden, sondern als [ZAHL], [NAME], [STANDORT] oder [ANTWORT] kennzeichnen. Alle Texte auf Deutsch.
```

Änderungen danach in Stitch (Chat, je Bildschirm):
- Hero: »rechtssicher« ersetzt, Bildunterschrift unter dem Foto gelöscht.
- Footer: Adresse durch [ADRESSE] ersetzt, die Zeilen »PRIO 01/02/03« unter den Karten entfernt.
- Schritt 3: Ausweis-Text ersetzt durch »Unsere Foodsaver:innen weisen sich bei jeder Abholung mit dem foodsharing-Ausweis aus und haben die Rechtsvereinbarung akzeptiert.«
- Karte »Wir ergänzen bei Resten und Mengen«: Text um Entsorgungsaufwand ergänzt (aus Zeile 3 der Tabelle).
Das sind vier Änderungen, die Aufgabe sieht höchstens zwei vor. Drei davon korrigieren Angaben, die Stitch erfunden hatte (Hero, Footer, Ausweis-Text), eine setzt Zeile 3 der Muster-Tabelle um (Entsorgungsaufwand).

---

## 3. Screenshot (Handy-Ansicht)

Datei: wireframe-handy-hero.png (Ausschnitt aus dem Stitch-Export der Handy-Version, oberer Teil: H1, Primär-Knopf, Foto).
Alternativ dein eigener Screenshot über Stitch: Preview, Mobile.

---

## 4. Drei Sätze

1. Übernommen habe ich aus der Recherche die Einwandbehandlung: Der häufigste Einwand meines Vereins („Bei uns kommt schon die Tafel“) steht im Hero-Untertitel und hat eine eigene Sektion, weil foodsharing.de ihn erst mitten im Text beantwortet, während die Tafel-Seite Kosten- und Entsorgungsvorteile schon weit oben nennt.
2. Falsch gemacht habe ich, dass mein Bauplan nur erfundene Zahlen und Namen verbot: Stitch schrieb trotzdem Behauptungen wie „rechtssicher“ und „verifizierte Foodsaver:innen“ hinein, die ich erst am foodsharing-Wiki prüfen und ersetzen musste, und dabei habe ich vier statt der vorgesehenen höchstens zwei Änderungen gemacht.
3. [Fünf-Sekunden-Test: Die Testperson hat gesagt: Angebot = ..., für wen = ..., was man tun soll = ... . Daraus folgt: ... .]

---

## Fünf-Sekunden-Test (Leitfaden)

1. Person wählen, die den Verein und das Projekt nicht kennt.
2. Handy-Ansicht des Wireframes (Stitch: Preview, Mobile, oder den Screenshot) genau fünf Sekunden zeigen, dann wegnehmen.
3. Drei Fragen stellen: Was wird hier angeboten? Für wen? Was soll man tun?
4. Antworten wörtlich notieren, nicht korrigieren.
5. Stimmen die Antworten nicht, ist der Hero nicht klar genug. Dann in Satz 3 benennen, was gefehlt hat.
