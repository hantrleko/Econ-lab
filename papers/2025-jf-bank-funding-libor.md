---
title: "Bank Funding Risk, Reference Rates, and Credit Supply"
authors: "Harry Cooperman; Darrell Duffie; Stephan Luck; Zachry Wang; Yilin (David) Yang"
year: "2025"
venue: "Journal of Finance 80(1)"
doi: "10.1111/jofi.13411"
method: "other"
slug: "2025-jf-bank-funding-libor"
source_file: "uploads/jofi.13411_6b3b.pdf"
status: "carded-from-first14pp"
---

# Cooperman et al. (2025) — 信贷额度、LIBOR 和债务积压

理论 + 监管微观数据。观点不代表纽联储。DOI 在 PDF 第 1 页。

## 问题

- 研究问题（一句）：压力时期企业狂提授信，银行股东的债务积压如何抑制信贷供给？从 LIBOR 换成无风险参考利率会不会加重？
- Estimand：模型里提款对资金成本、承诺规模、提款量的影响；LIBOR→SOFR 的比较静态。

## 识别

- 策略：不是准实验。用 FR 2052a、Y-14Q 等看提款和资金；模型把债务积压楔子定进授信定价。
- 关键假设：压力下提款升；若资金不回流成存款，就要用更贵批发融资；LIBOR 的信用敏感性能部分对冲。
- 最危险威胁：GFC 与 COVID 提款后资金去向不同（作者强调 COVID 时钱常留在本行），外推 LIBOR-SOFR 不能只用一个危机。

## 数据

- 观察单元 / 时间：约 20 家主样本银行；2019 年底截面 + 危机事件
- 来源：FR 2052a、Y-14Q、FR 2416、Y-9C / call reports（保密微观 + 公开）
- 处理与结果：无随机处理；结果 = 资金结构、提款、参考利率
- 样本限制：压力测试报告行，不是全体商业银行

## 主结果

- 表/图号：Table I 为 2019-12-31 存款/批发资金分解
- 点估计：模型：把该行为定价进新发放额度，已提款信贷预期成本约 +15 bps，承诺总额约 −6%，预期提款约 −3%（引言）。2019 年底美国银行对公贷款超 70% 参考 LIBOR（脚注）。
- 作者解释：无风险参考利率可能加重摩擦；若提款留在本行存款，则对冲。

## 可攻击点

- 识别：15bps/6%/3% 是模型不是回归 LATE
- 测量：LCR「关系存款」分类
- 外部有效：20 家大行
- 表文：不要把模型比较静态写成「SOFR 已经减少了信贷」

## 可复用设计

- 能偷：同一张授信，问「提款后钱是否还在本行」；危机对照（GFC vs COVID）
- 不该偷：用加总贷款变化当 LIBOR 改革的因果

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13411 | PDF p.1 | 已核 PDF |
| +15bps / −6% / −3% | 引言模型 | 已核引言，模型不是表 |

## 对我的训练价值

- 练到了哪一层：机制叙事 vs 数据描述
- 下一步 skill：无
