---
title: "Scope, Scale, and Concentration: The 21st-Century Firm"
authors: "Gerard Hoberg; Gordon M. Phillips"
year: "2025"
venue: "Journal of Finance 80(1)"
doi: "10.1111/jofi.13400"
method: "IV"
slug: "2025-jf-scope-scale-concentration"
source_file: "uploads/jofi.13400_d37c.pdf"
status: "carded-from-first14pp"
---

# Hoberg and Phillips (2025) — 用 10-K 文本量范围

DOI 在 PDF 第 1 页。范围是文本构念，不是 Compustat 分部数。

## 问题

- 研究问题（一句）：过去 30 年美国上市公司是不是在不增加传统分部的情况下扩大经营范围？范围扩大如何进入估值和集中度？
- Estimand：范围（文本行业覆盖）变化对估值等的效应；作者用可再配置性等当工具。

## 识别

- 策略：10-K 业务描述 → doc2vec → 文本「D2V industries」。工具之一：资产在邻近产品空间的可再配置性（及文中提到的 distant peers 思路）。
- 关键假设：工具只通过「更容易/更值得扩范围」进估值，不直接进定价；文本范围测到的是经营范围不是公关话术。
- 最危险威胁：10-K 措辞变化；工具与投资机会相关；把相关写成「市场喜欢新型范围企业」的因果。

## 数据

- 观察单元 / 时间：美国上市公司 × 年，约过去 30 年（精确起止前 14 页未钉死 → UNVERIFIED）
- 来源：10-K；Compustat 分部作对照
- 处理与结果：范围 ↑；结果 = 估值、并购、研发、资本开支、调整后 HHI
- 样本限制：能做文本行业分解的 10-K 公司

## 主结果

- 表/图号：引言报告分位效应，表号前 14 页未钉 → UNVERIFIED
- 点估计：范围从第 25 分位到第 75 分位，估值（作者用的估值指标）+0.31
- 作者解释：范围主要通过并购和研发扩大，不是资本开支；传统分部数没升；用范围调整后，横向集中度并不在升。

## 可攻击点

- 识别：IV 排他；范围与规模缠在一起
- 测量：doc2vec 行业阈值 ¯Q 固定是否任意
- 外部有效：美国上市、10-K 语料
- 表文：「new type of firm」是叙事，证据是文本范围和估值相关/IV

## 可复用设计

- 能偷：用文本覆盖而不是官方分部；扩范围渠道拆成并购 / 研发 / 资本开支
- 不该偷：把 Compustat 分部不变直接当成「范围没变」

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13400 | PDF p.1 | 已核 PDF |
| 范围 p25→p75 估值 +0.31 | 引言 | 已核引言 |

## 对我的训练价值

- 练到了哪一层：测量（构念）+ 弱一点的 IV
- 下一步 skill：identification-audit
