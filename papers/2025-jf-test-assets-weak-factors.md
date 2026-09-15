---
title: "Test Assets and Weak Factors"
authors: "Stefano Giglio; Dacheng Xiu; Dake Zhang"
year: "2025"
venue: "Journal of Finance 80(1)"
doi: "10.1111/jofi.13415"
method: "other"
slug: "2025-jf-test-assets-weak-factors"
source_file: "uploads/jofi.13415_5992.pdf"
status: "carded-from-first14pp"
---

# Giglio, Xiu, and Zhang (2025) — 测试资产和弱因子

计量方法文（SPCA）。DOI 在 PDF 第 1 页。前 14 页几乎没有具体风险溢价数字。

## 问题

- 研究问题（一句）：弱因子和测试资产怎么选，其实是同一件事——资产对因子暴露太弱，你就估不准风险溢价。怎么办？
- Estimand：因子风险溢价；即便有弱因子、有因子没被观测。

## 识别

- 策略：提出 supervised PCA：监督选资产 → 主成分 → 因子投影，迭代。给渐近性质。
- 关键假设：监督信号与目标因子相关；有限样本渐近近似成立。
- 最危险威胁：监督步骤用了与检验相关的信息导致过拟合；把方法表现写成某个宏观因子「一定有溢价」。

## 数据

- 观察单元：资产定价面板（实证应用在后文，前 14 页未展开 → 应用结果 UNVERIFIED）
- 来源：未在前 14 页钉死
- 处理与结果：无政策处理
- 样本限制：UNVERIFIED

## 主结果

- 表/图号：方法与模拟在后文；前 14 页无可用点估计 → UNVERIFIED
- 点估计：UNVERIFIED
- 作者解释：弱因子 = 测试资产暴露不够；把资产选对，因子会变强。SPCA 用来估溢价、诊断模型。

## 可攻击点

- 识别：方法文，取决于监督变量
- 测量：应用尚未在本卡片核对
- 外部有效：取决于你的测试资产库
- 表文：不要在没看应用表时引用「SPCA 找到了某某溢价」

## 可复用设计

- 能偷：先问测试资产有没有暴露，再骂因子弱
- 不该偷：没读应用节就当实证发现

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13415 | PDF p.1 | 已核 PDF |
| 应用表中的溢价数字 | 后文 | UNVERIFIED |

## 对我的训练价值

- 练到了哪一层：资产定价计量构念
- 下一步 skill：无（先补读应用节）
