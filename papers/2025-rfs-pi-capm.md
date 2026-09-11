---
title: "5-CAPM: The Classical CAPM with Probability Weighting and Skewed Assets"
authors: "Joost Driessen; Sebastian Ebert; Joren Koëter"
year: "2025"
venue: "Review of Financial Studies 38(12)"
doi: "10.1093/rfs/hhaf045"
method: "other"
slug: "2025-rfs-pi-capm"
source_file: "uploads/hhaf045_7865.pdf"
status: "carded-from-first14pp"
---

# Driessen, Ebert, and Koëter (2025) — 概率加权之后，偏度×波动决定价格，期权方差溢价对偏度是 U 形

开放获取。ERC Horizon 2020，协议 803380。DOI 在 PDF 第 1 页。标题里的 5 是决策权重 Π。和同辑短腿彩票文本那张并排：一个写投资者怎么说 upside，一个写偏度在定价里怎么进 CAPM。

## 问题

- 研究问题（一句）：代表投资者若用决策权重替代客观概率（高估极端尾部），波动和偏度在股票和期权上应该怎么定价？
- Estimand：不是因果。模型相对经典 CAPM 多一个概率加权强度；实证是美股截面上波动×偏度，以及个股期权方差溢价对偏度的 U 形。

## 识别

- 策略：理论。第一版两资产、两点分布，能匹配任意均值、波动、偏度、相关；neo-additive 加权（Chateauneuf–Eichberger–Grant）。第二版多资产、多状态，按市场组合排序结果来加权，数值解。加权强度取实验文献，不另估。
- 对照：没有概率加权的标准偏好配不上这些模式。
- 最危险威胁：双重排序和 Fama–MacBeth 是相关；偏度、波动同时被错误定价或微观结构噪声带着走。

## 数据

- 美股截面（Boyer–Mitton–Vorkink 一类预期偏度）。个股期权方差溢价，方法从 Kozhan–Neuberger–Schneider 的指数版改来。

## 主结果

- 预测：(i) 偏度有正价格效应，被波动放大——左偏相对经典 CAPM 有正 alpha，右偏多为负 alpha；(ii) 波动对左偏资产压价、对右偏抬价；(iii) 个股期权方差溢价对偏度呈 U 形，再被波动放大；(iv) 投资人夸大共同运动，能给出正的、且随客观相关下降的相关溢价。
- 双重排序：正偏度只在中高波动股票里对应低收益。
- 波动异象：偏度接近零时，高减低波动多空 alpha 大约每年 **−4%**；很高正偏度时大约 **−28%**。Fama–MacBeth 里交互项比波动或偏度单独更强。
- 作者称个股期权上看到 U 形，且右偏股票也有正方差溢价——标准偏好难讲。相关溢价对齐 Driessen–Maenhout–Vilkov 等。
- U 形和相关溢价的具体点数前 14 页没有，**部分 UNVERIFIED**。

## 可攻击点

- −4% / −28% 是引言里的双重排序，表号在后文。
- 加权参数外生于实验，拟合好可能是碰巧。
- 第二版「按市场组合排序来加权」是额外假设。
- 不要把「解释了波动之谜」写成识别了因果。

## 可复用设计

- 偏度和波动不要分开报，交互才是模型的可证伪点。
- 方差溢价对偏度画 U，不要只报市场指数的一个数。
- 校准先钉实验文献的加权强度，再看数量级，比事后估 Π 干净。
- 和短腿文本：定价含义是彩票溢价，文本应看到 upside 词。

## 证据指针

- 摘要、三条预测、相关溢价：PDF 第 1 页。
- −4% vs −28%、交互：PDF 第 3–4 页。
- 期权 U 形：PDF 第 4 页。
- 期权/相关的点估计：前 14 页不全，UNVERIFIED。

## 训练价值

行为定价卡。写偏度溢价必须带波动交互。不是准实验审计对象。
