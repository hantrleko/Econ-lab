---
title: "Mergers and acquisitions, technological change, and inequality"
authors: "Wenting Ma, Paige Ouimet, Elena Simintzi"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104136
method: matched DID
slug: ma-tech-inequality
source_file: uploads/1-s2.0-S0304405X25001448-main_6df9.pdf
status: carded-from-first14pp
---

# Mergers and acquisitions, technological change, and inequality

文章编号 104136。Papanikolaou 编辑。BLS OEWS 限制数据，观点不代表 BLS。SSHRC Insight。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

水平并购之后，目标店的常规职业份额、IT 投资和店内工资不平等会怎么变。是不是收购方把技术能力迁到目标。

## 识别

2001–2017 水平并购目标店 vs 匹配未并购店。处理：成为水平并购目标。不是随机并购。异质性：目标事前常规份额相对收购方更高、收购方工资或 IT 更高时效应更大。错时并购；前 14 页未见 stacked / Callaway–Sant’Anna。最危险：收购方专挑将要自动化的目标；匹配吃掉可观测，吃不掉并购时机。

## 数据

BLS OEWS 职业就业与工资。2924 家目标店、1159 起水平并购。IT：CiTDB。就业水平用年内分位（Chen–Roth / Delius–Sterck）处理零值。

## 主结果

目标店常规职业份额相对对照大约 −1.9 个百分点（相对事前均值 −5.3%，约合年化 −1.23%）。目标事前常规更高时大约 −4 个百分点。常规就业分位下降、非常规不显著。IT 投资（人均 IT）分位在收购方事前 IT 更高的交易里每年大约 +2.1（+2.3）个百分点。作者称店内工资不平等升。点估计表号在后文。

## 可攻击点

- 匹配 DID 不是随机并购；「技术转移」是事后叙事。
- 错时未报现代估计量。
- OEWS 是店–职业，不是工人追踪；份额下降可以是编制或分类。
- IT 匹配率引言写特别低。
- 不要把稳健性异质性写成第二条贡献。

## 可复用设计

并购劳动后果按职业常规强度拆，不要只报总就业。零就业用分位。同时报 IT。错时要补现代估计量。可跑识别审计。

证据指针：摘要（常规下降、不平等升）；引言（2924/1159、−1.9 pp / −5.3%、−4 pp、IT +2.1/+2.3）。

训练价值：匹配错时并购。识别未闭合。
