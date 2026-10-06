<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · fr · no clinical/professional/rights approval -->

# Score de Silverman-Andersen

[conditions, sources et autorisations](https://elucenia.org/fr/outils/boletim-de-silverman-andersen)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Mouvement thoracoabdominal

`tor`

- `0` — Synchronisé
- `1` — Retard inspiratoire
- `2` — Balancement thoracoabdominal

### Tirage intercostal

`ic`

- `0` — Absent
- `1` — Peu visible
- `2` — Marquée

### Rétraction xiphoïdienne

`xif`

- `0` — Absent
- `1` — Peu visible
- `2` — Marquée

### Battement des ailes du nez

`asa`

- `0` — Absent
- `1` — Discret
- `2` — Marqué

### Geignement expiratoire

`gem`

- `0` — Absent
- `1` — Audible au stéthoscope
- `2` — Audible sans stéthoscope

## Édition de la méthode

Silverman–Andersen 1956 : 5 signes 0–2, total 0–10

## Formule documentée

Cinq signes, chacun 0 (absent) à 2 (intense) : mouvement thoraco-abdominal, tirage intercostal, rétraction xiphoïdienne, battement des ailes du nez et geignement expiratoire. Total 0–10 : plus élevé signifie plus grave (à l’inverse d’Apgar).

## Limites et population

La somme Silverman-Andersen dépend d’une observation adéquate de cinq signes respiratoires. L’étude de fiabilité de 2023 chez des prématurés sous différentes assistances respiratoires a retrouvé une faible concordance entre évaluateurs ; les interfaces respiratoires peuvent gêner l’observation des signes et la formation est importante. La somme disponible ne détermine pas automatiquement l’assistance ventilatoire et ne démontre pas la validité de tous les seuils cliniques.

## Références

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Aucune détresse respiratoire


### 2

Détresse respiratoire présente (1 à 4 points)

Surveiller la saturation et réévaluer fréquemment le score ; rechercher la cause (tachypnée transitoire, maladie des membranes hyalines, pneumonie, aspiration méconiale).


### 3

Détresse modérée à sévère (≥ 5 points)

Dans l'étude de Hedstrom (2018), 79% des nouveau-nés avec BSA ≥ 5 ont eu besoin d'une augmentation du support respiratoire dans les 24 heures (contre 28% avec < 5).


### 4

Détresse modérée à sévère (≥ 5 points)

Dans l'étude de Hedstrom (2018), 79% des nouveau-nés avec BSA ≥ 5 ont eu besoin d'une augmentation du support respiratoire dans les 24 heures (contre 28% avec < 5).

