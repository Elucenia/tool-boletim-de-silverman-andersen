<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · es · no clinical/professional/rights approval -->

# Puntuación de Silverman-Andersen

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/boletim-de-silverman-andersen)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Movimiento toracoabdominal

`tor`

- `0` — Sincronizado
- `1` — Retraso inspiratorio
- `2` — Respiración paradójica

### Tiraje intercostal

`ic`

- `0` — Ausente
- `1` — Poco visible
- `2` — Marcada

### Retracción xifoidea

`xif`

- `0` — Ausente
- `1` — Poco visible
- `2` — Marcada

### Aleteo nasal

`asa`

- `0` — Ausente
- `1` — Leve
- `2` — Marcado

### Quejido espiratorio

`gem`

- `0` — Ausente
- `1` — Audible con estetoscopio
- `2` — Audible sin estetoscopio

## Edición del método

Silverman–Andersen 1956: 5 signos 0–2, total 0–10

## Fórmula documentada

Cinco signos de 0 (ausente) a 2 (intenso): movimiento toracoabdominal, tiraje intercostal, retracción xifoidea, aleteo nasal y quejido espiratorio. Total 0–10: cuanto mayor, peor (al contrario de Apgar).

## Límites y población

La suma Silverman-Andersen depende de la observación adecuada de cinco signos respiratorios. El estudio de fiabilidad de 2023 en prematuros con distintos soportes encontró baja concordancia entre evaluadores; las interfaces respiratorias pueden dificultar la observación de signos y la formación es importante. La suma disponible no determina automáticamente el soporte ventilatorio ni demuestra la validez de todos los umbrales clínicos.

## Referencias

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Sin dificultad respiratoria


### 2

Distrés respiratorio presente (1 a 4 puntos)

Monitorear la saturación y reevaluar el puntaje con frecuencia; investigar la causa (taquipnea transitoria, enfermedad de membrana hialina, neumonía, aspiración de meconio).


### 3

Distrés moderado a grave (≥ 5 puntos)

En el estudio de Hedstrom (2018), 79% de los recién nacidos con BSA ≥ 5 necesitaron aumentar el soporte respiratorio en 24 horas (frente a 28% con < 5).


### 4

Distrés moderado a grave (≥ 5 puntos)

En el estudio de Hedstrom (2018), 79% de los recién nacidos con BSA ≥ 5 necesitaron aumentar el soporte respiratorio en 24 horas (frente a 28% con < 5).

