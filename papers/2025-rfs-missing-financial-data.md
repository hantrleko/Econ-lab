---
title: "Missing Financial Data"
authors: "Svetlana Bryzgalova; Sven Lerner; Martin Lettau; Markus Pelger"
year: "2025"
venue: "Review of Financial Studies 38(3)"
doi: "10.1093/rfs/hhae036"
method: "other"
slug: "2025-rfs-missing-financial-data"
source_file: "uploads/hhae036_ded3.pdf"
status: "carded-from-first14pp"
---

# Bryzgalova, Lerner, Lettau, and Pelger (2025) — 公司基本面缺失是系统的，不能随便删

测度 / 插补。DOI 在 PDF 第 1 页。

## 问题

- 研究问题（一句）：公司财务特征缺得有多广、缺得是否成块，传统插补会不会把风险溢价和异常做歪？
- Estimand：缺失覆盖的公司数与市值；新插补（同时用时间序列和截面依赖、允许系统缺失）对风险溢价、异常和组合的影响。

## 识别

- 策略：先画缺失结构，说明不是随机缺。传统方法（删观测、简单填）在系统缺失下无效。新方法利用时序和截面依赖补成完整面板。
- 不是准实验。含义靠「补完前后估计差多少」。

## 数据

- 公司基本面特征面板。
- 引言：JF/RFS 等顶刊里约 70% 碰到缺失的论文直接丢掉缺失观测。

## 主结果

- 超过 70% 的公司有缺失，大约对应一半市值。
- 缺失模式复杂、系统，传统插补不成立。
- 对风险溢价估计、截面异常和组合构建有重要影响（具体方向和幅度前 14 页未写，UNVERIFIED）。
- 例：2015 年左右约 42% 公司缺研发（转引）。

## 可攻击点

- 「系统缺失」的插补仍是模型；补出来的值会进异常收益。
- 70% 公司 / 一半市值对特征清单敏感。
- 和应用 Freyberger 等的方法并排时，要以同一套异常复现。

## 可复用设计

- 先报缺失的公司覆盖和市值覆盖，再谈因子。
- 缺研发、缺广告这种块状缺失，不要当 MCAR。
- 插补方法必须允许「整类公司整段时间一起缺」。

## 证据指针

- 70% 公司、约一半市值、系统缺失：PDF 第 1 页摘要。
- 顶刊约 70% 直接删除：PDF 第 2 页。
- 对异常/溢价的定量：前 14 页不足，UNVERIFIED。

## 训练价值

和 `2025-rfs-missing-data-asset-pricing.md` 一起读。特征工作流的第一张检查表。
