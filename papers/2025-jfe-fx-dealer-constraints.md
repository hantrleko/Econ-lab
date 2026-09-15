---
title: "Constrained liquidity provision in currency markets"
authors: "Wenqian Huang, Angelo Ranaldo, Andreas Schrimpf, Fabricius Somogyi"
year: 2025
venue: Journal of Financial Economics 167
doi: 10.1016/j.jfineco.2025.104028
method: microstructure / SVAR
slug: fx-dealer-constraints
source_file: uploads/1-s2.0-S0304405X25000364-main_acd4.pdf
status: carded-from-first14pp
---

# Constrained liquidity provision in currency markets

文章编号 104028。开放获取 CC BY。Roussanov 编辑。Huang / Schrimpf 当时在国际清算银行。Ranaldo：SNSF 182303。只根据 PDF 前约 14 页。

## 问题

外汇现货里，交易商资产负债表一紧，流动性成本会不会相对成交量不成比例地上升？这种非线性是供给弹性变陡，还是需求在变。

## 识别

先写流动性供需的简约模型：融资成本 η 和一部分交易商碰到的 VaR 上限 ω 让供给曲线变陡。两个价格：三角套汇中间价偏离（VLOOP，影子成本）和来回交易成本（TCOST）。数量是交易商中介的成交量。经验：用 10 家主要外汇交易商的融资成本、组合 VaR、当季 VaR 违约次数的第一主成分做 DCM。平滑转移回归（LSTAR）让「约束区制」内生。作者用时间/截面固定效应、波动和价格冲击控需求；再用带符号限制的 SVAR 拆供给冲击和需求冲击。对照 `references/methods/iv.md`：这里没有制度工具，符号限制是结构假设。约束紧的时候宏观波动也在变，DCM 可能和需求一起动。

## 数据

CLS 全球外汇现货成交。引言后文写样本约 2011 年 11 月–2022 年 9 月；有的回归从 2012 年 9 月 1 日到 2022 年 9 月 30 日。也看远期、掉期，并对照国债市场「波动与流动性成本」的类似非线性。

## 主结果

VLOOP 与 TCOST 同向，相关约 54%。交易商不太紧时，流动性成本与中介量正相关约 9%–25%。约束紧时，成本相对量升得更狠，条件相关至少降一半。作者称 SVAR 里只有流动性供给冲击能解释这段相关的变化，需求冲击不能。远期和掉期上机制更强。

## 可攻击点

- DCM 是 10 家银行约束的共同成分，和全球风险偏好、波动一起动。
- LSTAR 的区制由同一套价格/量数据长出来，非线性可能被过拟合。
- 符号限制 SVAR 把「供给」定义成作者想要的符号，不是随机约束冲击。
- VLOOP 不是可执行利润；TCOST 更大时中间价偏离仍可在无套利带内。
- 前 14 页没有可核对的回归系数和标准误。

## 可复用设计

OTC 流动性不要只回归价差对杠杆。同时看价格和中介量，再问相关在约束紧时是否断掉。约束度量尽量对应模型里的融资成本和 VaR，而不是只丢一个中介杠杆因子。把结果写成「供给弹性变陡」时，必须另有需求侧对照。相关卡，不当准实验。

证据指针：摘要（成本相对量不成比例上升；供给弹性而非需求）；引言（VLOOP / TCOST、相关 9–25% 与至少降一半、CLS、LSTAR / SVAR）；后文（约 2011-11–2022-09）。

训练价值：约束下的价量非线性。中介资产定价的描述设计，不是 IV。
