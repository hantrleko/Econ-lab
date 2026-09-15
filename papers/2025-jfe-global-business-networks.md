---
title: "Global Business Networks"
authors: "Christian Breitung, Sebastian Müller"
year: 2025
venue: Journal of Financial Economics 166
doi: 10.1016/j.jfineco.2025.104007
method: text / embedding
slug: global-business-networks
source_file: uploads/1-s2.0-S0304405X25000157-main_b6ed.pdf
status: carded-from-first14pp
---

# Global Business Networks

开放获取 CC BY-NC-ND。网络和描述放在 www.global-business-networks.com。只根据 PDF 前约 14 页。

## 问题

没有统一的全球同行/客户/供应商图时，怎么从文本给 6 万多家、67 国公司建时变商业网络，并用来看股票领先滞后和并购标的。

## 识别

测度论文，不是因果设计。用 GPT-3 生成历史业务描述，再用 OpenAI embedding 连边。作者遮住公司特定细节，减轻 embedding 训练截止日期带来的前瞻偏差；另微调开源模型，试图区分竞争、供应商、客户。展示应用（领先滞后、并购预测）是相关，不是处理效应。

## 数据

63,000+ 家上市公司、67 国。描述来自年报（美国 EDGAR 10-K、国际 LSEG），GPT-3 生成后用 OpenAI embedding 做余弦相似，超过 99 分位当连边。覆盖约 2000–2021：美国市值约 91.6%–99.8%，国际约 79.9%–98.3%。网络和描述公开。

## 主结果

网络能复现已知的全球股票领先滞后，并能帮助预测并购标的。美国情境感知组合七因子 alpha 约每月 119–146 个基点（TNIC 对照约 156）；全球最高约每月 281 个基点。这是新测度能用的证据，不是「网络导致回报或并购」。

## 可攻击点

- GPT 生成的「历史」描述仍可能泄漏事后知识，遮住专名不等于去掉所有前瞻。
- embedding 空间里的近邻是语义相似，不一定是真实供应链。
- 开源微调区分关系类型，标签从哪来、错误率多少，前 14 页未给可核对数字。
- 网站公开网络便于跟，但不保证年度复现稳定。

## 可复用设计

用大模型做经济网络时，必须处理知识截止日期，并尽量把竞争/供/客分开，而不是只做余弦相似。展示应用要标明是预测/相关。不要把 embedding 近邻写成因果传导。

证据指针：摘要（63,000+、67 国、GPT-3、embedding、领先滞后与并购）；引言（遮住公司细节、微调开源模型、公开网站）。

训练价值：文本网络的前瞻偏差。测度卡，不当因果。
