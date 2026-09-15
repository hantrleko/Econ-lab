---
title: "Revenue collapses and the consumption of small business owners in the COVID-19 pandemic"
authors: "Olivia S. Kim, Jonathan A. Parker, Antoinette Schoar"
year: 2025
venue: Journal of Financial Economics 170
doi: 10.1016/j.jfineco.2025.104079
method: IV / 2SLS
slug: sme-covid-consumption
source_file: uploads/1-s2.0-S0304405X2500087X-main_ce7d.pdf
status: carded-from-first14pp
---

# Revenue collapses and the consumption of small business owners in the COVID-19 pandemic

文章编号 104079。Whited 编辑。JPMorgan Chase Institute 去识别账户；观点不代表摩根大通。Kauffman Knowledge Challenge。只根据 PDF 前约 14 页。对照 `references/methods/iv.md`。

## 问题

疫情里小企业营收塌了，老板家庭消费跟不跟。跟的是本县感染和居家令，还是全国冲击。一块钱营收损失会漏多少消费。

## 识别

描述：全国紧急状态后营收大约掉 40%，主要是全国因子。县新感染 1 个标准差，营收大约多掉 0.5%；州居家令大约再掉 11% 营收、5.4% 老板消费。传导：同一县–月内，四位 NAICS × 当地感染/居家令当营收工具，县 × 时间固定效应吸掉当地对家庭的直接冲击。对照 `iv.md`：排他是「行业–当地交互只通过本店营收进老板消费」。最危险：重创行业同时改老板时间、本地可消费场景和行业特定补贴。不是随机疫情。

## 数据

摩根大通小企业与老板支票/卡账户，2019-01 至 2021-09 月度面板。覆盖不少无雇工企业。全国紧急状态：2020-03-13。

## 主结果

一块钱营收（费用）损失，老板消费大约只少 1.6（2.6）分。封锁期营收相对疫前大约月均 −2400 美元，对应消费大约 −36 美元，不到当月消费变化（约 396 美元）的 10%。疫苗后传导大约翻倍。作者归到联邦补贴和可消费场景变少。点估计表号在后文。

## 可攻击点

- 行业–当地工具仍可能直接改老板消费篮子。
- 样本是摩根大通客户，不是全国随机小企业。
- 1.6 分是疫情 MPC，不要写成平常小企业 MPC。
- 补贴机制是时间对上，不是随机发放实验。

## 可复用设计

把企业账户和老板账户对上，才能写「店的冲击」和「家的消费」。当地公共冲击用县–时 FE 拿掉后，再用行业暴露做工具。同时报全国因子 vs 当地政策。IV 卡。

证据指针：摘要（40%、1.6 分）；引言（感染 0.5%、SIP 11%/5.4%、−2400 / −36 / 396）。

训练价值：企业收入如何漏到老板消费。可跑识别审计。
