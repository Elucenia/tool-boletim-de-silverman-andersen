<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · en · no clinical/professional/rights approval -->

# Silverman–Andersen score

[conditions, sources and permissions](https://elucenia.org/en/tools/boletim-de-silverman-andersen)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Thoracoabdominal movement

`tor`

- `0` — Synchronized
- `1` — Inspiratory lag
- `2` — Seesaw breathing

### Intercostal retractions

`ic`

- `0` — Absent
- `1` — Slightly visible
- `2` — Marked

### Xiphoid retraction

`xif`

- `0` — Absent
- `1` — Slightly visible
- `2` — Marked

### Nasal flaring

`asa`

- `0` — Absent
- `1` — Slight
- `2` — Marked

### Expiratory grunting

`gem`

- `0` — Absent
- `1` — Audible with a stethoscope
- `2` — Audible without a stethoscope

## Method edition

Silverman–Andersen 1956: 5 signs 0–2, total 0–10

## Documented formula

Five signs, each 0 (absent) to 2 (marked): thoracoabdominal movement, intercostal retraction, xiphoid retraction, nasal flaring and expiratory grunting. Total 0–10: higher is worse (unlike Apgar).

## Limits and population

The Silverman-Andersen total depends on adequate observation of five respiratory signs. The 2023 reliability study in preterm infants on different forms of support found low interrater agreement; respiratory interfaces may hinder observation of signs, and training matters. The available total does not automatically determine ventilatory support or demonstrate the validity of all clinical thresholds.

## References

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
