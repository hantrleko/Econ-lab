---
title: "Collateral value uncertainty and mortgage credit provision"
authors: "Erica Xuewei Jiang, Anthony Lee Zhang"
year: 2025
venue: Journal of Financial Economics 169
doi: 10.1016/j.jfineco.2025.104054
method: IV / structural
slug: house-value-uncertainty
source_file: uploads/1-s2.0-S0304405X25000625-main_8f87.pdf
status: carded-from-first14pp
---

# Collateral value uncertainty and mortgage credit provision

文章编号 104054。Whited 编辑。Fama–Miller。TransUnion 有权预审以免误述。只根据 PDF 前约 14 页。对照 `references/methods/iv.md`。

## 问题

房价更难估的房子，按揭是不是更难批、利率更高、贷价比更低。是回收率渠道，还是评估噪声让监管 LTV 更容易绑住。电脑评估会怎样。

## 识别

价值不确定：特征价格模型残差（2000–2020 美国成交）。相关：拒绝、利率、贷价比。工具：相对本地房库的异质性（更不标准 → 市场更薄 → 离散更高）。作者称工具与买方事前信用无关，工具化离散也不预测事后违约。对照 `iv.md`：排他是「房子不像邻居只通过评估/回收影响信贷，不通过买方选择」。结构模型把回收渠道和评估监管渠道拆开。不是随机评估改革。

## 数据

美国住宅成交与按揭，2000–2020。评估相对成交价。高离散地区更多低收入和少数族裔。

## 主结果

价格离散高 1 个标准差：与抵押相关的拒绝大约多 25%，总拒绝大约多 10%；利率大约高 0.9 个基点；贷价比大约低 20 个基点。作者称工具结果支持「房子是更差抵押」而不是「买方更差」。结构用来量化两渠道和电脑评估的反事实。点估计表号在后文。

## 可攻击点

- 异质性工具仍可能和街区收入、维修、保险同向。
- 0.9 个基点很小，经济意义主要在拒绝。
- 结构评估偏差和毁约固定成本是校准。
- 分配含义是相关地理，不是种族实验。

## 可复用设计

抵押质量不要只写 LTV。先报价格离散，再找一个与买方信用无关的房屋异质性工具。监管评估渠道要单独写，才能谈电脑评估。IV + 结构，不是 RD。

证据指针：摘要（两渠道、电脑评估）；引言（1 SD → 拒绝 +25% / +10%，利率 +0.9bp，LTP −20bp）。

训练价值：评估噪声如何变成信贷约束。可与 168 卷 MEW 种族差距并排：一个是房子难估，一个是申请人被拒。
