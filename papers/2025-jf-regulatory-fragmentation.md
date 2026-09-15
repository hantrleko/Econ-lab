---
title: "Regulatory Fragmentation"
authors: "Joseph Kalmenovitz; Michelle Lowry; Ekaterina Volkova"
year: "2025"
venue: "Journal of Finance 80(2)"
doi: "10.1111/jofi.13423"
method: "other"
slug: "2025-jf-regulatory-fragmentation"
source_file: "uploads/jofi.13423_da5e.pdf"
status: "carded-from-first14pp"
---

# Kalmenovitz, Lowry, and Volkova (2025) — 多部门管同一件事的成本

文本度量 + 企业结果。DOI 在 PDF 第 1 页。前 14 页没有可独立引用的回归弹性。

## 问题

- 研究问题（一句）：多个联邦机构共管同一议题（监管碎片化）会不会抬高企业成本、压低生产率、利润和增长？更伤人的是规则打架，还是规则重复？
- Estimand：企业层面碎片化指标与成本/生产率/进入退出的条件相关，不是一个干净的政策 DID。

## 识别

- 策略：Federal Register 全文（1994 起）+ LDA 分成 100 个主题，算每个主题在机构间的碎片化，再按企业文本权重加总。拆 redundancy vs inconsistency。对照「监管文本页数」。
- 关键假设：LDA 主题和机构—企业匹配抓住的是真实监管重叠，而不是行业差本身。
- 最危险威胁：差行业会被写更多规则（内生）；没有清晰外生冲击写在前 14 页。作者用过一些对照（Tobin's Q、现金流、同行业不同碎片化），但仍是条件相关。

## 数据

- 观察单元 / 时间：企业 × 年；FR 自 1994
- 来源：联邦公报全文；企业财务。数据页：http://www.evolkova.info/data/fragmentation/（PDF 脚注写出）
- 处理与结果：无外生处理；结果 = 成本、生产率、盈利、增长、进入、小企业退出
- 样本限制：能和 FR 文本对上的美国企业

## 主结果

- 表/图号：前 14 页未钉 → UNVERIFIED
- 点估计：引言定性——碎片化高的企业成本更高，生产率、盈利、增长更低；抑制进入、提高小企业退出。这些效应来自冗余，**更主要来自机构间不一致**。时间上多数企业碎片化在降，但住房等主题在升。具体弹性 UNVERIFIED。
- 作者解释：监管负担不只是「规则有多少页」，还有「多少个衙门说的话打架」。

## 可攻击点

- 识别：缺少准实验时不要写成监管因果
- 测量：LDA 主题数、企业和文档匹配会改排序
- 外部有效：只覆盖联邦公报，没有州监管和执法强度
- 表文：摘要的因果动词强于识别

## 可复用设计

- 能偷：把「监管数量」拆成「冲突 vs 重复」
- 不该偷：在没有冲击时把系数写成「碎片化的因果成本」

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13423 | PDF p.1 | 已核 PDF |
| 碎片化提高成本、降低生产率/增长；inconsistency 更重要 | 摘要 | 已核 |
| 回归幅度 | 结果表 | UNVERIFIED |

## 对我的训练价值

- 练到了哪一层：文本测度，识别偏弱
- 下一步 skill：无
