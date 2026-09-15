---
title: "Data and welfare in credit markets"
authors: "Mark Jansen, Fabian Nagel, Constantine Yannelis, Anthony Lee Zhang"
year: 2025
venue: Journal of Financial Economics 174
doi: 10.1016/j.jfineco.2025.104171
method: DID + sufficient stats
slug: data-welfare-credit
source_file: uploads/Data-and-welfare-in-credit-markets_2025_Journal-of-Financial-Economics_0782.pdf
status: carded-from-first14pp
---

# Data and welfare in credit markets

文章编号 104171。Whited 编辑。版权保留。TransUnion 经芝大 Booth Kilts；TransUnion 有权审稿确保不泄密、不误导。只根据 PDF 全文 13 页已抽。对照 `references/methods/did.md`。

## 问题

贷款人多掌握借款人成本数据，价格更贴成本，总福利升、组间剩余转移。只用价格和数量，能不能估福利和再分配。破产标记永不删除，汽车贷市场会怎样。

## 识别

理论：数据 = 三级价格歧视。需求对还款近似线性时，福利和转移是有/无数据下价格数量的函数。经验：FCRA 下 Chapter 13（7）标记 7（10）年后删除。同一人删除前后比贷款条件。从未破产组：用贷款人零利润反推反事实价格，并假设两组需求弹性相同推数量。DID 估删除效应。最危险：删除时点可预期，人会等；弹性相同是强假设；零利润排除市场势力。

## 数据

TransUnion 行政信用。美国汽车贷。

## 主结果

标记删除：信用分 +17 分，利率 −22.6 bp，借款 +18 美元（DID）。若永不删除：社会剩余每年大约多 59.8 万美元，但从曾破产者转到从未破产者大约 1900 万美元，即每再分配 1 美元只换大约 0.03 美元效率。点估计在引言。

## 可攻击点

- 福利数字完全靠线性需求、等弹性和零利润。
- DID 是预期到的制度时钟，不是随机删除。
- 59.8 万 vs 1900 万是汽车贷这一市场加总，不是全部信贷。
- 不要写成「删标记无效率」；作者写效率损失相对再分配很小。

## 可复用设计

数据政策先写成价格歧视的效率和再分配，再用价格数量足够统计。预期删除日要讨论提前行为。可跑识别审计。

证据指针：摘要（永不删除则曾破产剩余大降、效率只略升）；引言（+17 分、−22.6 bp、+$18、59.8 万 vs 1900 万）。

训练价值：制度时钟 + 福利足够统计。优先识别审计。
