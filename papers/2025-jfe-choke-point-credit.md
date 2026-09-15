---
title: "Defunding controversial industries: Can targeted credit rationing choke firms?"
authors: "Kunal Sachdeva, André F. Silva, Pablo Slutzky, Billy Y. Xu"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104133
method: staggered DID
slug: choke-point-credit
source_file: uploads/1-s2.0-S0304405X25001412-main_1b29.pdf
status: carded-from-first14pp
---

# Defunding controversial industries: Can targeted credit rationing choke firms?

文章编号 104133。开放获取 CC BY-NC。Schnabl 编辑。Y-14Q 监管贷款。观点不代表美联储理事会。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

司法部「掐点行动」逼一部分银行切断弹药、烟草、约会、色情、网络赌博等合法但有争议行业。被点名的银行少贷、断关系之后，企业能不能换到未被点名的银行。总体信贷、投资和业绩会不会动。

## 识别

掐点行动分批点银行，作者称法院文件和回归显示点名不按对这些行业的贷款量，也和多种银行/企业特征无关。错时动态 DID；稳健用 stacked（Gormley–Matsa / Baker 等）。企业–时间 FE 做 Khwaja–Mian，看多银行企业。安慰剂：未点名行业、现金密集行业、随机时点。对照 `did.md`：错时已报 stacked。最危险：点名仍可能和银行合规能力同动；Y-14Q 只覆盖资产 ≥500 亿美元、承诺 >100 万美元。

## 数据

美联储 Y-14Q 公司贷款季报，上市和未上市。

## 主结果

被点名银行对中小企业承诺信贷大约少 10%；大企业不动。提款比例几乎不变。关系更多被点名银行终止，新关系开在未点名银行。平均企业总信贷、杠杆、利润、投资无显著变化；高杠杆中小企业总承诺略降，大而盈利的企业总承诺还升。作者称定点断贷大体无效。点估计表号在后文。

## 可攻击点

- 监管样本没有社区银行，替代可能被高估。
- 「不按贷款量点名」是作者检验，不是随机。
- 10% 是被点名银行对中小企业，不是企业总信贷。
- 与煤炭退出那张并排：行业和资本密度不同，不要混成一条政策结论。

## 可复用设计

定点断贷必须同时报：被点名银行少贷、关系切换、企业总信贷和真实结果。错时用 stacked。多银行企业加企业–时间 FE。可跑识别审计。

证据指针：摘要（少贷但大多换得成、业绩不动）；引言（中小企业 −10%、stacked、KM）。

训练价值：信贷抵制有没有真实效果。优先识别审计。与煤炭退出并排。
