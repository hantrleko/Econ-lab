---
title: "Screening using a menu of contracts: A structural model for lending markets"
authors: "Alberto Polo, Arthur Taburet, Quynh-Anh Vo"
year: 2025
venue: Journal of Financial Economics 169
doi: 10.1016/j.jfineco.2025.104056
method: structural IO / IV
slug: uk-mortgage-screening
source_file: uploads/1-s2.0-S0304405X25000649-main_e0a9.pdf
status: carded-from-first14pp
---

# Screening using a menu of contracts: A structural model for lending markets

文章编号 104056。英格兰银行出版。Whited 编辑。观点不代表英格兰银行、MPC/FPC/PRA 或 FCA。复制数据 Harvard Dataverse。只根据 PDF 前约 14 页。对照 `references/methods/iv.md`。

## 问题

贷款人用合同菜单筛选借款人时，会不会让竞争对手的借款人池变差（合同外部性），从而筛得过多。英国首次购房按揭市场上，这种扭曲值多少福利。

## 识别

带内生菜单的结构筛选模型。需求：混合 logit + 贷款额。供给：多产品不完全竞争。道德风险 vs 逆向选择：合同 A 的价格变，会改选合同 B 的人的组成；比较选了同一合同 B、但因 A 的价不同而自选不同的组的违约。工具：合同特定资本要求，用来外生移动合同之间的利差。第一、第二最优用反事实菜单。不是随机监管实验。

## 数据

英国首次购房按揭，2015–2019。行政菜单、选择和违约。

## 主结果

LTV 和利率一起筛：高违约者选更高 LTV、更高利率。数据里约 50% 较低违约借款人选 70%–85% LTV；完全信息下他们（以及多数人）会拿到 85% 以上并买更大的房。95% LTV 的利率比完全信息大约低 70 个基点。相对内化外部性的第二最优，筛得过多；死重损失的下界相当于所有贷款利率高 30 个基点（约 15%），作者换算成每月约 25 英镑（20 万英镑、25 年），实际由约三分之一借款人承担则约每月 75 英镑。

## 可攻击点

- 资本要求工具可能同时改银行供给和谁来申请，不只改利差。
- 30 / 70 个基点是模型反事实。
- 「禁止低 LTV」一类政策在同伴理论文，不是本文实验。
- 只要首次购房，加按和投资房看不到。

## 可复用设计

菜单筛选要能把「A 的价改 B 的组成」写成 IV。资本要求按合同变，才分得开选择和道德风险。福利用第一、第二最优菜单，不要只报加成。结构卡。

证据指针：摘要（外部性、30 bp / 15%）；引言（70 bp、70–85% LTV 主要是为了筛、2015–2019）。

训练价值：合同外部性怎么量化。不当资本监管 DID。
