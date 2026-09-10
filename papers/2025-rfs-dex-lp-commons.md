---
title: "Liquidity Provision on Blockchain-Based Decentralized Exchanges"
authors: "Agostino Capponi; Ruizhe Jia"
year: "2025"
venue: "Review of Financial Studies 38(10)"
doi: "10.1093/rfs/hhaf046"
method: "theory"
slug: "2025-rfs-dex-lp-commons"
source_file: "uploads/hhaf046_ec84.pdf"
status: "carded-from-first14pp"
---

# Capponi and Jia (2025) — DEX 的 LP 是公地悲剧：套利租金中位数 96% 交给验证者

DOI 在 PDF 第 1 页。和 JF Lehar–Parlour Uniswap 那张是姊妹：他们比 AMM 和订单簿，这篇把区块链排序/gas 竞价接进去。

## 问题

- 研究问题（一句）：AMM 加「按 gas 不按时序出块」，会不会让流动性提供者没法撤池躲套利，租金最后落到验证者？
- Estimand：理论为主。实证是硅谷银行危机里，波动的 USDT–USDC 相对有 PSM、更稳的 DAI–USDC，LP 撤流动性、改用更凸定价曲线。

## 识别

- 策略：理论。公开基本面冲击（不是私有信息）让 AMM 汇率偏离。LP 撤池的损失由全池分担，套利者出最高 gas 拿走全部利润。单个 LP 只愿出到自己那一份预期损失，出价比不过套利者。套利者 Bertrand 式把 gas 抬到几乎全部利润，验证者收基础设施租。作者称验证者抽成可到 100%，CEX 共址大约 30%（Budish–Lee–Shim 2019）。
- 改设计：速度技术主要把租从验证者转给快套利者；随机排序或优待 LP，验证者没动机采用；更凸曲线减套利也减成交和费，套利租高时均衡更凸。
- 实证：SVB 期间 USDT–USDC 大波动，DAI–USDC 因 Peg Stability Module 相对稳，当准实验 DID。对照 `did.md`：一次危机、两个稳定币对，不是随机分配。
- 最危险威胁：DAI 和 USDT 的机制、客户、池深度本来就不同；PSM 本身会改套利；前 14 页没有 DID 系数。

## 数据

- 链上 DEX（后文落到 Uniswap V3 调凸性）。摘要里的关键数：套利者把利润的中位数 **96%** 交给验证者（gas / 套利收入中位数 0.96）。

## 主结果

- 公地悲剧：LP 集体被套利，个体没有激励撤。
- 速度、换排序、灵活曲线，作者称减不了这些租（曲线只是让 LP 在租高时更凸）。
- SVB：波动高、套利租高时，LP 撤流动性、更多用更凸曲线。具体 DID 系数前 14 页没有，**UNVERIFIED**。
- 中位 gas / 套利收入 0.96，至少一半交易的 gas 接近全部收入。

## 可攻击点

- 主贡献是机制，SVB 只是两对稳定币的事件比较。
- 96% 是中位数比，均值、尾部、是否含失败交易，前 14 页没写。
- 「解决方案都失败」取决于验证者目标函数；现实里有排序规则实验，这篇前 14 页当验证者不采用。
- 和 Lehar–Parlour 不要合成一个「AMM 一定更贵」：设定一个是私有信息，一个是公开冲击 + gas。

## 可复用设计

- 写 DEX 成本，必须同时有 AMM 曲线和出块排序，只写 xy=k 不够。
- 公地：损失分摊、抢跑独享，用来解释「为什么知情 LP 也不撤」。
- 稳定币对里找一个有硬锚、一个没有，当波动冲击的对照，但要承认机制不同。
- 租金归谁：报 gas / 套利收入，不要只报 LP 无常损失。

## 证据指针

- 摘要、公地、中位 96%、SVB 更凸：PDF 第 1 页。
- 验证者 vs CEX 约 30%、三种改设计：PDF 第 3 页。
- USDT–USDC vs DAI–USDC DID：PDF 第 4 页。
- DID 系数：前 14 页无，UNVERIFIED。

## 训练价值

理论卡。和 `2025-jf-uniswap-amm.md` 并排。SVB 那一段若审，按一次性事件 DID 审，不要写成随机实验。
