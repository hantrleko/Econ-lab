---
title: "Central bank liquidity reallocation and bank lending: Evidence from the tiering system"
authors: "Carlo Altavilla, Miguel Boucinha, Lorenzo Burlon, Mariassunta Giannetti, Julian Schumacher"
year: 2025
venue: Journal of Financial Economics 168
doi: 10.1016/j.jfineco.2025.104058
method: DID
slug: ecb-tiering-reserves
source_file: uploads/1-s2.0-S0304405X25000662-main_abdd.pdf
status: carded-from-first14pp
---

# Central bank liquidity reallocation and bank lending

文章编号 104058。开放获取 CC BY。Schnabl 编辑。观点不代表欧央行或欧元体系。Giannetti：Wallander / Hedelius、Riksbankens Jubileumsfond。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

央行准备金是更多信贷还是挤出信贷。关键是总量，还是准备金在银行间的分配。把 1 欧元准备金挪到事前准备金少的银行，信贷供给变多少。

## 识别

2019 年 10 月 30 日欧央行分层准备金：超额流动性最多 6 倍最低准备金免负利率。额度按最低准备金（存款规模）定，与银行事前超额准备金无关，因此「未用额度」银行边际回报上升，会去货币市场买准备金。处理：同一天对所有银行，强度是未用额度。对照是额度已用满、事前准备金高的银行。信贷需求用企业–时间固定效应（Khwaja–Mian）或行业–地区–规模–时间。作者称高准备金银行已饱和，转出准备金时不减贷、不加价，所以再分配提高总供给。同期还有 2019-09-12 降息（DFR −0.40% 到 −0.50%）、APP、TLTRO；2019-03-27 Draghi 已放风。这是同期强度 DID，不是错时；仍要事前趋势。聚类应对银行或政策赋值层。

## 数据

Anacredit：2018 年 9 月–2020 年 2 月，122 家银行、2,624,856 家企业、3,439,580 个银行–企业关系，19 国。贷款门槛 2.5 万欧元。IBSI 银行资产负债表；MMSR 货币市场（约 50 家大行）。

## 主结果

未用额度银行在货币市场净借入增加，且未付更高利率或被期限配给；高流动性银行更多地把钱借给它们。这些银行减持证券、增加信贷，利率更低、期限更长。作者估：1 欧元准备金挪到事前准备金低的银行，信贷供给大约多 15 欧分。高融资成本、低资本、高 CDS 的未用额度银行驱动结果；承诺信贷额度升、国债持有降。作者称未见明显把钱贷给更风险的借款人。无未用额度的银行（含高准备金、分层节省多的）信贷政策不变。

## 可攻击点

- 分层与降息、前瞻指引同一天，未用额度可能和「更依赖存款/NIRP」捆在一起。
- 3 月放风后股票跳了约 3%，10 月生效前可能已调组合。
- 「转出银行不减贷」是饱和假设；若它们本会加贷，15 欧分是再分配不是净创造。
- 样本只到 2020 年 2 月，疫情前短窗。
- 前 14 页未见现代连续处理估计量；强度 DID 的 TWFE 解释要小心。

## 可复用设计

QE/QT 论文把「总量」和「谁持有准备金」分开。用与事前准备金无关的豁免额度当强度，再用企业–时间 FE 挡需求。同时报货币市场价量、证券和贷款三张表。15 欧分是再分配 LATE，不要写成任意创造 1 欧元准备金的乘数。

证据指针：摘要（约 15 欧分）；引言（未用额度、KM FE、转出银行不减贷）；第 3 节（2019-03-27 放风、09-12 决定、10-30 生效、6 倍 MRR）。

训练价值：准备金分配的同期强度 DID。优先识别审计对象。
