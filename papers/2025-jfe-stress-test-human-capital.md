---
title: "Bank stress testing, human capital investment and risk management"
authors: "Thomas Schneider, Philip E. Strahan, Jun Yang"
year: 2025
venue: Journal of Financial Economics 171
doi: 10.1016/j.jfineco.2025.104104
method: panel / staggered
slug: stress-test-human-capital
source_file: uploads/1-s2.0-S0304405X25001126-main_fad0.pdf
status: carded-from-first14pp
---

# Bank stress testing, human capital investment and risk management

文章编号 104104。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。前 14 页未见编辑名。

## 问题

危机后银行有没有真的加风险管理人力资本。压力测试是扩大了量化风控，还是只为通过考试进人。大行是不是因为「太大不能倒」更少招风控。

## 识别

Lightcast 在线招聘当劳动需求。NLP 把「风险管理」岗位里真正要量化/分析技能的部分拆成运营、技术、放贷、合规、资本监管。描述：控趋势后，最大银行风控技能需求大约比小行低 30%；小行对过去波动加招，大行几乎不。压力测试：进进出出的名单和考试结果提供银行内时间变异；作者用银行 FE 和趋势。对照 `did.md`：错时进入，前 14 页未见现代估计量。作者承认反向因果（风控强的更易过关）会减弱「挂科→加人」。最危险：被测银行本来就大、本来就在建模型和数据仓库。

## 数据

Lightcast，2010–2021。银行风控相关招聘从大约 2.6 万条到超过 16.7 万条。压力测试相关岗位不到全部风控技能需求的 10%。

## 主结果

作者称从未测和曾经测的银行，风控技能占总招聘的水平和趋势相近，但技能结构不同：未测偏放贷和合规，被测偏技术和资本监管。预期下轮要考、以及挂科后，压力测试专项进人增加；其余 90% 以上风控需求不动。点估计表号在后文。

## 可攻击点

- 招聘不是入职，更不是风险下降。
- 错时 TWFE 可能负权重。
- 「30% 更少」是最简相关，不是 TBTF 实验。
- 不要写成「压力测试无效」的政策判决。

## 可复用设计

监管评估用招聘文本看「在招什么技能」，不要只看高管或董事会。把应试技能和其余风控拆开。错时必须现代估计量。弱 DID / 描述卡。

证据指针：摘要（只在考前和挂科后、90% 以上不动）；引言（6 倍招聘、大行 −30%、<10% 应试岗）。

训练价值：压力测试改变的是考试劳动还是风控。错时要打。
