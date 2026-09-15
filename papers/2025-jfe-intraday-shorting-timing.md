---
title: "When do short sellers trade? Evidence from intraday data and implications for informed trading models"
authors: "Danqi Hu, Charles M. Jones, Xiaoyan Zhang, Xinran Zhang"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104148
method: predictability
slug: intraday-shorting-timing
source_file: uploads/1-s2.0-S0304405X25001564-main_b8e7.pdf
status: carded-from-first14pp
---

# When do short sellers trade? Evidence from intraday data and implications for informed trading models

文章编号 104148。Roussanov 编辑。版权保留。献给已故 Charles M. Jones。Hu、两 Zhang：国家自然科学基金等；Jones：挪威央行 NFI。FINRA 场外短售时间戳。只根据 PDF 前约 14 页。

## 问题

开盘、午间、收盘附近的空头流，对次日和未来数周收益的预测力是否不同。分别更像 Kyle 平稳交易、Holden–Subrahmanyam 开盘抢跑，还是 Collin-Dufresne–Fos 择流动性。

## 识别

不是对「谁知情」的实验。用时段空头流预测收益和负面新闻。借券集中度代理空头竞争。Tick Size Pilot 当作流动性外生变动，看开盘空头是否随流动性上升。最危险：时段切分 11:30 / 14:00 是作者选的；Pilot 只碰最小报价单位，不是随机分配信息。可预测卡。

## 数据

2015–2019 CBOE 带时间戳空头。也用 FINRA TRF 场外短售。开盘=11:30 前，午间=11:30–14:00，收盘=14:00 后。

## 主结果

三段空头流都负向预测次日收益，开盘最大。把窗口拉到 12 周：开盘和午间仍显著，收盘不再显著。开盘空头对隔夜新闻反应快，并预测未来 12 周负面新闻。内幕卖出与开盘空头同日共动，但一起进回归时两者都显著。开盘空头与当时流动性/噪声交易正相关；新闻刚发布时择流动性变弱。点估计表号在后文。

## 可攻击点

- 「知情」仍是收益/新闻预测，不是账户身份。
- 三种模型都被说成「在不同情形下成立」，可证伪性变弱。
- CBOE 不是全市场；场外短售另说。
- 不要把 Pilot 结果写成对知情交易模型的判决性检验。

## 可复用设计

日度空头太粗就拆开盘/午间/收盘。要区分平稳 vs 抢跑 vs 择流动性，必须同时报长窗预测、竞争代理和流动性外生变动。可与同卷 stealthy shorts 对读：一篇拆主动/被动，一篇拆时段。

证据指针：摘要（开盘和午间强于收盘、三模型分情形）；引言（12 周开盘/午间仍在、收盘不在、Pilot）。

训练价值：空头可预测的日内拆分。不当准实验。
