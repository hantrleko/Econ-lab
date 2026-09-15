---
title: "Regulatory leakage among financial advisors: Evidence from FINRA regulation of “bad” brokers"
authors: "Colleen Honigsberg, Edwin Hu, Robert J. Jackson Jr."
year: 2025
venue: Journal of Financial Economics 174
doi: 10.1016/j.jfineco.2025.104170
method: DID / rule definition
slug: advisor-regulatory-leakage
source_file: uploads/Regulatory-leakage-among-financial-advisors--Evidence_2025_Journal-of-Financ_488f.pdf
status: carded-from-first14pp
---

# Regulatory leakage among financial advisors

文章编号 104170。Whited 编辑。版权保留。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

被 FINRA 盯上的「坏经纪」退出后，是离开金融销售，还是漏到州保险牌继续卖年金。交叉注册普遍时，单监管退出算不算行业退出。

## 识别

两块。① 描述：合并 FINRA BrokerCheck、SEC/州 IAPD、州保险生产者；跟踪交叉注册与退出后去向。② 2018–2019 提案窗口：FINRA 拟议 Rule 1017(a)(7)（雇「指定风险事件」经纪须事先批准）和 Rule 4111（高纪律经纪扎堆的公司为「受限」、须留赔偿准备金）；2021 年大体按原文通过。处理时点用**提案日**（行业已提前解雇）。处理组：2018 年被规则定义点名的高风险经纪（4062 人，约 0.6%）。对照：同公司、同县、同年、相近资格，且多为保险交叉注册、也可能有不良记录，但不够「坏」。线性概率 + 公司–县–年 FE。不是随机审计。窗口短，更像水平 DID；前 14 页未见 stacked / Callaway–Sant'Anna。最危险：定义内生（点名已知问题群体）；同公司对照同受声誉冲击；保险牌多在退出前已办好，泄漏是存量通道。

## 数据

FINRA / SEC / 州保险合并。保险生产者超 200 万，FINRA 经纪超 100 万，SEC 投顾约 40 万，州投顾约 2 万。2012–2022 退出 FINRA 且未回的 456,906 人中，约 26.5% 仍在其他金融监管。

## 主结果

交叉注册：FINRA 经纪约 42% 另有牌；与保险交叉从 2012 年约 14% 升到 2022 年 35%。退出 FINRA 者中 79% 退出时已有保险牌。严重不当后：无交叉者退出概率 +1.6 至 +3.3 pp，有保险交叉者约 +36 pp。退出后仍做规划：约 92% 有年金牌、76% 有可变年金牌。2018 提案后被点名者相对对照更退出；作者称几乎全是保险交叉者，退出后 98% 现仍是保险生产者。点估计在摘要与引言。

## 可攻击点

- 「坏」的定义来自提案文本，处理=被点名，不是随机执法。
- 同公司对照可能同被清理。
- 未观测客户是否跟随、产品风险是否下降。
- 不要把「退出 FINRA」写成「退出金融」。

## 可复用设计

监管泄漏必须合并相邻牌照。对照用同公司同县压共同冲击。处理用规则文本谁被点名。可跑识别审计。

证据指针：摘要（>40% 交叉、退出者 79% 已有保险、提案后漏出、98% 仍是保险生产者）；引言（同公司同县对照、4062 人）。

训练价值：高。规则定义处理 + 泄漏。
