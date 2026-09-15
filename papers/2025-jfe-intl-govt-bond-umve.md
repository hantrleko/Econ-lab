---
title: "Pricing and constructing international government bond portfolios"
authors: "Otto Randl, Giorgia Simion, Josef Zechner"
year: 2025
venue: Journal of Financial Economics 173
doi: 10.1016/j.jfineco.2025.104152
method: SDF / portfolio
slug: intl-govt-bond-umve
source_file: uploads/Pricing-and-constructing-international-governmen_2025_Journal-of-Financial-E_35b7.pdf
status: carded-from-first14pp
---

# Pricing and constructing international government bond portfolios

文章编号 104152。开放获取 CC BY。Zechner 通讯。WU / VGSF。只根据 PDF 前约 14 页。

## 问题

对冲汇率后的发达国家国债组合，随机贴现因子是什么。定价风险和收益的共同因子是不是一回事。对冲未定价风险能不能提高夏普。

## 识别

不是实验。把对冲后国债超额收益投影到无条件均值–方差有效（UMVE）组合上得到 SDF。预期收益用远期利差和实际收益率，协方差用收缩的时变矩阵。检验：UMVE 能否定价各国市场和动态策略；与货币 SDF 是否正交。组合卡。

## 数据

G10* 十个主要发达主权债市场，约占本币债务全球市值 70%。头寸用当地货币市场融资，等价于远期对冲。

## 主结果

UMVE 夏普超过 1，各国市场平均夏普 0.46。预期夏普在危机和通胀离散高时升高。前 3 个主成分解释收益方差 86%，但全部 PC 只解释 UMVE 收益大约 30%。对冲未定价风险后，1/N 等策略夏普明显提高；绝对权重受限仍大体稳健，只做多则差很多。点估计表号在后文。

## 可攻击点

- UMVE 用了预期收益模型，样本内拟合成分重。
- G10* 不是新兴市场。
- 「未定价」相对这个 SDF，换定价核可能翻。
- 不要写成「国债没有共同风险」。

## 可复用设计

国际债不要和货币因子混成一个 SDF。先报对冲后超额收益。共同因子（PCA）和定价因子（UMVE）分开。对冲未定价风险时同时报权重约束。

证据指针：摘要（夏普翻倍以上、危机和通胀离散、对冲未定价风险）；引言（0.46 → >1、3 PC 占 86% 方差但只解释 UMVE 约 30%）。

训练价值：国际债 SDF。不当准实验。
