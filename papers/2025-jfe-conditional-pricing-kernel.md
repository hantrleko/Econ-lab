---
title: "Conditional risk and the pricing kernel"
authors: "David Schreindorfer, Tobias Sichert"
year: 2025
venue: Journal of Financial Economics 171
doi: 10.1016/j.jfineco.2025.104106
method: option / density
slug: conditional-pricing-kernel
source_file: uploads/1-s2.0-S0304405X2500114X-main_4fa9.pdf
status: carded-from-first14pp
---

# Conditional risk and the pricing kernel

文章编号 104106。开放获取 CC BY。Papanikolaou 编辑。Sichert：Wallanders and Tom Hedelius / Tore Browaldhs Fh21-0026，Swedish House of Finance。只根据 PDF 前约 14 页。

## 问题

指数期权里，定价核和条件实物密度能不能一起估。低波动时同样的负收益是不是更「疼」。风险–收益权衡、Martin 股权溢价下界和方差溢价预测，还站不站得住。

## 识别

估计，不是准实验。风险中性密度从期权（Breeden–Litzenberger）。投影定价核用随波动变化的多项式，极大似然拟合实现收益。1990–2023，月度，主设定多项式阶 N=2。最危险：核的形状和波动绑定，识别靠参数；高波动期期权深度虚值更噪。

## 数据

股指期权与收益。图 1：波动第 10 与第 90 分位的投影核，块 bootstrap 21 个交易日。

## 主结果

月收益 −10%：低波动时边际效用大约 3.68，高波动时大约 1.32。波动高 1 个标准差，期望收益大约年化高 3.8 个百分点；对数线性或时不变核被 1% 水平拒绝。偏度更负 1 个标准差，期望收益大约年化高 1 个百分点。高波动（2008、2020）时 Martin（2017）负相关条件破，下界高估危机溢价。点估计表号在后文。

## 可攻击点

- 3.68 / 1.32 依赖多项式和样本。
- 「宏观金融模型对不上」是作者选的领先模型，前 14 页未逐个核。
- 不是交易策略收益。
- 不要写成「投资者在平静期更厌恶下跌」的实验。

## 可复用设计

要从期权读实物矩，先让定价核随波动变。同时报风险渠道和风险价格渠道。用同一套密度打 Martin 下界和方差溢价。资产定价估计卡。

证据指针：摘要（低波动更疼、Martin 下界、宏观模型）；引言（3.68 vs 1.32、3.8 pp、NCC 在危机破）。

训练价值：条件核怎么估。不当因果。
