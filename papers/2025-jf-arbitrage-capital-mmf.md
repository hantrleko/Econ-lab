---
title: "Arbitrage Capital of Global Banks"
authors: "Alyssa G. Anderson; Wenxin Du; Bernd Schlusche"
year: "2025"
venue: "Journal of Finance 80(5)"
doi: "10.1111/jofi.13478"
method: "IV"
slug: "2025-jf-arbitrage-capital-mmf"
source_file: "uploads/The_Journal_of_Finance_-_2025_-_ANDERSON_-_Arbitrage_Capital_of_Global_Banks_2d20.pdf"
status: "carded-from-first14pp"
---

# Anderson, Du, and Schlusche (2025) — 全球银行的套利资本

IV / 监管冲击。DOI 在 PDF 第 2 页。美联储观点免责与 DTCC 数据致谢在第 1–2 页。

## 问题

- 研究问题（一句）：批发融资突然变贵时，全球银行先砍套利交易还是先砍贷款？
- Estimand：银行对 prime 货币市场基金无担保融资的事前暴露，如何映射到改革后套利头寸与贷款。

## 识别

- 策略：2016 年 10 月美国 prime MMF 改革，批发融资大约少 6,000 亿美元（2015-10 至 2016-10）。Bartik / shift-share：事前 prime MMF 无担保融资份额 × 改革后该类融资的总量收缩。
- 关键假设：份额由历史关系决定，改革后总量收缩对银行而言近似外生；份额不直接预测贷款需求。作者用 Goldsmith-Pinkham, Sorkin, and Swift (2020) 做 shift-share 诊断。
- 安慰剂/对照：2011–2012 欧债危机同类批发融资冲击（Basel III 流动性监管落地前）——那时贷款明显下降。日度监管数据避开季末窗口粉饰。

## 数据

- 58 家高评级全球银行。
- 日度监管报告，用来看季末粉饰之外的真实头寸。
- 只读前 14 页：具体监管表名在后文。

## 主结果

- 全球银行主要收缩依赖无担保融资的套利（IOER、CIP），贷款没有明显下降。
- 引言数量：prime MMF 无担保融资占资产的份额高 1 个百分点，潜在套利资本大约少 0.9%，IOER 套利代理大约少 0.8%；贷款系数不显著。
- 欧债危机同类冲击则伤贷款——作者用来说明「不是银行永远不砍贷款」，而是流动性监管之后套利垫了缓冲。

## 可攻击点

- Shift-share 的外生性在银行之间仍可能与商业模式相关（越依赖批发融资的银行，贷款客户也可能更批发）。
- 「贷款没降」取决于贷款定义（未提用承诺 vs 账面贷款）。
- 改革同时改变 MMF 行业结构，不只是价格。

## 可复用设计

- 监管冲击 + 事前份额是标准 Bartik；一定要做 Goldsmith-Pinkham 诊断，不要只报第一阶段。
- 日度数据打「季末粉饰」是批发融资论文的基本功。
- 找一个监管前的同类冲击当对照，能把「机制随制度变」讲清楚。

## 证据指针

- 6,000 亿美元：PDF 第 2 页。
- 0.9% / 0.8% / 贷款不显著：PDF 第 3 页。
- Goldsmith-Pinkham 诊断：PDF 第 3 页。
- 欧债对照：PDF 第 3 页。

## 训练价值

对照 `references/methods/iv.md`。监管 × 份额的 IV 课；写「银行惜贷」前先问砍的是套利还是贷款。
