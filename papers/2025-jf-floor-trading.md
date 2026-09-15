---
title: "Does Floor Trading Matter?"
authors: "Jonathan Brogaard; Matthew C. Ringgenberg; Dominik Roesch"
year: "2025"
venue: "Journal of Finance 80(1)"
doi: "10.1111/jofi.13401"
method: "DID"
slug: "2025-jf-floor-trading"
source_file: "uploads/jofi.13401_f2f7.pdf"
status: "carded-from-first14pp"
---

# Brogaard, Ringgenberg, and Roesch (2025) — 纽交所关交易大厅

经典同一时点 DID。处理日是 2020-03-23 COVID 关厅。DOI 在 PDF 第 1 页。对照 `references/methods/did.md`：最危险的是 COVID 同期冲击。

## 问题

- 研究问题（一句）：算法主导之后，大厅交易员还改不改善市场质量？
- Estimand：关厅后，NYSE 股票相对对照（纳斯达克匹配股，或同股其他交易所）的有效价差、定价误差变化。

## 识别

- 策略：两条 DID。(1) NYSE 股 vs 匹配 NASDAQ 股，关厅前后；(2) 同一只 NYSE 股在纽交所 vs 其他交易所。公司 FE + 时间 FE。机制用两次部分重开（特征不同）。短窗口 2020-03-16 至 2020-03-27 减缓适应/恐慌叙事。
- 关键假设：若无关厅，处理组与对照平行；关厅是大厅活动的外生关闭，不是别的市场结构同时只打 NYSE。
- 最危险威胁：2020 年 3 月波动、疫情、美联储操作对 NYSE 股与对照不对称；匹配质量；同股跨所也可能被溢出。

## 数据

- 观察单元 / 时间：股票 × 日（及日内）；2020 年关厅前后
- 来源：NYSE 提供数据；价差来自 WRDS（PESPR 等）；OneTick
- 处理与结果：处理 = 失去大厅；结果 = 比例有效价差、Hasbrouck 定价误差、开收盘拍卖偏离
- 样本限制：匹配的 NYSE / NASDAQ 股；连续交易 + 拍卖

## 主结果

- 表/图号：引言；图为 PESPR 相对 2020-01-01 的变化。回归表号前 14 页未钉 → UNVERIFIED
- 点估计：同股纽交所相对其他所，比例有效价差约 +11%；定价误差：相对纳斯达克对照约 +6%，相对同股跨所约 +2%
- 作者解释：面对面把算法没有的信息传给 DMM / 大厅经纪。

## 可攻击点

- 识别：COVID 不是干净的「只关大厅」；平行趋势在 3 月很难信
- 测量：价差在极端波动日
- 外部有效：危机月的大厅 ≠ 平常大厅
- 表文：机制「in-person human interaction」比价差上升多走了一步

## 可复用设计

- 能偷：同一处理用「跨市场对照」+「同资产跨场所对照」两套 DID；部分重开做机制
- 不该偷：把危机月单一冲击写成对日常做市的普适结论而不写边界

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13401 | PDF p.1 | 已核 PDF |
| 价差 +11%；定价误差 +6% / +2% | 引言 | 已核引言 |

## 对我的训练价值

- 练到了哪一层：DID + 同期宏观混淆
- 下一步 skill：identification-audit（对照 did.md）
