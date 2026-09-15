---
title: "Do intermediaries improve GSE lending? Evidence from proprietary GSE data"
authors: "Joshua Bosshardt, Ali Kakhbod, Amir Kermani"
year: 2025
venue: Journal of Financial Economics 170
doi: 10.1016/j.jfineco.2025.104082
method: reduced-form + structural
slug: gse-intermediaries
source_file: uploads/1-s2.0-S0304405X2500090X-main_1edd.pdf
status: carded-from-first14pp
---

# Do intermediaries improve GSE lending? Evidence from proprietary GSE data

文章编号 104082。开放获取 CC BY。Schnabl 编辑。观点不代表联邦住房金融局或美国政府。只根据 PDF 前约 14 页。对照 `references/methods/iv.md`。

## 问题

两房已经给违约保险、自动审批之后，放贷中介再加 overlay 和自主定价，值不值。筛掉隐藏风险省的成本，能不能盖过加点。

## 识别

减式：同一贷款人、同一 ZIP，利率减去 g-fee 对可观察违约风险（信用分、LTV、DTI 预报的违约）。再看扣掉可观察风险后，净利率还能否预测违约。用 g-fee 交叉补贴和跳跃造成的固定利率变异，检验「利率本身导致违约」；作者称因果几乎为零。结构：有皮肤、有成本筛选、借款人少逛。反事实：两房标准接受的贷款按可观察风险零利润定价，中介不再自主筛和加点。不是随机去掉中介。

## 数据

2016–2017 两房收购的全部贷款，能精确看到当时 g-fee。申请端看即便自动审批通过是否仍被拒。NSMO 作购物和金融素养稳健。

## 主结果

可观察风险高 1 个百分点，净利率大约高 4.2 bp；最安全借款人均值与第 10 分位大约差 23 bp（第 90–10 大约 49 bp）。净利率高 1 个百分点，条件违约大约高 47 bp（样本违约约 50 bp）。可观察风险高 1 个百分点，即便两房已过，拒贷大约高 1.92 个百分点。结构：去掉筛选后违约大约增至三倍，但平均约 25 bp 加点更大；反事实下可观察风险最低（最高）一成的利率大约再低 23（22）bp。银行 vs 非银差异，作者更贴近皮肤不同而不是筛选质量。点估计表号在后文。

## 可攻击点

- 4.2 bp / 每月约 4.29 美元本息很小，故事主要靠加点。
- 反事实「平台化、去掉回购」不是实验。
- 违约「大约三倍」是模型。
- 样本只有 2016–2017，非银份额正在涨。

## 可复用设计

两房贷款先把 g-fee 抠掉，才能谈中介皮肤。减式同时报可观察风险定价、残差违约和拒贷。福利用「无中介」反事实，不要只骂 overlay。结构卡。

证据指针：摘要（筛 vs 加点、无中介利率更高）；引言（4.2 bp、47 bp、25 bp 加点、23/22 bp）。

训练价值：中介在保险式按揭里还剩什么。可与 169 卷英国菜单筛选并排，不当同一设计。
