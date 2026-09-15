---
title: "The retail execution quality landscape"
authors: "Anne Haubo Dyhrberg, Andriy Shkilko, Ingrid M. Werner"
year: 2025
venue: Journal of Financial Economics 168
doi: 10.1016/j.jfineco.2025.104051
method: descriptive / DiD
slug: retail-wholesaler-execution
source_file: uploads/1-s2.0-S0304405X25000595-main_f09c.pdf
status: carded-from-first14pp
---

# The retail execution quality landscape

文章编号 104051。开放获取 CC BY-NC-ND。Papanikolaou 共同编辑。只根据 PDF 前约 14 页。

## 问题

美国散户单大多外包给批发做市商。市场很集中，监管担心价格改善几乎为零、PFOF 扭曲路由。批发商规模是省成本还是抬价。新进入者会不会压低执行成本。

## 识别

主文是描述：Rule 605 执行质量、Rule 606 路由和 PFOF。跨批发商比执行成本要用毒性调整后的实现价差，因为各家接到的券商流毒性不同。进入段：Jane Street 2019 年 7 月进场，几个月内拿走超过 12% 散户流，作者做 DID。对照 `references/methods/did.md`：进入时点对全市场同时，处理强度是在位者规模被摊薄；不是随机进入。作者预期竞争加剧应降成本，结果成本升，解释为在位者失去规模经济。

## 数据

2019–2022 年主要批发商 Rule 605，覆盖 12,000+ 只 NMS 股票。Rule 606 看券商路由和 PFOF。

## 主结果

批发商价格改善约占报价价差的 27%；平均 S&P 500 股票约 51%。接受 PFOF 的券商，PFOF 约占价差 1%，且对所有批发商同一费率。两大批发商（Citadel、Virtu）约占散户流 70%，实现成本反而更低，作者称规模解释全部差距。TD Ameritrade 在 606 能估的流里超过 47%。Jane Street 进入后执行成本上升，不是下降。小票散户受益更大。Fidelity、Vanguard 不收 PFOF 仍大量路由给批发商。

## 可攻击点

- 605/606 是监管披露，不是随机实验；「规模全部解释差距」是会计分解。
- Jane Street DID：进入与 2019–2020 市场结构、散户潮同动。
- 毒性调整依赖实现价差窗口，换窗口可能改排名。
- 不能直接证伪「大户在谈判里拿定价权」。

## 可复用设计

比批发商不要只用价格改善，先固定券商流或改用实现价差。PFOF 若对所有批发商同费率，路由激励要另找。进入事件先写预期符号，再报相反结果。描述卡；Jane Street 段可当弱 DID 练习，不当政策因果。

证据指针：摘要（规模节约、进入后成本升、小票受益最大）；引言（27% / 51% / 1% PFOF、两大约 70%、Jane Street >12%）。

训练价值：集中度是效率还是势力。零售微观结构描述卡。
