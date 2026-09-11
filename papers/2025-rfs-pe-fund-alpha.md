---
title: "Risk-Adjusted Returns of Private Equity Funds: A New Approach"
authors: "Arthur Korteweg; Stefan Nagel"
year: "2025"
venue: "Review of Financial Studies 38(9)"
doi: "10.1093/rfs/hhae067"
method: "other"
slug: "2025-rfs-pe-fund-alpha"
source_file: "uploads/hhae067_6b1b.pdf"
status: "carded-from-first14pp"
---

# Korteweg and Nagel (2025) — 单只 PE 基金的 α，比 GPME 少吃现金流噪声

MSCI-Burgiss 数据；发表前 Burgiss 审过，防反推单基金。Korteweg 事后接过 VC 风险诉讼咨询/专家证人——写进卡头，不当识别。DOI 在 PDF 第 1 页。评估 PE 时不要只用 PME。

## 问题

- 研究问题（一句）：GPME 在资产类别平均上定价含义清楚，但对单只基金太吵，能不能做一个同期望、更少噪声的单基金 α？
- Estimand：不是因果。是单只基金相对基准组合的异常支付，并要求跨基金平均异常支付等于该类的 GPME。

## 识别

- 策略：测度，不是准实验。GPME 用校准过的 SDF 贴现现金流，期望定价误差为零，但实现值吃不下共同因子冲击。新 α：再加两条——现金流与基准支付联合对数正态、资产类别内常数 beta。用使平均异常支付 = GPME 且最小化跨基金方差的 beta，做基准组合通缩。
- 关键假设：类内 beta 相同且不随时间变；对数正态。作者称模拟里对合理偏离仍比 (G)PME 准。beta=1 时 α 接近 PME；beta 等于风险价格时 α 接近 GPME。
- 最危险威胁：类内 beta 其实在变（作者自己按时期、规模、VC 子类切开，beta 不同）；对数正态错了就会系统性偏。

## 数据

- 观察单元：基金现金流史。1,630 只 VC，1,073 只杠杆买断。
- 来源：MSCI-Burgiss Manager Universe，只从 LP 侧来，多 LP 交叉核对。
- 基准：基线 CAPM SDF / 市场组合；后文也加过 Fama–French 规模、价值组合。
- 样本限制：发表数字是汇总，单基金不可反推。

## 主结果

- VC：beta 2.37，相对 SDF 里市场风险价格 3.61；α 跨基金标准差大约比 GPME 低 30%。差别不大，因为 beta 已经接近风险价格。
- 买断：beta 0.91，风险价格 3.78；α 的跨基金 SD 大约低 65%。
- 规模回归：用 α 当因变量，标准误大约低 1/3 到 2/3。
- 持续性：买断上 α 预报后续基金更好；VC 上 GPME 略好。
- 双因子：VC 更载大盘成长而不是小盘成长；买断是离开小盘成长。Brown–Ghysels–Gredil 的买断 beta 大约 0.97–1.15，和这里 0.91 接近；他们的 VC beta 1.39–1.60，低于这里 2.37。

## 可攻击点

- 不是「PE 有没有 alpha」的因果设计，是噪声更小的绩效尺子。
- 类内常数 beta 被作者自己的子样本切开打脸；他们靠模拟说仍更准，前 14 页没有那些模拟表。
- Burgiss 是能被 LP 看到的基金，不是全市场。
- 利益：数据方发表前审查；作者事后做 VC 风险诉讼咨询。

## 可复用设计

- 先钉资产类别 GPME，再找使平均异常支付对齐、跨基金方差最小的 beta，不要直接对单基金套 PME。
- 买断和 VC 分开报：beta 离风险价格越远，GPME 越吵。
- 用规模回归标准误、后续基金可预测，当「尺子有没有用」的规格检验，不当第二条故事。
- 评估 PE 业绩或持续性时，至少并行 PME / GPME / 这个 α。

## 证据指针

- 新 α、同 GPME 总体含义、买断上 PME 与 α 接近但子样本会偏：PDF 第 1 页摘要。
- 1,630 VC / 1,073 LBO、VC beta 2.37 vs 3.61、SD −30%：PDF 第 4 页。
- 买断 beta 0.91 vs 3.78、SD −65%、规模回归 SE、持续性：PDF 第 5 页。
- Burgiss 预审、Korteweg 诉讼咨询：PDF 第 1 页脚注。

## 训练价值

没有识别审计对象。写 PE 绩效时当方法卡用：尺子选错，持续性回归会被噪声吃掉。
