---
title: "War Discourse and the Cross Section of Expected Stock Returns"
authors: "David Hirshleifer; Dat Mai; Kuntara Pukthuanthong"
year: "2025"
venue: "Journal of Finance 80(6)"
doi: "10.1111/jofi.13482"
method: "other"
slug: "2025-jf-war-discourse-returns"
source_file: "uploads/jofi.13482_77b9.pdf"
status: "carded-from-first14pp"
---

# Hirshleifer, Mai, and Pukthuanthong (2025) — 战争话语因子

文本资产定价。DOI 在 PDF 第 1 页。Dat Mai 就职 MKT MediaStats。

## 问题

- 研究问题（一句）：媒体里的战争话题，能不能做成解释股票截面的风险因子——对冲战争的资产是不是预期收益更低？
- Estimand：战争因子（WarFac）在传统与机器学习测试资产、以及 138 个异常上的价格；可交易版本的溢价。

## 识别

- 策略：半监督主题模型，从约 160 年、700 万篇《纽约时报》抽战争话语，做成冲击因子。不是准实验。
- 作者给两种读法：对冲战争风险 → 更低风险溢价；或对战争消息更敏感的资产被高估。
- 对照：无监督 LDA 战争主题不带溢价；与其他媒体不确定性因子比较。

## 数据

- 《纽约时报》约 700 万篇、160 年。
- 测试资产：Hou, Xue, and Zhang (2020) 的 138 个多空，以及作者复现的异常。

## 主结果

- 战争因子能预测这些截面；溢价相对标准因子是增量的。
- WarFac 的收益溢价为负且显著，在比较组里幅度常排在最前几名（只读前 14 页未见精确月度 bps）。
- 可交易战争组合同样是显著为负的 beta 溢价。
- 无监督 LDA 的战争主题没有溢价——监督/半监督的主题定义本身在干活。

## 可攻击点

- 文本因子对词典、报纸和战争定义敏感。
- 「对冲」对「错误定价」在前 14 页没有被分开检验清楚。
- 160 年里战争形态变了，稳态溢价未必存在。

## 可复用设计

- 灾难风险不要只用通用尾部指标，战争新闻可能是另一条。
- 文本因子必须过：多种测试资产、可交易版本、无监督安慰剂。
- 半监督比纯 LDA 更可能「找到自己想要的主题」，这既是贡献也是攻击点。

## 证据指针

- 700 万篇、160 年、138 个异常：PDF 第 1 页摘要。
- 负溢价、LDA 无溢价：PDF 第 3–5 页。

## 训练价值

文本资产定价方法卡。不要写成「战争导致收益」的因果。
