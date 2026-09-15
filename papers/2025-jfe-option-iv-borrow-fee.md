---
title: "Why does options market information predict stock returns?"
authors: "Dmitriy Muravyev, Neil D. Pearson, Joshua M. Pollet"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104153
method: predictability
slug: option-iv-borrow-fee
source_file: uploads/1-s2.0-S0304405X25001618-main_472a.pdf
status: carded-from-first14pp
---

# Why does options market information predict stock returns?

文章编号 104153。开放获取 CC BY。Roussanov 编辑。Canadian Derivatives Institute；Markit 借券数据。Muravyev 现密歇根州大。只根据 PDF 前约 14 页。

## 问题

隐含波动率价差、偏度等期权变换能预测股票收益，是不是因为它们代理了已知能预测收益的借券费，而不是股价对期权信息反应慢。

## 识别

不是实验。泰勒展开：忽略借券费算出的 IV 价差与借券费成比例。检验：剔除年借券费 >1% 的股票、或把收益扣掉借券费后，价差/偏度多空还剩多少。可预测卡，不当因果。

## 数据

2006–2020。期权 IV 来自按零借券费计算的供应商数据（引言写 OptionMetrics 一类）。借券费 Markit。

## 主结果

价差十分位多空原始或 DGTW 大约 64–66 bp/月；偏度更弱。预测力集中在要做空的最低十分位。剔除高费股票（约 11% 样本）后，第一十分位异常收益掉到原来的十分之一以下且不显著；多空至少掉三分之二。扣费后同样大幅变弱。其他期权预测变量扣费后多空也不显著。点估计表号在后文。

## 可攻击点

- 「至少掉三分之二」依赖 1% 年费切分，切分是作者选的。
- 高费股同时难借、难卖空、波动大，剔除不是只拿掉借券费这一维。
- 公式针对同执行价价差；偏度和其他矩是间接代理。
- 不要写成「期权没有信息」，只是这条可预测通道被借券费吃掉很多。

## 可复用设计

凡用 OptionMetrics 式零费率 IV 做预测，先和借券费对一下，并报扣费/剔高费后的多空。把限卖空同时写成套利障碍和信号来源。

证据指针：摘要（至少掉三分之二）；引言（64–66 bp、剔 11% 高费股）。

训练价值：可预测的测度错误。不当准实验。
