<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · it · no clinical/professional/rights approval -->

# Punteggio di Silverman-Andersen

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/boletim-de-silverman-andersen)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Movimento toracoaddominale

`tor`

- `0` — Sincronizzato
- `1` — Ritardo inspiratorio
- `2` — Respiro paradosso

### Rientramenti intercostali

`ic`

- `0` — Assente
- `1` — Poco visibile
- `2` — Marcata

### Rientramento xifoideo

`xif`

- `0` — Assente
- `1` — Poco visibile
- `2` — Marcata

### Alitamento delle pinne nasali

`asa`

- `0` — Assente
- `1` — Lieve
- `2` — Marcato

### Gemito espiratorio

`gem`

- `0` — Assente
- `1` — Udibile con lo stetoscopio
- `2` — Udibile senza stetoscopio

## Edizione del metodo

Silverman–Andersen 1956: 5 segni 0–2, totale 0–10

## Formula documentata

Cinque segni, ciascuno da 0 (assente) a 2 (intenso): movimento toracoaddominale, retrazioni intercostali e xifoidee, alitamento nasale e gemito espiratorio. Totale 0–10: più alto, peggio (al contrario dell’Apgar).

## Limiti e popolazione

Il totale Silverman-Andersen dipende dall’osservazione adeguata di cinque segni respiratori. Lo studio di affidabilità del 2023 in prematuri con diversi supporti ha riscontrato un basso accordo tra valutatori; le interfacce respiratorie possono ostacolare l’osservazione dei segni e la formazione è rilevante. Il totale disponibile non determina automaticamente il supporto ventilatorio e non dimostra la validità di tutte le soglie cliniche.

## Riferimenti

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
