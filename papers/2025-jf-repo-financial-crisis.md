---
title: "Repo over the Financial Crisis"
authors: "Adam Copeland; Antoine Martin"
year: "2025"
venue: "Journal of Finance 80(2)"
doi: "10.1111/jofi.13406"
method: "other"
slug: "2025-jf-repo-financial-crisis"
source_file: "uploads/jofi.13406_08ac.pdf"
status: "carded-from-first14pp"
---

# Copeland and Martin (2025) — 危机里的回购

描述性新数据，不是准实验。DOI 在 PDF 第 1 页。观点不代表纽联储 / 瑞士央行。

## 问题

- 研究问题（一句）：2007–09 回购活动掉了多少、掉在双边还是三方、抵押品是什么、是不是客户因对手方风险跑了？
- Estimand：无因果处理；分市场、分抵押品的存量变化。

## 识别

- 策略：拼出更全的回购图（双边 vs 三方、ID vs DtC、GC vs MIX）。不是 DID/IV。
- 关键假设：数据覆盖足以谈「全面图」；危机前后窗口可比。
- 最危险威胁：仍可能漏一段市场；「不是对手方跑路」是排除法，不是随机对照。

## 数据

- 观察单元 / 时间：券商回购存量，危机前 vs 危机
- 来源：FR 2004C 等（Table II 注）
- 处理与结果：无处理；结果 = 各类回购余额
- 样本限制：能观察到的券商负债端回购

## 主结果

- 表/图号：Table I、Table II
- 点估计：全部资产类日均存量 4,646 → 3,848，−7980 亿美元（−17%）；国债 2,400 → 1,930，−20%。下降集中在 MIX：ID −24%、DtC −31%；GC 的 ID 反而 +7%。国债 MIX：ID −23%、DtC −37%；国债 GC 的 ID +52%。作者：一半以上下降来自国债回购，且与做市/中介能力有关，不完全是客户因信用担忧撤资。
- 作者解释：和「全面 run on repo」叙事不完全一致。

## 可攻击点

- 识别：无外生冲击
- 测量：分段定义
- 外部有效：美国危机
- 表文：「至少一部分不是对手方担忧」比「国债回购也掉了」多走一步

## 可复用设计

- 能偷：同一「回购」先拆双边/三方、GC/MIX，再谈 run
- 不该偷：用一段市场的 haircut 故事外推全市场

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13406 | PDF p.1 | 已核 PDF |
| −17% / 国债 −20% | Table I | 已核 Table I 摘录 |

## 对我的训练价值

- 练到了哪一层：测量（市场分段）
- 下一步 skill：无
