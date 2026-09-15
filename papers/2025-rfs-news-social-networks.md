---
title: "News Diffusion in Social Networks and Stock Market Reactions"
authors: "David Hirshleifer; Lin Peng; Qiguang Wang"
year: "2025"
venue: "Review of Financial Studies 38(3)"
doi: "10.1093/rfs/hhae025"
method: "other"
slug: "2025-rfs-news-social-networks"
source_file: "uploads/hhae025_92a8.pdf"
status: "carded-from-first14pp"
---

# Hirshleifer, Peng, and Wang (2025) — 总部县城越中心，盈余新闻进价格越快，交易却更吵

社会网络相关。DOI 在 PDF 第 1 页。旧题 *Social Networks and Market Reactions to Earnings News*。行为金融研究奖；Peng 获 Krell / Keynes 基金。

## 问题

- 研究问题（一句）：上市公司总部所在县在社交网络里更中心，盈余公告是不是更快进价格，同时带来更持久的意见分歧和过度交易？
- Estimand：县中心度最高 vs 最低十分位，公告窗 [0,1] 的价格/波动/成交量反应，以及随后的 PEAD 和波动衰减。

## 识别

- 策略：中心度 = 总部县在 Facebook 社交连接（美国和加拿大）里的度/特征向量中心度，代理本地投资者在潜在投资者网络中的位置。不是随机实验。
- 作者提出 social churning：连接更有利于及时纳入价格，也放大意见分歧和过度交易。用 StockTwits 和家庭交易账户做机制。
- 关键假设：总部县中心度不是在代理纽约/加州基本面、分析师覆盖或机构。作者强调相邻县中心度可以差很多。

## 数据

- Facebook 县域连接；盈余公告。
- StockTwits；家庭交易记录。
- 图 1 特征向量中心度截至 2016 年 6 月。

## 主结果

- 相对度中心度最低十分位，最高十分位的公告：[0,1] 价格反应大约强 29%，随后 PEAD 大约弱 20%（都相对各自样本均值），波动掉得更快。
- 事后成交量更高、更持久。
- 作者读成：新闻进价格更快，但交易更吵。

## 可攻击点

- 总部县同时是媒体、基金、分析师密度；Facebook 中心度可能只是大城市。
- 29%/20% 是相对均值，不是回归系数本身。
- 不是实验；StockTwits 用户不是家庭账户的同一群人。

## 可复用设计

- 盈余反应不要只控州或距离，县域网络位置是另一层。
- 同时报价格效率（更小 PEAD）和交易过量（更持久成交），避免只讲「传播更快更好」。
- 相邻县反差是挡「就是沿海」的最小证据。

## 证据指针

- 更强即时反应、更弱漂移、social churning：PDF 第 1 页摘要。
- +29% / −20% PEAD：PDF 第 3 页。

## 训练价值

社交金融相关卡。和路演视频、战争话语同一作者家族；识别上弱于碎股 DID。
