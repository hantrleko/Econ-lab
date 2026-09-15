---
title: "Forest through the Trees: Building Cross-Sections of Stock Returns"
authors: "Svetlana Bryzgalova; Markus Pelger; Jason Zhu"
year: "2025"
venue: "Journal of Finance 80(5)"
doi: "10.1111/jofi.13477"
method: "other"
slug: "2025-jf-forest-cross-sections"
source_file: "uploads/The_Journal_of_Finance_-_2025_-_BRYZGALOVA_-_Forest_through_the_Trees__Building_Cross_E2_80_90Sections_of_Stock_Returns_c245.pdf"
status: "carded-from-first14pp"
---

# Bryzgalova, Pelger, and Zhu (2025) — 用树做股票截面

资产定价 / 方法。DOI 在 PDF 第 1 页。

## 问题

- 研究问题（一句）：测试资产和可交易因子，能不能用决策树内生分组股票，而不是手工单/双排序？
- Estimand：树分组得到的截面/因子，相对大量特征排序与机器学习预测组合的样本外 Sharpe 与 alpha。

## 识别

- 策略：方法论文。树在特征空间里切股票，叶子是测试资产，也可做成可交易因子。
- 关键假设：样本外验证能管住过拟合；比较组（单/双排序、ML 组合）代表现行做法。
- 不是因果识别。

## 数据

- 标准美国股票截面特征与收益（只读前 14 页：具体样本年与特征清单在后文）。

## 主结果

- 相对大量单/双排序和 ML 预测组合，树截面的维度更低，样本外 Sharpe / alpha 最高大约是比较组的 3 倍。
- 作者强调「截面是建出来的」，不是天上掉下来的 25 组合。

## 可攻击点

- 「3 倍」对比较组定义敏感；换一套异常收益清单可能缩小差距。
- 树仍然用了研究者选定的特征库。
- 交易成本与可交易约束只读前 14 页未见完整处理。

## 可复用设计

- 不要把 Fama–French 手工排序当成唯一测试资产；分组规则本身是设定。
- 方法贡献要用样本外 Sharpe/alpha 对现行截面，而不是只报样本内 R²。

## 证据指针

- 约 3 倍样本外 Sharpe/alpha：PDF 第 1 页摘要。

## 训练价值

资产定价计算课。做因子论文时用来提醒：测试资产不是中性的。
