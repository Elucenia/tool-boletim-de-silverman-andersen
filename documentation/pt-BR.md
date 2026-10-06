<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · pt-BR · no clinical/professional/rights approval -->

# Boletim de Silverman-Andersen

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/boletim-de-silverman-andersen)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Movimento tóraco-abdominal

`tor`

- `0` — Sincronizado
- `1` — Declínio inspiratório
- `2` — Balancim (gangorra)

### Tiragem intercostal

`ic`

- `0` — Ausente
- `1` — Pouco visível
- `2` — Marcada

### Retração xifoide

`xif`

- `0` — Ausente
- `1` — Pouco visível
- `2` — Marcada

### Batimento de asa nasal

`asa`

- `0` — Ausente
- `1` — Discreto
- `2` — Acentuado

### Gemido expiratório

`gem`

- `0` — Ausente
- `1` — Audível com estetoscópio
- `2` — Audível sem estetoscópio

## Edição do método

Silverman Andersen 1956:5 sinais 0–2, total 0–10

## Fórmula documentada

Cinco sinais, cada um de 0 (ausente) a 2 (intenso): movimento tóraco-abdominal, tiragem intercostal, retração xifoide, batimento de asa nasal e gemido expiratório. Total de 0 a 10: quanto maior, pior (ao contrário do Apgar).

## Limites e população

A soma Silverman-Andersen depende de observação adequada de cinco sinais respiratórios. O estudo de confiabilidade de 2023 em prematuros sob diferentes suportes encontrou baixa concordância entre avaliadores; interfaces respiratórias podem dificultar a observação de sinais e o treinamento é relevante. A soma disponível não determina automaticamente o suporte ventilatório e não comprova validade de todos os limiares clínicos.

## Referências

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Sem desconforto respiratório


### 2

Desconforto respiratório presente (1 a 4 pontos)

Monitorar saturação e reavaliar o boletim com frequência; investigar a causa (taquipneia transitória, doença da membrana hialina, pneumonia, aspiração de mecônio).


### 3

Desconforto moderado a grave (≥ 5 pontos)

No estudo de Hedstrom (2018), 79% dos recém-nascidos com BSA ≥ 5 precisaram aumentar o suporte respiratório em 24 horas (contra 28% com < 5).


### 4

Desconforto moderado a grave (≥ 5 pontos)

No estudo de Hedstrom (2018), 79% dos recém-nascidos com BSA ≥ 5 precisaram aumentar o suporte respiratório em 24 horas (contra 28% com < 5).

