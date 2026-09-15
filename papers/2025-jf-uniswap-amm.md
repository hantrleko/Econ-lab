---
title: "Decentralized Exchange: The Uniswap Automated Market Maker"
authors: "Alfred Lehar; Christine Parlour"
year: "2025"
venue: "Journal of Finance 80(1)"
doi: "10.1111/jofi.13405"
method: "theory"
slug: "2025-jf-uniswap-amm"
source_file: "uploads/jofi.13405_b682.pdf"
status: "carded-from-first14pp"
---

# Lehar and Parlour (2025) — Uniswap 自动做市

理论 + 链上描述。DOI 在 PDF 第 1 页。摘要里的 40 亿 / 70 亿 USD 是规模描述，不是回归系数。

## 问题

- 研究问题（一句）：Uniswap 这种 AMM 流动性池的均衡是什么，什么时候比中心化限价订单簿更好？
- Estimand：模型均衡；链上对照 AMM vs 订单簿的价差/套利/冲击。

## 识别

- 策略：先建流动性池均衡，再收集 Uniswap 交互与中心化订单簿比较。不是政策 DID。
- 关键假设：费用 30bp 硬编码等协议规则；套利者使价格不长期偏离。
- 最危险威胁：把「没有长寿命套利」写成信息有效；样本期的链上选择。

## 数据

- 观察单元：池 / 区块内交互；作者称 95.8 million Uniswap interactions，105,098 个流动性池（引言/数据段）
- 来源：以太坊上 Uniswap 智能合约
- 处理与结果：无外生处理；结果 = 套利持续、价格冲击 vs Binance 等
- 样本限制：Uniswap 上存在的池

## 主结果

- 表/图号：前 14 页以描述和模型为主，具体表号 UNVERIFIED
- 点估计：无因果点估计。作者称：无长寿命套利；低波动时 Uniswap 价格冲击小，Binance 更高更波动（引言）
- 作者解释：在给出的条件下 AMM 可以优于限价订单市场。

## 可攻击点

- 识别：比较不是随机分配交易场所
- 测量：池生存、手续费档
- 外部有效：ETH / Uniswap v 时期
- 表文：「dominates a limit order market」有条件，不要摘成无条件

## 可复用设计

- 能偷：先写清 AMM 的机械价格冲击，再谈实证
- 不该偷：用链上相关性当「AMM 更好」的因果

## 证据指针

| Claim | 本地路径或页码 | 状态 |
|---|---|---|
| DOI 10.1111/jofi.13405 | PDF p.1 | 已核 PDF |
| 9580 万笔交互 | 摘要 | 已核摘要 |

## 对我的训练价值

- 练到了哪一层：市场设计构念
- 下一步 skill：无
