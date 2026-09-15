---
title: "Why do portfolio choice models predict inelastic demand?"
authors: "Carter Davis, Mahyar Kargar, Jiacui Li"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104096
method: decomposition
slug: inelastic-demand-decomp
source_file: uploads/1-s2.0-S0304405X25001047-main_d730.pdf
status: carded-from-first14pp
---

# Why do portfolio choice models predict inelastic demand?

文章编号 104096，印在 172 卷。Papanikolaou 编辑。旧题 *Why is Asset Demand Inelastic?*。Mendeley `5tz5fgjmxg/2`（未点开）。只根据 PDF 前约 14 页。

## 问题

经典组合选择为什么把个股需求弹性说到几千，实证大约是 1。是不是必须靠摩擦和行为，还是价格传导和「未被其他股票张成的收益」两个可估项就能把缺口收掉。

## 识别

分解，不是准实验。CRRA、可有卖空约束。弹性 ≈ 1 +（价格传导）×（1 / 未张成收益）。价格传导：与现金流无关的价格变动对下期期望收益的影响，Fama–MacBeth，月度大约 0.01。未张成收益：对其他股票线性投影后的残差期望收益；特征期望收益 + Ledoit–Wolf 收缩协方差，最优组合里平均股票月度大约 0.3%。弱因子让未张成项变大。

## 数据

美国月度股票收益。价格传导的稳健用文献里与现金流无关的价格变异。

## 主结果

经典假设下弹性大约 7000。只把价格传导换成 0.01，降到大约 800。再换上实证未张成收益，降到大约 5，接近实证的约 1。作者称经典模型同时假设太高的价格传导和太低的未张成收益。点估计表号在后文。

## 可攻击点

- 0.01 / 0.3% / 5 依赖期望收益和协方差模型。
- 「接近 1」仍差一个数量级。
- 不是估计一条需求曲线。
- 不要写成「已解释全部无弹性」。

## 可复用设计

需求弹性争论先拆价格传导和替代性，再谈摩擦。弱因子进入协方差，未张成项就不会接近零。方法 / 分解卡。

证据指针：摘要（三个数量级、弱因子）；引言（7000→5、传导 0.01、未张成 0.3%）。

训练价值：需求弹性缺口从哪来。不当因果。
