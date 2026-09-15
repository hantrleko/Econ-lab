---
title: "War Discourse and Disaster Premium: 160 Years of Evidence from the Stock Market"
authors: "David Hirshleifer; Dat Mai; Kuntara Pukthuanthong"
year: "2025"
venue: "Review of Financial Studies 38(2)"
doi: "10.1093/rfs/hhae081"
method: "other"
slug: "2025-rfs-war-disaster-premium"
source_file: "uploads/hhae081_57d3.pdf"
status: "carded-from-first14pp"
---

# Hirshleifer, Mai, and Pukthuanthong (2025) — 战争话语预报市场超额收益

文本资产定价（时间序列）。DOI 在 PDF 第 1 页。和同组作者 JF 80(6) 的战争因子截面论文是姊妹篇：这篇盯市场超额，那篇盯截面。

## 问题

- 研究问题（一句）：媒体战争/灾难话题升上去，接下来的股票市场超额收益会不会更高—— rational 灾难溢价和显著/前景理论都能推出这个符号？
- Estimand：话语主题对市场超额收益的样本外预测（战争主题 OOS R²）。

## 识别

- 策略：半监督 seeded LDA，约 160 年、700 万篇《纽约时报》。作者强调避开前视、处理语义漂移。灾难罕见，用新闻注意力放大样本。
- 不是准实验。理性（灾难风险升 → 预期收益升）和两个行为假说（高估罕见概率、前景理论加权重尾）符号相同，前 14 页没有把它们分开。
- 也系统比较非灾难主题。

## 数据

- 《纽约时报》约 700 万篇、160 年。
- 市场超额收益。

## 主结果

- 话语主题正向预测市场超额；战争主题样本外 R² 为 1.35%。作者称为战争收益溢价。
- 这一溢价在更近的样本里更大。

## 可攻击点

- OOS R²=1.35% 对主题种子、样本划分和交易成本敏感。
- 战争新闻也是宏观新闻，不一定是「灾难概率」。
- 理性与行为同向，这篇时间序列解不开。
- 和 JF 截面那篇共用文本管道，复制误差会两边一起错。

## 可复用设计

- 罕见灾难不要只数战争年份，用连续的媒体注意力。
- 半监督主题要写清种子和如何防前视。
- 市场溢价和截面对冲是两个检验，不要合成一篇故事。

## 证据指针

- 700 万篇、战争 OOS R² 1.35%、近期更大：PDF 第 1 页摘要。

## 训练价值

文本资产定价。和 `2025-jf-war-discourse-returns.md` 对照着读：一个市场、一个截面。
