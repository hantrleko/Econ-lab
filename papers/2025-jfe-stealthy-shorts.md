---
title: "Stealthy shorts: Informed liquidity supply"
authors: "Amit Goyal, Adam V. Reed, Esad Smajlbegovic, Amar Soebhag"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104155
method: predictability
slug: stealthy-shorts
source_file: uploads/1-s2.0-S0304405X25001631-main_c24c.pdf
status: carded-from-first14pp
---

# Stealthy shorts: Informed liquidity supply

文章编号 104155。开放获取 CC BY。Roussanov 编辑。Cboe、Nasdaq、NYSE 成交层空头。Smajlbegovic：ERIM。Soebhag：Robeco Quantitative Investing。只根据 PDF 前约 14 页。

## 问题

空头知情，按教科书应是吃流动性。拆成流动性供给（LSS）和流动性需求（LDS）之后，哪一类预测未来收益。

## 识别

不是实验。十一家交易所成交匹配当时报价，Lee–Ready 一类规则拆主动/被动。可预测：高 LSS 股票随后收益更低。作者称做市和机会主义风险承担解释不了，更像知情者策略性挂单。不当因果。

## 数据

2014–2018 美国十一家主要交易所成交层空头。约 238 万股票–日。

## 主结果

只有 LSS 预测：最高 vs 最低五分位 21 日风险调整大约 −38 bp。LDS 同期大约 12 bp、不显著，且几乎全来自组合形成次日。横截面回归里 LSS 不被常见空头比率和其他预测变量吃掉。点估计表号在后文。

## 可攻击点

- 成交–报价匹配和买卖方向分类有误差，被动单可能混进知情吃单。
- 「知情」是事后收益预测，不是直接看到私有信号。
- Robeco 作者在量化投资；复制包能否覆盖交易所原始成交未核。
- 不要写成「所有空头都在做市」。

## 可复用设计

日度空头比率太粗。有成交层数据就拆供给/需求，再看消息日和异象组合。可预测卡。

证据指针：摘要（供给端更知情）；引言（LSS −38 bp / 21 日，LDS 12 bp）。

训练价值：空头可预测的微观拆分。不当准实验。
