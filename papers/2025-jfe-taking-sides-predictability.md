---
title: "Taking sides on return predictability"
authors: "R. David McLean, Jeffrey Pontiff, Christopher Reilly"
year: 2025
venue: Journal of Financial Economics 173
doi: 10.1016/j.jfineco.2025.104158
method: predictability
slug: taking-sides-predictability
source_file: uploads/Taking-sides-on-return-predictability_2025_Journal-of-Financial-Economics_bf32.pdf
status: carded-from-first14pp
---

# Taking sides on return predictability

文章编号 104158。Roussanov 编辑。版权保留。对冲基金识别数据来自多位学者。只根据 PDF 前约 14 页。

## 问题

九类市场参与者（零售、空头、公司发行、六类机构）相对 193 个预测变量合成的预期收益，是站在聪明钱一边还是对着做。谁的交易本身还能预测收益。

## 识别

不是实验。自适应 group LASSO 把 193 个已知预测元收成一个预期收益。看持仓变化在预测元构造前 1/3 年和后 3 个月是否同向。再把交易与预期收益交叉五分位。可预测/描述卡。

## 数据

美股截面。参与者：零售、空头、公司净发行、共同基金、对冲基金、银行、保险、财富管理、其他机构（作者称多为独立账户/CIT）。

## 主结果

公司发行最对齐：低预期收益股票过去 3 年发行最多，193 个变量解释发行截面 36%。其次是空头。零售最差：低预期收益股票零售增持最多，3 年零售交易被解释 32%。周度零售不平衡仍按 Boehmer et al. (2021) 方向预测，且在五个预期收益分位都在；三年加总零售只在两端预测为负。机构总体对着高预期收益股票卖，事后这些股票表现好。预期收益的预测力在零售交易更密的股票更强。点估计表号在后文。

## 可攻击点

- 193 个预测元是事后已知宇宙，不是交易当时的信息集。
- 「聪明」= 对齐这个合成信号，不是私有信息。
- 机构分类依赖 13F 与作者的对冲基金名单。
- 不要写成「零售造成全部异象」。

## 可复用设计

问谁在交易异象时，把公司和零售加进去，不要只报机构合计。周度流和多年持仓变化分开报。交叉排序看预测力是不是只在两端。

证据指针：摘要（公司/空头聪明、零售对着做）；引言（36% 发行、32% 零售、周度流正交）。

训练价值：可预测的交易对手。不当准实验。
