---
title: "Resilience in collective bargaining"
authors: "Carlos F. Avenancio-León, Alessio Piccolo, Roberto Pinto"
year: 2025
venue: Journal of Financial Economics 173
doi: 10.1016/j.jfineco.2025.104157
method: staggered DID
slug: rwl-bargaining-resilience
source_file: uploads/Resilience-in-collective-bargaining_2025_Journal-of-Financial-Economics_d172.pdf
status: carded-from-first14pp
---

# Resilience in collective bargaining

文章编号 104157。Papanikolaou 编辑。版权保留。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

集体谈判里，扛得住拖延（韧性）往往是私有信息。企业会不会在谈判前主动改财务结构来提高韧性。工作权法（RWL）削弱工会后，企业和工会的财务怎么动。

## 识别

理论：把违约期限写进 Rubinstein 讨价还价；期限越长越扛得住罢工，工资越低；杠杆一边抽走可分剩余、一边缩短韧性，符号不定。经验：2011 年后五州错时通过 RWL，总部在立法州的企业相对未立法州。企业+行业–年 FE，标准误聚在州。动态 DID 用 Sun–Abraham (2021)。样本跟 Fortin et al. (2023)，去掉 2007 年前已有 RWL 的州。最危险：RWL 州同时改产业/信贷；总部州不等于谈判州。作者报债务定价不动、现金/存货不是主通道。

## 数据

Compustat 企业债务期限与杠杆。罢工：BLS 千人以上停工 1993–2019，图 1 用 57 次、平均 20 天。工会财务：劳工部 OLMS LM-2/LM-3，717 个组织。

## 主结果

RWL 后长期债（>5 年）占比大约 −2.0 至 −2.3 个百分点（表 3 无条件）；韧性的期限分量显著下降。杠杆无条件大约 −3 pp、条件后不显著。工会化行业、罢工更贵的企业期限降得更多。大工会提高人均会费、总会费上升；小工会加杠杆。点估计见表 3。

## 可攻击点

- 处理在州、结果在总部企业，谈判可能在工厂州。
- 只有五州立法，聚类 28 州；外推窄。
- 主回归仍是 TWFE；Sun–Abraham 用在动态图，不是主表。
- 不要把「期限缩短」写成「工会变弱所以企业变穷」：作者解释是韧性需求下降。

## 可复用设计

谈判韧性用期限，不要只用杠杆。错时劳动法报 Sun–Abraham 事件研究，聚类对立法州。工会侧同时报会费和人数。可跑识别审计。

证据指针：摘要（企业改韧性、工会财务也动）；表 3（期限 −0.020/−0.023）；引言（Sun–Abraham、五州 RWL）。

训练价值：错时劳动法 + 财务结构。优先识别审计。
