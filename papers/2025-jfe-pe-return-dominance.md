---
title: "The return of return dominance: Decomposing the cross-section of prices"
authors: "Ricardo Delao, Xiao Han, Sean Myers"
year: 2025
venue: Journal of Financial Economics 169
doi: 10.1016/j.jfineco.2025.104059
method: return decomposition
slug: pe-return-dominance
source_file: uploads/1-s2.0-S0304405X25000674-main_889e.pdf
status: carded-from-first14pp
---

# The return of return dominance: Decomposing the cross-section of prices

文章编号 104059。开放获取 CC BY。Papanikolaou 编辑。只根据 PDF 前约 14 页。

## 问题

截面市盈率差，有多少会在未来收益里实现，有多少在未来盈利增长里实现。价值溢价模型能不能对上这个分解。账面市值比和未来盈利能力的旧结果，是不是把「当前盈利水平」当成了「未来增长」。

## 识别

会计分解，不是因果。组合层用 Campbell–Shiller 变体；公司层新分解，能处理负盈利。样本：NYSE/AMEX/NASDAQ 普通股，1963–2020。作者用会计恒等式说明：账面市值比与未来盈利能力的相关，几乎来自当前盈利/账面。VAR 把 15 年窗口延到无限期。对比六类价值溢价模型。

## 数据

美国股票 1963–2020。组合与个股。

## 主结果

市盈率截面差：约 75% 对应未来收益差，约 25% 对应未来盈利增长。组合和个股类似。多数标准模型（增长期权、资本不可逆、久期、外推过度自信）预测增长解释 90% 以上，对不上。长期风险暴露差异或缓慢学习参数的模型更接近。长期几乎没有增长差，被作者当作长期收益可预测的新证据。收益意外的截面也是预测收益主导。

## 可攻击点

- 75/25 依赖窗口、盈利定义和 VAR。
- 「贴现率或错价」在分解里分不开。
- 模型「对不上」是作者选的六个，不是全部模型。
- 不是交易策略收益，不要写成价值溢价已被解释。

## 可复用设计

截面价格比先分解成未来收益 vs 未来盈利增长，再拿模型对这个份额，而不是只对短期多空。账面市值比要先扣掉当前盈利/账面。资产定价测度卡。

证据指针：摘要（75/25、模型、长期可预测）；引言（1963–2020、账面比旧结果是当前盈利水平）。

训练价值：把宏观「收益主导」搬到截面。不当因果。
