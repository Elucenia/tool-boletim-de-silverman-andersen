<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · ja · no clinical/professional/rights approval -->

# Silverman-Andersen呼吸窮迫スコア

[条件・出典・許諾](https://elucenia.org/ja/tools/boletim-de-silverman-andersen)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 胸腹部運動

`tor`

- `0` — 同期
- `1` — 吸気時の胸郭陥没
- `2` — 胸腹部のシーソー呼吸

### 肋間陥没

`ic`

- `0` — なし
- `1` — わずかに見える
- `2` — 著明

### 剣状突起部の陥没

`xif`

- `0` — なし
- `1` — わずかに見える
- `2` — 著明

### 鼻翼呼吸

`asa`

- `0` — なし
- `1` — 軽微
- `2` — 著明

### 呼気性呻吟

`gem`

- `0` — なし
- `1` — 聴診器で聞こえる
- `2` — 聴診器なしで聞こえる

## 方法の版

Silverman–Andersen 1956：5徴候0～2点、合計0～10

## 記載された計算式

5徴候を各0（なし）～2（高度）で採点：胸腹部の動き、肋間陥没、剣状突起下陥没、鼻翼呼吸、呼気性呻吟。合計0～10： 高いほど重症 （Apgarとは逆）.

## 限界・対象集団

Silverman-Andersenの合計点は、五つの呼吸徴候を適切に観察することに依存します。さまざまな呼吸補助を受ける早産児を対象とした2023年の信頼性研究では、評価者間の一致度が低いことが示されました。呼吸補助のインターフェースは徴候の観察を妨げる場合があり、訓練が重要です。利用できる合計点だけで換気補助を自動的に決定することはできず、すべての臨床閾値の妥当性も証明できません。

## 参考文献

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

呼吸窮迫なし


### 2

呼吸窮迫あり（1～4点）

酸素飽和度を監視し、スコアを頻回に再評価する；原因を調べる（遷延性頻呼吸、硝子膜病、肺炎、胎便吸引）。


### 3

中等度から重度の呼吸窮迫（≥ 5点）

Hedstrom の研究（2018）では、BSA ≥ 5 の新生児の79%が24時間以内に呼吸サポートの増強を必要とした（< 5 では28%）。


### 4

中等度から重度の呼吸窮迫（≥ 5点）

Hedstrom の研究（2018）では、BSA ≥ 5 の新生児の79%が24時間以内に呼吸サポートの増強を必要とした（< 5 では28%）。

