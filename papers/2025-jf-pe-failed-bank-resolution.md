---
title: "Private Equity and Financial Stability: Evidence from Failed-Bank Resolution in the Crisis"
authors: "Emily Johnston-Ross; Song Ma; Manju Puri"
year: "2025"
venue: "Journal of Finance 80(1)"
doi: "10.1111/jofi.13399"
method: "other"
slug: "2025-jf-pe-failed-bank-resolution"
source_file: "uploads/jofi.13399_35aa.pdf"
status: "carded-from-first14pp"
---

# Johnston-Ross, Ma, and Puri (2025) — 危机里 PE 接盘破产银行

接近「双方都出价且出价接近」的准随机，不是标准 RCT/RD。DOI 在 PDF 第 1 页。

## 问题

- 研究问题（一句）：2008 年后 PE 参与 FDIC 破产银行拍卖，是在填补本地银行空缺，还是在掏空？
- Estimand：在 PE 和银行都竞价、出价接近的拍卖里，PE 赢相对银行赢，对银行事后表现和县域实体经济的效应。

## 识别

- 策略：FDIC 专有竞价数据。限制在「PE 与银行都可买、出价接近」（相对 FDIC 保留价/cover bid）。作者称准随机；并说该子样本上可观察特征平衡、赢率接近。
- 关键假设：接近出价时，谁赢近似随机；赢者类型不通过未观察拍卖特征进入结果。
- 最危险威胁：谁进入「接近」窗口仍有选择；PE 另有 10% 一级资本要求，处理不是「纯粹所有权」；银行收购后关网点有合并机械效应（作者试图用全县退出等来挡）。

## 数据

- 观察单元 / 时间：破产银行拍卖 / 网点 / 县；主样本 2009–2014
- 来源：FDIC 破产银行收购与竞价（专有）；Preqin 等识别 PE
- 处理与结果：处理 = PE 赢下 vs 银行赢下；结果 = 事后银行表现、网点关闭、存款、县域小企业信贷等
- 样本限制：危机后 failed-bank resolution；准随机样本再砍到双方竞价且接近

## 主结果

- 表/图号：描述性在后文；前 14 页引言称 PE 买的是更大、更差、更险的银行
- 点估计：准随机样本上，PE 接管网点的存款增长约高 35%（「roughly 35% higher growth across specifications」，引言）。其他绩效系数前 14 页未钉 → UNVERIFIED
- 作者解释：PE 在本地银行也困难的地方填空，对金融稳定是正的。

## 可攻击点

- 识别：close-bid 带宽怎么定；FDIC 对 PE 的额外资本约束
- 测量：PE 定义（所有权门槛，附录做了替换）
- 外部有效：危机 + 美国破产银行拍卖
- 表文：「positive role in stabilizing the financial system」比「接近拍卖里存款长得更快」宽

## 可复用设计

- 能偷：拍卖里用「双方都出价 + 出价接近」做准随机，而不是比较所有 PE vs 所有银行
- 不该偷：把「买了更差的银行」的描述性差异当成处理效应

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13399 | PDF p.1 | 已核 PDF |
| close-bid 准随机 | 引言 | 已核 |
| 存款增长约 +35% | 引言 | 已核引言，未对表 |

## 对我的训练价值

- 练到了哪一层：识别设计（选择 vs 准随机）
- 下一步 skill：identification-audit
