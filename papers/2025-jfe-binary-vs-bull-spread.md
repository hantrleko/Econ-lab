---
title: "Overvaluing simple bets: Evidence from the options market"
authors: "Aaron Goodman, Indira Puri"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104140
method: descriptive / dominance
slug: binary-vs-bull-spread
source_file: uploads/1-s2.0-S0304405X25001485-main_c3fc.pdf
status: carded-from-first14pp
---

# Overvaluing simple bets: Evidence from the options market

文章编号 104140。Papanikolaou 编辑。Goodman 后入职 Vanguard，观点不代表 Vanguard。NSF GRFP、MIT Shultz、Puri：Soros。旧题 *Bulls and Binaries* / *Overvaluing 0-1 Bets*。只根据 PDF 前约 14 页。

## 问题

零售二元期权成交价，会不会经常高于状态占优的牛市价差。标准偏好（前景理论、模糊、凸出、理性疏忽）能不能产生这种占优违反。

## 识别

不是实验。在 Nadex 一类零售交易所比较：二元（0-1 赌）vs 状态上处处不差且常更便宜的牛市价差。违反无占优 = 买了被占优的二元。作者证明常见效用形式只要尊重占优就推不出；并排除交易成本、流动性、交易所 FE、噪声交易等金融解释。描述/占优卡。

## 数据

零售二元期权成交。标的：标普、金、银。开源复制链接 openicpsr 234221。

## 主结果

15% 标普、19% 金、25% 银成交违反无占优。买被占优二元平均亏合约价 34%。作者归到「简单、好懂的二元赌」。点估计表号在后文。

## 可攻击点

- 牛市价差是反事实组合，零售客是否真能同时买到、费用是否对称，要看后文。
- 占优按到期收益，忽略提前平仓和保证金路径。
- 样本是选择进二元交易所的人，不是全体零售。
- 不要写成「证明了新效用函数」；作者只说现有框架盖不住。

## 可复用设计

行为异常先找状态占优违反，再谈概率扭曲。被占优证券的成交份额本身就是可报告统计量。

证据指针：摘要（15%/19%/25%、亏 34%、标准理论证不出）。

训练价值：描述性占优。不当准实验。
