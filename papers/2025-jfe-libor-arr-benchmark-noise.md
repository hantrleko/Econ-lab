---
title: "Benchmarking benchmarks"
authors: "James Brugler, Marta Khomyn, Tālis Putniņš"
year: 2025
venue: Journal of Financial Economics 168
doi: 10.1016/j.jfineco.2025.104018
method: state-space / measurement
slug: libor-arr-benchmark-noise
source_file: uploads/1-s2.0-S0304405X25000261-main_830b.pdf
status: carded-from-first14pp
---

# Benchmarking benchmarks

文章编号 104018，印在 168 卷（不是 166/167 缺号里的那一卷）。开放获取 CC BY。Schnabl 编辑。Putniņš：ARC DP200101445。Khomyn 曾在 Chi-X/CBOE 澳大利亚访问。只根据 PDF 前约 14 页。

## 问题

LIBOR 换成交易型替代参考利率（ARR）后，基准价里有多少是噪声。噪声会在挂钩合约对手方之间转移多少财富。哪些设计（扩大参考市场、切尾均值）能降噪。

## 识别

状态空间：有效基准是随机游走，观测值加平稳噪声（Menkveld et al. 2007）。用模拟检查模型。财富转移：每天取出噪声分量，乘以当天定盘的隔夜指数掉期（OIS）名义，并用主体净额名义调整轧差。这是测度，不是政策实验。SOFR 更噪是回购抵押品供求尖峰，不是随机分配设计。

## 数据

五种主要货币的 LIBOR 与对应 ARR（CHF SARON、EUR ESTR、GBP SONIA、JPY TONAR、USD SOFR）。OIS 名义用于 2020 年转移额。前 14 页未写完整起止日表。

## 主结果

四国 ARR 噪声份额低于对应 LIBOR。美元 SOFR 明显比美元 LIBOR 更噪，可单日跳超过 1 个百分点再回去。若 2020 年 OIS 全挂 LIBOR，噪声相关转移约 770 亿美元；全挂 ARR 合计约 1660 亿美元，主要因为 SOFR。约相当于 OIS 未偿名义的 0.38%。GBP SONIA 在 2018-04-23 改革后，噪声份额从约 54.7% 降到 11.7%（扩大参考市场 + 切尾均值）。作者也称 ARR 去掉银行信用风险，有另一套信贷激励代价。

## 可攻击点

- 随机游走加噪声的分解依赖设定；尖峰可能被算成噪声或信息。
- 770 亿 / 1660 亿是噪声乘名义，不是已实现的法院可追转移。
- 五种货币改革同时改了定义、抵押和无担保，不能把「更噪」只怪 SOFR 一个设计旋钮。

## 可复用设计

评基准先把价格拆成信息/噪声，再乘挂钩名义谈转移。改革要能指到具体设计（切尾、扩市场）。美元 SOFR 不要和欧元/英镑 ARR 写进同一句「改革成功」。测度卡，不当因果。

证据指针：摘要（四国更净、美元更噪、数十亿转移）；引言（$77bn / $166bn、SONIA 54.7%→11.7%、1bp × $10 万亿 = $10 亿例子）。

训练价值：基准质量怎么测。SOFR 噪声与 165 卷国债发行漂移可并排，不当同一设计。
