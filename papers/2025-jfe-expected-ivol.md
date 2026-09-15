---
title: "Expected idiosyncratic volatility"
authors: "Geert Bekaert, Mikael Bergbrant, Haimanot Kassa"
year: 2025
venue: Journal of Financial Economics 167
doi: 10.1016/j.jfineco.2025.104023
method: volatility forecast / cross-section
slug: expected-ivol
source_file: uploads/1-s2.0-S0304405X25000315-main_a365.pdf
status: carded-from-first14pp
---

# Expected idiosyncratic volatility

文章编号 104023。Roussanov 编辑。只根据 PDF 前约 14 页。

## 问题

个股方差里 idiosyncrasy 通常比系统部分大，但预期 idiosyncratic 方差怎么预报，文献少。用更好的预报再看 Ang 等的 IVOL 之谜：是风险被定价，还是鞅预报把暂时高波动当成预期。

## 识别

预报赛马，不是因果。基准包括鞅（Ang et al. 2006）、HAR、非线性自回归、ARMA(1,1)，以及加上市场方差的变体；再比更高阶 ARMA、quarticity、MIDAS。样本外 RMSE 选模型。定价段：把各模型的预期 IVOL 丢进横截面，看负相关是否还在。作者再删掉鞅预报误差最大的一小撮观测，看之谜是否消失。没有外生冲击。

## 数据

CRSP 日收益 1926–2022。数据节：78,304,731 条日收益、3,715,261 条月收益、26,493 家（家数从约 500 到 7,519）。摘要写近 8000 万日收益、1.9 万+ 家，预报样本可能更窄。会计与特征来自 Compustat；买卖价差等来自 Open Source Asset Pricing，并滞后。

## 主结果

ARMA(1,1)（加或不加市场方差）对约 46% 的公司样本外最好；单 ARMA 引言约 34%，进前三约 72%。相对最佳模型的 RMSE 中位数比约 1.0106。ARMA 平均 RMSE 显著低于所有对照。鞅预期 IVOL 与收益负相关；其他预报、包括 ARMA，都不显著。每月去掉预报误差最高的约 0.4% 观测，或去掉鞅与 ARMA 差距最大的约 5%–7%，鞅回归也不显著。极端误差和买卖价差、规模、非流动性、反转、尤其 MAX 相关。

## 可攻击点

- 「之谜消失」依赖删极端值，审稿人可说这是把定价对象删掉。
- 预期 IVOL 仍是模型构造，不是投资者预期。
- 摘要 1.9 万家与数据节 2.6 万家对不上，预报样本边界要核对全文表。
- 没有识别设计，不能写成「IVOL 未被定价所以市场有效」。

## 可复用设计

横截面风险度量先做预报赛马，再定价。鞅把上月实现波动当预期时，先看暂时冲击是否在回吐。删掉预报最差的一小撮，是打「之谜很脆」的写法，但要同时报不删的 ARMA 结果。不要把 RMSE 冠军写成因果。

证据指针：摘要（约 46% 公司 ARMA 最好；鞅之谜由预报过冲驱动）；引言（0.4% / 5%–7% 观测；MAX）；数据节（1926–2022 行数）。

训练价值：IVOL 之谜可能是预报误设。资产定价测度卡，不当因果。
