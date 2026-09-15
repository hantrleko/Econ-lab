---
title: "Machine learning from a “Universe” of signals: The role of feature engineering"
authors: "Bin Li, Alberto G. Rossi, Xuemin (Sterling) Yan, Lingling Zheng"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104138
method: predictability
slug: ml-feature-engineering
source_file: uploads/1-s2.0-S0304405X25001461-main_3aa4.pdf
status: carded-from-first14pp
---

# Machine learning from a “Universe” of signals: The role of feature engineering

文章编号 104138。Roussanov 编辑。Li、Zheng：国家自然科学基金。武大超算。只根据 PDF 前约 14 页。

## 问题

用实时可构造的「宇宙」基本面信号做机器学习选股，样本外还能不能达到既往用已发表异象当特征的那些夏普。特征工程和简单历史排序是不是比模型本身更要紧。

## 识别

不是实验。增强回归树（BRT）等模型，特征是 Yan–Zheng 式排列出的 18000 多个基本面信号，训练时不把后来才发表的异象当成已知。对照：用已发表异象集的既往 ML 结果，以及各信号历史表现的递归排序。可预测/特征工程卡。

## 数据

美股截面。信号宇宙 >18000。也报过去收益类信号。样本期细表在后文。

## 主结果

BRT 等权多空 0.95%/月（t=6.63），年化夏普 1.02；市值加权 0.40%/月（t=2.34），夏普 0.30。弱于 Gu et al. (2020) 等用已发表异象当特征的数字（作者引等权 2.14%、夏普 1.73）。若改用已发表异象，作者自己的 BRT 等权可超过 3.5%/月。递归排序各信号历史表现，样本外更好。点估计表号在后文。

## 可攻击点

- 「宇宙」仍是研究者选定的变换族，不是投资者当时真会搜的集合。
- 与既往论文的夏普对比混了样本、成本和特征集。
- 等权远强于市值加权，经济意义取决于能否交易小盘。
- 不要写成「机器学习没用」，作者写的是特征工程和归纳偏置。

## 可复用设计

复现 ML 选股时把特征分成：当时可构造的宇宙 vs 事后已发表异象，并并列一个递归单信号排序。先报市值加权。

证据指针：摘要（弱于既往、递归排序更好）；引言（>18000、0.95%/0.40%、夏普 1.02/0.30）。

训练价值：可预测的特征泄漏。不当准实验。
