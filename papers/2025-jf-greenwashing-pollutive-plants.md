---
title: "Sustainability or Greenwashing: Evidence from the Asset Market for Industrial Pollution"
authors: "Ran Duchin; Janet Gao; Qiping Xu"
year: "2025"
venue: "Journal of Finance 80(2)"
doi: "10.1111/jofi.13412"
method: "DID"
slug: "2025-jf-greenwashing-pollutive-plants"
source_file: "uploads/jofi.13412_f0fc.pdf"
status: "carded-from-first14pp"
---

# Duchin, Gao, and Xu (2025) — 卖污染工厂算不算漂绿

主分析是选择模型 + 工厂-化学品 DID。作者承认出售非随机。DOI 在 PDF 第 1 页。

## 问题

- 研究问题（一句）：企业迫于环境压力卖掉污染工厂后，污染降了没有，卖家是否只是在 ESG 叙事和评级上获益？
- Estimand：环境压力 → 出售概率；出售后工厂污染相对未出售工厂的变化。

## 识别

- 策略：(1) 环境压力指数与出售选择；(2) 工厂-化学品 Poisson DID，对照未出售工厂；(3) 准外生环境风险事件后的出售，看事前趋势。
- 关键假设：DID 对照工厂构成反事实；事件后出售更接近外生。
- 最危险威胁：卖「治不了」的厂、买「能接着排」的厂（选择）；错时出售用普通 TWFE（作者引了 Baker et al.）。对照 did.md：处理时点不同，要当心。

## 数据

- 观察单元 / 时间：污染工厂 / 工厂-化学品；具体年份前 14 页未钉 → UNVERIFIED
- 来源：有毒物质排放 + 交易 + ESG / 电话会文本（细节以数据节为准）
- 处理与结果：处理 = 出售污染资产；结果 = 排放、减排努力、卖方电话会话术、收益、ESG、合规成本
- 样本限制：能匹配买卖双方工厂的交易

## 主结果

- 表/图号：引言；具体回归表号 UNVERIFIED
- 点估计：环境压力综合指数 +1SD → 出售概率相对样本均值 +54%。有毒排放四分位距 ↑ → 出售概率 +2.3pp（样本均出售概率 1.9pp）。买方更常是私有（+5.5pp）、无 ESG 覆盖（+4.7pp）、共和党县总部（+5.4pp）。出售后工厂污染 DID 与未出售无显著差异；买卖合计污染也不降。
- 作者解释：资产市场让企业重画边界，看起来绿，污染没实质下降，但有交易收益。

## 可攻击点

- 识别：出售选择；DID 对照
- 测量：有毒释放 vs 真实环境损害
- 外部有效：美国工业
- 表文：「without real consequences for pollution」取决于排放测度

## 可复用设计

- 能偷：压力 → 谁卖给谁（压力更弱的买方）；工厂级 DID + 双方合计排放
- 不该偷：把 ESG 上升写成减排

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13412 | PDF p.1 | 已核 PDF |
| +54% 出售；污染 DID 为零 | 引言 | 已核引言 |

## 对我的训练价值

- 练到了哪一层：DID + 选择
- 下一步 skill：identification-audit
