---
title: "The impact of prices on analyst cash flow expectations: Reconciling subjective beliefs data with rational discount rate variation"
authors: "Aditya Chaudhry"
year: 2025
venue: Journal of Financial Economics 171
doi: 10.1016/j.jfineco.2025.104095
method: IV
slug: analyst-cf-from-prices
source_file: uploads/1-s2.0-S0304405X25001035-main_3061.pdf
status: carded-from-first14pp
---

# The impact of prices on analyst cash flow expectations: Reconciling subjective beliefs data with rational discount rate variation

文章编号 104095。开放获取 CC BY-NC-ND。Roussanov 编辑。NSF DGE-1746045；观点不代表 NSF。Pavlova 与 Sikorskaya 提供数据。只根据 PDF 前约 14 页。对照 `references/methods/iv.md`。

## 问题

分析师现金流预期跟着价格走、预测误差可预测、负向预测收益，是不是就能否掉「投资者理性、贴现率驱动价格」。价格本身会不会反过来改分析师预期。

## 识别

两个价格工具，要的是与现金流消息无关的价格。(1) Russell 重组的基准强度（BMI）变化，Pavlova–Sikorskaya（2023）：用 5 月市值定 1000/2000 切断，避开 6 月选择；Ben-David 等（2019）方法近似 Russell 市值。(2) 基金流诱导交易（FIT），Lou（2012），避开 Wardlaw（2020）对 Edmans 构造的批评。对照 `iv.md`：排他是「指数流/机械再平衡不通过未来盈利进分析师预测」。作者称 BMI 不预测盈利、价格冲击会反转。最危险：指数纳入仍有治理/真实效应；FIT 的流仍可能沾基本面。

## 数据

股票截面分析师 LTG 与 1–4 年 EPS。BMI 只在切断点附近；FIT 覆盖基金持仓股。

## 主结果

工具化的 1% 涨价：LTG 大约升 5 bp；1–4 年 EPS 预期和预测误差大约升 20–40 bp（BMI 约 40 bp，FIT 约 20 bp，作者称两者无统计差别）。大约解释价格与预期/误差协方差的一半。模型：理性投资者有私有信息，分析师误把贴现率推进价格当成现金流信号。点估计表号在后文。

## 可攻击点

- Russell / 流工具的排他文献本身有争议。
- 解释的是分析师，不是投资者信念。
- 「一半协方差」和模型匹配是作者计算。
- 不要写成「已证明投资者理性」。

## 可复用设计

信念数据先问：价格是不是进了分析师的信息集。工具要明确是噪声交易而不是现金流。两套工具同向才报。IV 卡。可跑识别审计。

证据指针：摘要（价格推高预期、部分和解理性模型）；引言（1% → LTG 5 bp、EPS 20–40 bp、一半协方差）。

训练价值：主观信念和理性贴现率能否共存。优先识别审计。
