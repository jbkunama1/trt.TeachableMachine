# Unterrichtsvorhaben (UVP) – Teachable Machine im Unterricht (Sek I, BW 2016)

## 1. Rahmenbedingungen

- **Thema:** Wie lernt eine KI? – Ein Klassifikationsmodell mit Teachable Machine
- **Zielgruppe:** Sekundarstufe I (empfohlen: Klassen 7–9, anpassbar für 6–10)
- **Fach:** Informatik und Medienbildung (bzw. Medienbildung integriert in andere Fächer)
- **Umfang:** 4–6 Unterrichtsstunden
- **Vorkenntnisse:** Grundlegende Computerbedienung, Umgang mit Browser, einfache Dateiorganisation

## 2. Bildungsplanbezug (BW 2016)

### 2.1 Leitperspektive Medienbildung

- Leitperspektive Medienbildung (MB) als durchgängiger Auftrag aller Fächer.
- Anknüpfung an den Basiskurs Medienbildung (Kompetenzbereiche „Information und Wissen“, „Produktion und Präsentation“, „Mediengesellschaft“).

### 2.2 Prozessbezogene Kompetenzen Informatik

Auszug und Konkretisierung für dieses Vorhaben (vereinfacht formuliert):

| Bereich | Bildungsplanbezug (vereinfacht) | Konkretisierung im Vorhaben |
| --- | --- | --- |
| Strukturieren und Vernetzen | Probleme analysieren und in geeignete Teilprobleme aufteilen | Klassifikationsproblem definieren (z.B. Mülltrennung), Klassen festlegen und beschreiben |
| Modellieren und Implementieren | Informatiksysteme und Modelle erstellen/anpassen | Trainingsdaten sammeln, Modell in Teachable Machine trainieren, ggf. Export in Webumgebung |
| Kommunizieren und Kooperieren | In Teams arbeiten, Ergebnisse adressatengerecht präsentieren | Gruppenarbeit, Präsentation der Modelle und Ergebnisse im Plenum |
| Analysieren und Bewerten | Informatiksysteme und ihre Auswirkungen analysieren | Modellleistung testen, Grenzen, Bias und gesellschaftliche Auswirkungen von KI diskutieren |

## 3. Grobziel und Feinziele

### Grobziel

Die Schülerinnen und Schüler entwickeln ein grundlegendes Verständnis dafür, wie
Machine-Learning-Modelle aus Daten lernen, erproben dies praktisch mit
Teachable Machine und reflektieren Chancen und Risiken solcher Systeme.

### Feinziele (Auswahl)

Die Schülerinnen und Schüler …

1. benennen Beispiele für KI-Anwendungen aus ihrem Alltag.
2. erklären den Unterschied zwischen klassischer Programmierung und Lernen aus Daten in eigenen Worten.
3. planen ein einfaches Klassifikationsproblem und legen sinnvolle Klassen fest.
4. sammeln geeignete Trainingsdaten (Bild, Audio oder Pose) und organisieren diese strukturiert.
5. trainieren ein Modell in Teachable Machine und testen es mit neuen Beispielen.
6. dokumentieren Stärken und Schwächen ihres Modells.
7. leiten Verbesserungsmaßnahmen ab (z.B. mehr/bessere Trainingsdaten).
8. reflektieren Chancen und Risiken des Einsatzes von KI im Alltag (z.B. Bias, Fehleinschätzungen).

## 4. Verlaufsplanung (Beispiel für 5 Stunden à 45 Minuten)

### Stunde 1 – Einstieg in KI und Machine Learning

- **Ziele:**
  - Vorwissen aktivieren, Begriff „KI/Machine Learning“ an Beispielen verdeutlichen.
  - Neugier auf das eigene Projekt wecken.
- **Inhalte:**
  - Beispiele für KI im Alltag (Smartphone, Streaming, Social Media, Sprachassistenten).
  - Unterschied Programmierung vs. Machine Learning (klassische Wenn-Dann-Regeln vs. Lernen aus Daten).
  - Kurze Demo eines vorbereiteten Teachable-Machine-Modells (z.B. zwei Gesten oder zwei Objekte).
- **Methoden/Sozialformen:**
  - Brainstorming im Plenum, Think-Pair-Share, Lehrerinput, Live-Demo.
- **Materialien/Medien:**
  - Tafel/Whiteboard, Beamer/Display, Lehrer-PC mit Internet, vorbereitete TM-Demo.

### Stunde 2 – Projektidee und Datensammlung planen

- **Ziele:**
  - Projektidee und Klassen definieren.
  - Anforderungen an gute Trainingsdaten kennenlernen.
- **Inhalte:**
  - Beispielprojekte vorstellen (z.B. Mülltrennung, Emojis per Handzeichen, Umweltsounds).
  - Gruppenbildung und Wahl eines Klassifikationsproblems.
  - Kriterien für gute Trainingsdaten: Anzahl, Vielfalt, Qualität (Licht, Ton, Perspektive).
- **Methoden/Sozialformen:**
  - Gruppenarbeit, Lehrkraft als Coach, Plenumsphasen zur Sicherung.
- **Materialien/Medien:**
  - Arbeitsblatt/Canvas zur Projektplanung, Geräte mit Webcam/Mikro, Internetzugang.

### Stunde 3 – Datensammlung und erstes Training

- **Ziele:**
  - Trainingsdaten aufnehmen.
  - Erstes Modell trainieren und testen.
- **Inhalte:**
  - Arbeit in Teachable Machine: Projekt anlegen, Klassen erstellen, Beispiele aufnehmen/hochladen.
  - Modelltraining und erster Test (inkl. Beobachtung der Ausgaben/Wahrscheinlichkeiten).
- **Methoden/Sozialformen:**
  - Gruppenarbeit an Geräten, kurze Zwischenstopps für Tipps und Austausch.
- **Materialien/Medien:**
  - Computer/Notebooks/Tablets mit Webcam/Mikro und Browser, Teachable Machine Webseite.

### Stunde 4 – Optimierung und Fehleranalyse

- **Ziele:**
  - Modellleistung analysieren und verbessern.
  - Reflexion über Datenqualität und Bias anstoßen.
- **Inhalte:**
  - Test des Modells mit neuen, unbekannten Beispielen (auch mit anderen Personen).
  - Dokumentation von Fehlklassifikationen, Diskussion möglicher Ursachen.
  - Sammlung zusätzlicher Trainingsdaten für schwache Klassen, erneutes Training.
  - Gesprächsanlass: Was passiert, wenn reale KI-Systeme (z.B. Gesichtserkennung) ähnlich fehlerhaft sind?
- **Methoden/Sozialformen:**
  - Gruppenarbeit, Plenumsdiskussion, ggf. Galeriegang mit kurzen Demos.
- **Materialien/Medien:**
  - Wie in Stunde 3, zusätzlich Protokollbögen/Notizvorlagen.

### Stunde 5 – Präsentation und Reflexion

- **Ziele:**
  - Ergebnisse präsentieren und bewerten.
  - Chancen und Risiken von KI reflektieren.
- **Inhalte:**
  - Kurzpräsentationen der Gruppen (Problem, Vorgehen, Modell, Testergebnisse, Bewertung).
  - Gemeinsame Sammlung von Chancen (z.B. Unterstützung, Automatisierung) und Risiken (z.B. Fehlentscheidungen, Diskriminierung durch Bias).
  - Optional: Ausblick auf weiterführende Projekte (Export in Webprojekte).
- **Methoden/Sozialformen:**
  - Präsentation im Plenum, Feedbackrunden, Blitzlicht.
- **Materialien/Medien:**
  - Beamer/Display, ggf. vorbereitete Folien oder Plakate der Gruppen.

## 5. Methoden, Medien und Materialien

### Methoden

- Brainstorming, Think-Pair-Share, Gruppenarbeit, Lernzirkel/Stationen (optional), Präsentationen, Plenumsdiskussion.

### Medien/Materialien

- Computer/Notebooks/Tablets mit Webcam und ggf. Mikrofon
- Internetzugang
- Teachable Machine (https://teachablemachine.withgoogle.com/)
- Tafel/Whiteboard, Beamer/Display
- Arbeitsblätter/Protokollbögen (Projektplanung, Fehleranalyse, Reflexionsfragen)

## 6. Differenzierung

- **Unterstützungsangebote:**
  - Konkrete Projektvorschläge mit geringem Schwierigkeitsgrad.
  - Schritt-für-Schritt-Anleitungen mit Screenshots.
  - Klare Rollen in der Gruppe, damit auch weniger sichere SuS sinnvolle Aufgaben übernehmen können.

- **Erweiterungen:**
  - Mehr Klassen und komplexere Datensätze.
  - Export als TensorFlow.js-Modell und Einbindung in eine eigene HTML-Seite.
  - Vergleich unterschiedlicher Projekttypen (Bild vs. Audio vs. Pose).

## 7. Leistungsbewertung

Mögliche Bewertungsaspekte:

- **Fachlich:**
  - Verständlichkeit der Problembeschreibung und Klassendefinition.
  - Qualität der Datensammlung (Menge, Vielfalt, Sorgfalt).
  - Umgang mit Fehlklassifikationen und Optimierungsversuchen.

- **Methodisch/Sozial:**
  - Mitarbeit und Verantwortungsübernahme in der Gruppe.
  - Qualität der Dokumentation (Protokoll, Plakat, Präsentation).

- **Reflexion:**
  - Fähigkeit, Chancen und Risiken von KI differenziert zu benennen.
  - Bezug zu Alltagsbeispielen herstellen.

## 8. Reflexions- und Erweiterungsfragen

- Wo begegnet dir im Alltag bereits KI oder Machine Learning?
- Was könnte passieren, wenn ein KI-System dauerhaft bestimmte Personengruppen schlechter behandelt?
- Wie könnte man Probleme durch verzerrte Datenbestände vermeiden oder verringern?
- Welche Anwendungen von KI findest du besonders sinnvoll, welche kritisch?
