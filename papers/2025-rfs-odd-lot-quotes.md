---
title: "The Market Inside the Market: Odd-Lot Quotes"
authors: "Robert P. Bartlett; Justin McCrary; Maureen O’Hara"
year: "2025"
venue: "Review of Financial Studies 38(3)"
doi: "10.1093/rfs/hhad074"
method: "other"
slug: "2025-rfs-odd-lot-quotes"
source_file: "uploads/hhad074_fbb3.pdf"
status: "carded-from-first14pp"
---

# Bartlett, McCrary, and O’Hara (2025) — NBBO 里面还有一个零股报价市场

市场微观结构测度。DOI 在 PDF 第 1 页（`hhad074`，2023 年提前发表）。LSEG 低延迟（原 May Street）数据。

## 问题

- 研究问题（一句）：低于 100 股的零股报价是不是经常比 NBBO 更好，并且只有买了交易所专有行情的人看得见？
- Estimand：优于 NBBO 的零股报价出现频率；零股中间价对随后 NBBO 的预测；用零股训练的交易策略盈亏；SEC 拟议整手重定义能消掉多少。

## 识别

- 策略：不是准实验。2021 年 1–3 月 16 家美股交易所几乎全部报价与成交（作者称与 SEC MIDAS 同源）。XGBoost 用零股预测未来价格。
- 信息优势来自「公开展示的 NBBO 不含零股，专有行情含」。

## 数据

- 2021 年 1–3 月全市场消息；部分表涉及约 320 亿观测。
- 零股订单占比：不到 500 股的订单里，组别 1 约 5.7%，组别 5 约 46.9%。

## 主结果

- 样本期内，亚马逊 60% 的时间有更好的零股买价，谷歌 54%，特斯拉 53%，Facebook 超过 25%。
- 零股参与价格发现；对能看到专有行情的交易者有信息。
- 作者展示一个简单、用零股预测的盈利策略（具体收益前 14 页未写，UNVERIFIED）。
- SEC 拟议的整手重定义能减少、但不能消灭 NBBO 之内的更优零股报价。

## 可攻击点

- 三个月、正值散户和碎股高峰，外部有效性窄。
- 「盈利策略」有过拟合和不可交易（延迟、费用）风险。
- 隐藏单、中间价单也会造成「价差内更好价格」，不一定是零股。

## 可复用设计

- 执行质量不要只对 NBBO；先问零股是否经常更好。
- 公开展示 vs 专有行情是信息分层，不是同一个「最佳买价」。
- 政策评估要报「改革后还剩多少价差内零股」，不要报「问题消失」。

## 证据指针

- 内部市场、XGBoost、改革减但不消：PDF 第 1 页摘要。
- AMZN/GOOG/TSLA/FB 频率、320 亿点、5.7%–46.9%：PDF 第 2 页。

## 训练价值

微观结构测度。和 JF 真实零售价、RFS 碎股交易放一起：散户单变碎之后，公开展示更落后。
