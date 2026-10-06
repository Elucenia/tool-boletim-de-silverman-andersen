<!-- ELUCENIA technical documentation · boletim-de-silverman-andersen · zh · no clinical/professional/rights approval -->

# Silverman-Andersen 呼吸窘迫评分

[条件、来源与许可](https://elucenia.org/zh/tools/boletim-de-silverman-andersen)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 胸腹运动

`tor`

- `0` — 同步
- `1` — 吸气时胸廓凹陷
- `2` — 胸腹矛盾运动

### 肋间凹陷

`ic`

- `0` — 无
- `1` — 不明显
- `2` — 明显

### 剑突下凹陷

`xif`

- `0` — 无
- `1` — 不明显
- `2` — 明显

### 鼻翼扇动

`asa`

- `0` — 无
- `1` — 轻微
- `2` — 显著

### 呼气呻吟

`gem`

- `0` — 无
- `1` — 听诊器可闻
- `2` — 不用听诊器即可听到

## 方法版本

Silverman–Andersen 1956：5项体征0–2分，总分0–10

## 已记录的公式

五项体征，每项0分（无）至2分（明显）：胸腹运动、肋间凹陷、剑突下凹陷、鼻翼扇动及呼气呻吟。总分0–10： 越高越严重 （与Apgar相反）.

## 限制与适用人群

Silverman-Andersen总分依赖于对五项呼吸体征的适当观察。2023年对接受不同支持方式的早产儿进行的信度研究发现评估者间一致性较低；呼吸支持接口可能妨碍体征观察，培训具有重要作用。所提供的总分不会自动决定通气支持，也不能证明所有临床阈值的有效性。

## 参考文献

- [Silverman WA, Andersen DH. A controlled clinical trial of effects of water mist on obstructive respiratory signs, death rate and necropsy findings among premature infants. Pediatrics, 1956.](https://doi.org/10.1542/peds.17.1.1)

- [Hedstrom AB et al. Performance of the Silverman Andersen Respiratory Severity Score in predicting PCO2 and respiratory support in newborns: a prospective cohort study. J Perinatol, 2018.](https://doi.org/10.1038/s41372-018-0049-3)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

无呼吸窘迫


### 2

存在呼吸窘迫（1至4分）

监测血氧饱和度并频繁重新评估评分；调查病因（暂时性呼吸急促、透明膜病、肺炎、胎粪吸入）。


### 3

中度至重度呼吸窘迫（≥ 5分）

在 Hedstrom（2018）研究中，BSA ≥ 5 的新生儿中有 79% 需要在 24 小时内增加呼吸支持（而 < 5 者为 28%）。


### 4

中度至重度呼吸窘迫（≥ 5分）

在 Hedstrom（2018）研究中，BSA ≥ 5 的新生儿中有 79% 需要在 24 小时内增加呼吸支持（而 < 5 者为 28%）。

