---
title: "Robust difference-in-differences analysis when there is a term structure"
authors: "Kjell G. Nyborg, Jiri Woschitz"
year: 2025
venue: Journal of Financial Economics 170
doi: 10.1016/j.jfineco.2025.104081
method: methods / DiD
slug: did-term-structure
source_file: uploads/1-s2.0-S0304405X25000893-main_112a.pdf
status: carded-from-first14pp
---

# Robust difference-in-differences analysis when there is a term structure

文章编号 104081。开放获取 CC BY-NC-ND。Whited 编辑。瑞士国家科学基金会 100018_172679。数据：Mendeley `10.17632/j4fgvbrghv.1`（未点开核验）。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

结果变量有期限结构（收益率、利差、贷款利率、隐含波动、期货）时，经典证券–时间双向固定效应 DID 会不会就算随机分组也设错。处理效应本身有没有期限结构。

## 识别

方法论文，不是一个政策实验。经典 DID 假定每个证券的非处理路径是固定的；期限结构天天动、处理组和控制组剩余期限对不上时，OLS 正交条件破。长窗口还有曲线滚动。作者手检三大金融期刊 21 篇期限结果 DID：没有一篇估处理的期限结构；两篇试图按剩余期限配对，描述统计仍差大约 1–2 年。十五篇加期限控制，作者称有时更糟。国债月度 10 年–3 月期限利差变化：2000–2022 年标准差中位大约 31 bp，美国绝对变化均值大约 23 bp，可能盖过单位数 bp 的真效应。

## 数据

模拟期限结构。十二国国债（Bloomberg）作数量级。真实例子在后文第 8 节，前 14 页未核。

## 主结果

作者给两套修法。(1) 零息：用处理/控制、事前/事后四条参数曲线代替证券和时点 FE，一次回归出「Delta 曲线」，即处理效应的期限结构。(2) 附息或零息：半合成匹配，给每只处理券配同票息、同剩余期限的合成控制，再沿期限看。零息且函数形式一致时，两步等于一步。标准按均值画的事前趋势，期限对不齐也会骗人。组间截面同样有期限污染。

## 可攻击点

- 21 篇清单是作者手检，前 14 页没有逐篇核对。
- 模拟数据里的「假效应」大小依他们的数据生成过程。
- Delta 曲线仍要函数形式；半合成控制仍要曲线估计。
- 不是 Callaway–Sant’Anna 那类错时论文。

## 可复用设计

凡是收益率 DID，先问剩余期限有没有配对，再决定是报平均处理还是处理的期限结构。不要只加一个期限控制交差。可偷：灵活曲线 DID、半合成匹配、按期限桶画趋势。方法卡。

证据指针：摘要（随机分组也会错、要估处理的期限结构）；引言（21 篇、31 / 23 bp、两种修法）。

训练价值：做债券/贷款 DID 前先读。不当一篇实证贡献。
