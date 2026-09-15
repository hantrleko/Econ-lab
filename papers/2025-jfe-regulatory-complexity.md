---
title: "Measuring regulatory complexity"
authors: "Jean-Edouard Colliard, Co-Pierre Georg"
year: 2025
venue: Journal of Financial Economics 174
doi: 10.1016/j.jfineco.2025.104186
method: measurement
slug: regulatory-complexity
source_file: uploads/Measuring-regulatory-complexity_2025_Journal-of-Financial-Economics_52e4.pdf
status: carded-from-first14pp
---

# Measuring regulatory complexity

文章编号 104186。Schnabl 编辑。版权保留。ANR / Labex / ACPR–HEC–TSE / Natixis / Europlace。工具箱源里写 zenodo 记录 16601188，未打开核验。只根据 PDF 前约 14 页。

## 问题

监管文本有多复杂，能否测到篇幅以外的东西。复杂度和精度怎么定量权衡。

## 识别

测度论文，无因果设计。监管当算法：算子与操作数（Halstead 一类）。三维：内在、心理、计算。五个文本测度；作者强调两个超出篇幅的 `quantity`（监管算子数，近 RegData）和 `potential`（独特操作数，经济概念多样性）。语料：Basel I（先写成代码再对照文本）、Dodd–Frank 各 title、EBA 2021 ITS 模板。校验：① 实验被试用随机 Basel I 型规则算风险加权资产，看错和耗时；② EBA 合规成本调查；③ 监管者「重要性」调查。不估计复杂度对银行结果的因果效应。

## 数据

监管文本结构化。实验与 EBA 调查：前 14 页未给可引用的被试/银行数。

## 主结果

五个测度里，只有 `quantity` 和 `potential` 在控篇幅后仍解释实验对错/耗时。`quantity` 还解释 EBA 高合规成本（大中银行），小银行更对 `potential` 敏感。`potential` 与监管者认为的重要性正相关，`quantity` 负相关。未见因果回归系数。

## 可攻击点

- 法律不是可执行代码；算子/操作数标注是判断。
- 实验是假设银行资产负债表，外部有效窄。
- 调查是相关，不是识别。
- 不要把页数或 zenodo 工具写成已证明的政策最优复杂度。

## 可复用设计

监管论文先报测度，再谈效应。不要只用页数。测度为卡，不当 DID。

证据指针：摘要（五维、Basel I / DFA / EBA ITS、实验+调查）；引言（`quantity`、`potential` 超出篇幅）。

训练价值：测度卡。不当准实验。
