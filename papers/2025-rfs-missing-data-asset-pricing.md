---
title: "Missing Data in Asset Pricing Panels"
authors: "Joachim Freyberger; Bjoern Hoeppner; Andreas Neuhierl; Michael Weber"
year: "2025"
venue: "Review of Financial Studies 38(3)"
doi: "10.1093/rfs/hhae003"
method: "other"
slug: "2025-rfs-missing-data-asset-pricing"
source_file: "uploads/hhae003_9367.pdf"
status: "carded-from-first14pp"
---

# Freyberger, Hoeppner, Neuhierl, and Weber (2025) — 截面定价里缺特征怎么补

计量方法。DOI 在 PDF 第 1 页。和同刊 Bryzgalova 等「缺失财务数据」是姊妹：这篇偏 GMM/加权，那篇偏系统缺失结构。

## 问题

- 研究问题（一句）：股票特征经常缺，但收益还在，能不能既用上所有有收益的观测，又给出有效推断？
- Estimand：条件均值插补 + 加权最小二乘，放在 GMM 里；相对完整案例删除和计算昂贵的有效 GMM。

## 识别

- 策略：方法论文。对缺失特征做条件均值插补，再用 WLS/GMM。作者称可用于非线性、高维。
- 模拟里接近有效但更贵的 GMM。不是因果识别。

## 数据

- 大面板收益预测变量（只读前 14 页：特征清单在后文）。

## 主结果

- 能用上所有有收益的观测，推断有效（作者声称）。
- 应用到大量预测变量时，样本外可预测性改善。
- 具体 OOS 增量和模拟 RMSE 前 14 页未写，UNVERIFIED。

## 可攻击点

- 条件均值插补若缺失与收益相关（非随机缺失），加权也救不回。
- 「几乎和有效 GMM 一样好」对模拟设计敏感。
- 和 Bryzgalova 等提出的系统缺失方法可能给出不同补全。

## 可复用设计

- 缺特征不要直接 listwise delete，先写缺失机制。
- 插补要进 GMM/加权，才能谈推断，不要只填完再 OLS。
- 两篇 RFS 缺失数据要并排：一个强调 GMM，一个强调系统模式。

## 证据指针

- 条件均值 + WLS/GMM、OOS 改善：PDF 第 1 页摘要。
- 模拟与应用数字：前 14 页不足，UNVERIFIED。

## 训练价值

资产定价计算课。做特征面板前先问缺失。
