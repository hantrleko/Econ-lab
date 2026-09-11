---
title: "The Impact of Minority Representation at Mortgage Lenders"
authors: "W. Scott Frame; Ruidi Huang; Erica Xuewei Jiang; Yeonjoon Lee; Will Shuo Liu; Erik J. Mayer; Adi Sunderam"
year: "2025"
venue: "Journal of Finance 80(2)"
doi: "10.1111/jofi.13428"
method: "IV"
slug: "2025-jf-minority-representation-mortgage"
source_file: "uploads/jofi.13428_de8f.pdf"
status: "carded-from-first14pp"
---

# Frame, Huang, Jiang, Lee, Liu, Mayer, and Sunderam (2025) — 少数族裔贷款官

DOI 在 PDF 第 1 页。对照 `references/methods/iv.md`。作者单位有美联储/行业协会披露。

## 问题

- 研究问题（一句）：抵押贷款官里少数族裔偏少，会不会让少数族裔申请人更难完成申请、更难获批、违约表现也更差？换少数族裔 LO，缺口能不能缩小？
- Estimand：同一白人 LO 手里，少数族裔相对白人申请人的完成/批准差距；少数族裔 LO 使该差距缩小多少。IV 是对「因排班而分到少数族裔 LO」的 LATE。

## 识别

- 策略：两条。(1) OLS 用网点-LO-年 FE，外加 FICO/LTV/DTI 窄桶，比较同一 LO 手里可观测上等价的少数族裔 vs 白人申请。(2) IV：用**同一网点、同一星期几、过去若干周**由少数族裔 LO 经手的申请份额，做「本次是否由少数族裔 LO 经手」的工具。想法是排班接近条件随机，申请质量不该跟 LO 轮班走。
- 关键假设：排他——历史星期几份额只通过「更可能碰到少数族裔 LO」影响结果，不通过某类申请人专挑某天去网点。
- 最危险威胁：申请人按星期几自选；LO 族裔用姓名+地点推断有误差；完成/批准/违约是不同选择阶段。对照 iv.md：这是排班份额 IV，LATE 只对有少数族裔 LO 轮班的网点。

## 数据

- 观察单元 / 时间：申请 × LO；主样本约 2018–2019 HMDA 扩展版
- 来源：机密 HMDA 匹配 NMLS 贷款官；违约用 FHA；另有 Black Knight McDash。机密数据不可外传（作者写明已筛查）。
- 处理与结果：处理 = 是否少数族裔 LO（及是否同族裔配对）；结果 = 完成、批准（尤其 AUS 说不清的高裁量申请）、放贷、FHA 违约
- 样本限制：能匹配到 LO 的购房抵押贷款；2019 年估计少数族裔占美国劳动力 39%，占贷款官约 15%

## 主结果

- 表/图号：引言转述；回归表号前 14 页未钉 → UNVERIFIED
- 点估计：白人 LO 手里，少数族裔申请完成率低约 **2 个百分点**；少数族裔 LO 使缺口小 **1–2 个百分点**。高裁量批准：白人 LO 手里少数族裔低约 **3 个百分点**；少数族裔 LO 再使缺口小 **1–2 个百分点**。FHA 违约：白人 LO 手里少数族裔高 **1.7 个百分点**，少数族裔 LO 时差距**消失**。高裁量批准缺口：OLS 缩小 **1.2pp**，IV 缩小 **3.6pp**。效应集中在同族裔配对、低收入、低学历/非英语区、小银行；FinTech 最弱。
- 作者解释：更像软信息优势（批准升且违约不升），不像单纯偏爱（偏爱会预测违约升或白人 LO 的拒绝伴随更低违约）。

## 可攻击点

- 识别：星期几自选；姓名族裔算法
- 测量：AUS「高裁量」如何切
- 外部有效：2018–19 美国购房贷；有少数族裔 LO 轮班的网点
- 表文：IV 比 OLS 大，要解释（OLS 可能低估匹配效应 / 弱工具）

## 可复用设计

- 能偷：排班/历史星期几份额 IV；同一代理人内部比两种客户；同时报完成、批准、违约
- 不该偷：只用 OLS 缺口讲歧视，不谈违约；把 LATE 写成全国 ATE

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13428 | PDF p.1 | 已核 PDF |
| 完成 −2pp，少数族裔 LO 缩小 1–2pp；高裁量批准 −3pp | 引言 | 已核引言 |
| FHA 违约 +1.7pp，少数族裔 LO 时消失；IV 3.6pp vs OLS 1.2pp | 引言 | 已核引言 |

## 对我的训练价值

- 练到了哪一层：IV + 组织匹配
- 下一步 skill：identification-audit
