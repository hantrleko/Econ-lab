---
title: "Differential access to dark markets and execution outcomes"
authors: "James Brugler, Carole Comerton-Forde"
year: 2025
venue: Journal of Financial Economics 171
doi: 10.1016/j.jfineco.2025.104086
method: DID / matching
slug: dark-pool-access
source_file: uploads/1-s2.0-S0304405X25000947-main_31c1.pdf
status: carded-from-first14pp
---

# Differential access to dark markets and execution outcomes

文章编号 104086，印在 171 卷。开放获取 CC BY。Roussanov 编辑。Cboe Australia 经纪商–场所成交数据。Comerton-Forde：CEPR 研究员、澳洲证监会经济顾问、Plato Partnership 学术顾问；挪威金融倡议资助。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

暗池能不能把高频/电子做市挡在门外。限制准入的券商暗池，成交后信息泄漏和逆向选择是不是更小。限制是不是因果。

## 识别

澳洲：交易所暗池不能限准入，券商暗池可以。成交层比较券商暗 vs 交易所暗。92% 在 NBBO 中点成交，没有方向，不能用有效价差。结果：成交后 500ms–30 分钟绝对中间价变动（泄漏）、买卖价差（逆向选择）。面板：股票和日期 FE。因果：样本内三家券商暗池因合规风险关停，不是因为市场份额或成交质量；关停后其客户的暗单只能去交易所暗池。把仍开着的券商暗成交，和关停券商转到交易所暗的成交，按股票、成交和订单簿匹配。作者称关停是外生。最危险：关停券商的客户本身更怕泄漏；匹配去不掉客户组成。

## 数据

澳洲股票全部暗成交，2017-01-01 至 2019-09-30。ASX、Cboe 和 13 家券商暗池。

## 主结果

60 秒窗口，券商暗相对交易所暗，绝对价格变动大约少 1 bp。关停匹配后方向相同。完全禁止高频的券商池，比允许客户选择退出高频的池泄漏更小。交易所暗成交后，亮市更活跃、失衡更大、报价成交比更低。作者称限制准入是用成交概率换更少泄漏。点估计表号在后文。

## 可攻击点

- 只有三次关停，独立变异少。
- 「合规关停」仍可能和客户质量同动。
- 1 bp 是条件于成交，不含未成交风险。
- 作者与监管/行业有顾问关系。

## 可复用设计

暗池不要当同质。用能看见场所的成交层数据，结果用无方向的绝对价格变动。关停当路由外生。同时报成交质量和成交概率的权衡。可跑识别审计。

证据指针：摘要（限制更少泄漏、关停证明因果）；引言（−1 bp / 60s、三次关停）。

训练价值：准入限制如何改暗池执行。优先识别审计。
