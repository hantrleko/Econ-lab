---
title: "Financial constraints and the racial housing gap"
authors: "Arpit Gupta, Christopher Hansman, Pierre Mabille"
year: 2025
venue: Journal of Financial Economics 173
doi: 10.1016/j.jfineco.2025.104142
method: bunching + DID + structural
slug: racial-housing-fha
source_file: uploads/Financial-constraints-and-the-racial-housing_2025_Journal-of-Financial-Econo_4ab6.pdf
status: carded-from-first14pp
---

# Financial constraints and the racial housing gap

文章编号 104142。Whited 编辑。Zillow、Infutor。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

首付约束会不会把黑人家庭挡在高机会地区，从而维持种族财富差距。放松或收紧 FHA 贷款上限，购房和区位怎么变。

## 识别

两套简约：① bunching——黑人借款人更堆在 FHA 贷款上限（3.5% 首付 vs 常规约 20%，上限按县年设定）。② 2014 年危机期临时高上限回撤：高房价地区首付骤升，低房价地区几乎不变。DID：受影响地区黑人新发放按揭份额大约 −8%；作者称未转向租赁，黑人人口下降。结构：两地区重叠世代，用该弹性校准，再反事实改按揭准入和住房供给。最危险：2014 回撤与房价/信贷周期同动；「未预期」是作者判断。前 14 页未见现代错时估计量（这次更接近同期政策）。

## 数据

按揭与区位（Zillow、Infutor 等，细节后文）。FHA 县年上限。模型匹配收入、自有率、迁移；未瞄准的杠杆和财富差距：作者称匹配杠杆，并解释财富差距 75% 以上。

## 主结果

简约：黑人更堆在上限；2014 后受影响地区黑人新发放大约 −8%。模型：改善高机会区的按揭准入和住房供给，比只推自有住房更能缩小种族财富差距。点估计表号在后文。

## 可攻击点

- −8% 是份额不是人数；对照是低房价地区，不是随机未回撤。
- bunching 是约束更紧的描述，不是种族歧视的判决。
- 模型里两组的初始财富、收入、出生地不同，反事实混了历史差距。
- 不要把「首付」写成种族差距的唯一机制。

## 可复用设计

空间错配用监管贷款上限做 bunching + 上限回撤 DID。结构模型用同一弹性校准。自有住房和「住进高机会区」分开报。优先识别审计（简约段）。

证据指针：摘要（bunching + DID、空间错配）；引言（2014 回撤、黑人新发放大约 −8%、模型解释财富差距 >75%）。

训练价值：监管上限与种族住房。优先识别审计。
