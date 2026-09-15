---
title: "Maximal extractable value and allocative inefficiencies in public blockchains"
authors: "Agostino Capponi, Ruizhe Jia, Kanye Ye Wang"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104132
method: theory + chain
slug: mev-private-pools
source_file: uploads/1-s2.0-S0304405X25001400-main_a68a.pdf
status: carded-from-first14pp
---

# Maximal extractable value and allocative inefficiencies in public blockchains

文章编号 104132。Fuster 编辑。Capponi：Ethereum、Stellar 基金。Wang：澳门大学 APAEM、FDCT 0129/2022/A。旧题 *The Evolution of Blockchain: from Lit to Dark*。只根据 PDF 前约 14 页。

## 问题

公链结算层系统性抢跑如何浪费区块空间。私人交易池能不能减无效率。验证者不愿放弃 MEV 租金时，会不会停在部分采纳、抢跑仍在。

## 识别

理论：费用拍卖 + 内存池可见 → 抢跑。私人池可提高配置效率，但验证者和用户激励不对齐，均衡是部分采纳。经验：以太坊 Flashbots 私人池。不是随机上线私人池。最危险：用 Flashbots 的用户本来就被抢得更惨。

## 数据

Uniswap V2 等以太坊成交。含 Ether 的区块里大约 90% 有可被抢跑交易，16.1% 有已确认三明治。抢跑者每次成功大约 0.108 Ether。用户累计损失超过 13 万 Ether。

## 主结果

作者称：验证者收入更高；抢跑风险更大的用户更常用私人池；私人池里攻击者成本/收入比收敛到 1。点估计表号在后文。

## 可攻击点

- 13 万 Ether 是作者累计，汇率换算不要外推。
- Flashbots 是选择进入，不是实验。
- 资助来自以太坊生态，利益要写在卡头。
- 不要写成「私人池消除了 MEV」。

## 可复用设计

链上市场设计先写内存池可见和费用排序，再谈私人池。均衡要允许部分采纳。理论 + 链上描述卡。

证据指针：摘要（部分采纳、Flashbots）；引言（90% / 16.1%、0.108 Ether、>13 万 Ether）。

训练价值：结算层抢跑的福利。不当准实验。
