<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · de · no clinical/professional/rights approval -->

# Silverman-Andersen-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/boletim-de-silverman-andersen)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Thorakoabdominale Bewegung

`tor`

- `0` — Synchron
- `1` — Inspiratorische Verzögerung
- `2` — Paradoxe Atmung

### Interkostale Einziehungen

`ic`

- `0` — Nicht vorhanden
- `1` — Kaum sichtbar
- `2` — Ausgeprägt

### Xiphoidale Einziehung

`xif`

- `0` — Nicht vorhanden
- `1` — Kaum sichtbar
- `2` — Ausgeprägt

### Nasenflügeln

`asa`

- `0` — Nicht vorhanden
- `1` — Gering
- `2` — Ausgeprägt

### Exspiratorisches Stöhnen

`gem`

- `0` — Nicht vorhanden
- `1` — Mit Stethoskop hörbar
- `2` — Ohne Stethoskop hörbar

## Fassung der Methode

Silverman–Andersen 1956: 5 Zeichen 0–2, gesamt 0–10

## Dokumentierte Formel

Fünf Zeichen, jeweils 0 (fehlend) bis 2 (ausgeprägt): thorakoabdominale Bewegung, interkostale Einziehung, xiphoidale Einziehung, Nasenflügeln und exspiratorisches Stöhnen. Gesamt 0–10: je höher, desto schlechter (anders als beim Apgar).

## Grenzen und Population

Die Silverman-Andersen-Summe hängt von der angemessenen Beobachtung von fünf Atemzeichen ab. Die Zuverlässigkeitsstudie von 2023 bei Frühgeborenen mit unterschiedlichen Formen der Atemunterstützung fand eine geringe Übereinstimmung zwischen Beurteilenden; Beatmungsinterfaces können die Beobachtung erschweren, und Schulung ist wichtig. Die verfügbare Summe bestimmt die Beatmungsunterstützung nicht automatisch und belegt nicht die Gültigkeit aller klinischen Schwellenwerte.

## Referenzen

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
