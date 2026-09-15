---
title: "Robustness and dynamic sentiment"
authors: "Pascal J. Maenhout; Andrea Vedolin; Hao Xing"
year: "2025"
venue: "Journal of Financial Economics 163"
doi: "10.1016/j.jfineco.2024.103953"
method: "theory"
slug: "2025-jfe-robustness-dynamic-sentiment"
source_file: "uploads/1-s2.0-S0304405X24001764-main_a96f.pdf"
status: "carded-from-first14pp"
---

# Maenhout, Vedolin, and Xing (2025) — Cressie–Read 稳健控制里，情绪自己会随冲击走

文章编号 103953。Papanikolaou 编辑。数据链接在 PDF 第 1 页。INSEAD 中东校区 / BU Questrom；Vedolin 兼 NBER、CEPR。

## 问题

- 研究问题（一句）：调查预期误差一会儿乐观一会儿悲观，稳健控制能不能内生出这种波动，而不是只给出一成不变的最坏信念？
- Estimand：不是因果。校准后看主观信念、风险厌恶、组合权重和均衡资产收益能不能同时对上 SPF 调查和股市特征。

## 识别

- 策略：理论。Hansen–Sargent 稳健控制里，用 Cressie–Read (1984) 散度替换相对熵，并构造保持递归性和位似性的动态差异度量。η → 1 时退回相对熵；η 管信念扭曲要不要跨期抹平。
- η < 1：正冲击后更不悲观 / 更乐观，情绪顺周期，像动量。η > 1：正冲击后更悲观，像反转。情绪波动对正负冲击不对称。
- 校准：SPF 一致（中位）GDP 预报减去 VAR(2) 客观预报，当作信念扭曲；假定调查答案就是主观信念。代表代理人 Epstein–Zin + Cressie–Read。
- 最危险威胁：调查答案不等于交易用信念；VAR(2) 被当成「客观」会把模型误设写进情绪。

## 数据

- 图 1：1990Q1–2019Q4，同比实际 GDP、SPF 一季前一致预报、用 GDP / 失业率 / 联邦基金利率 / 通胀估的 VAR(2)。灰色条是 NBER 衰退。
- 校准用同一套调查扭曲，再对资产价格做数量匹配。点估计表号在后文。

## 主结果

- 扭曲信念给出逆周期风险厌恶、顺周期组合权重、逆周期均衡资产收益。
- 校准后，时变情绪能对上股权风险溢价和 Sharpe；悲观态溢价和波动更高、无风险利率更低，乐观态相反。
- 信念楔对股权收益有长视野预报力；作者称校准模型里的回归系数和数据对齐（具体系数前 14 页没有，UNVERIFIED）。
- 用模型跑预报误差对 GDP 实现值的回归，能复制 Kohlhas–Walther (2021) 的负系数，作者读成顺周期主观信念，不必另加过度反应。

## 可攻击点

- 相对熵在 i.i.d. 冲击下信念扭曲是短视、常数；换散度是为了对上「波浪」，不是从数据里估出 η。
- 「调查 = 主观信念」写在脚注里，作者自己承认没有调查答题模型。
- 资产价格匹配是校准，不是识别。不要写成发现了情绪因果定价。
- 乐观嵌的是 Bhandari et al. (2024) 式机制 + 区制转换，识别不了是哪一块在干活。

## 可复用设计

- 调查预报减统计预报当情绪状态，再拿去校准，比事后编一个情绪因子干净。
- 要动态悲观/乐观，先问散度是不是状态依赖；相对熵往往给不出波浪。
- 和同辑 Goldstein 信息分享、Horvath recovery 并排：都是信念 / 测度，不要合成「JFE 这期发现了情绪」。

## 证据指针

- 摘要、逆周期风险厌恶：PDF 第 1 页。
- Fig. 1、SPF − VAR(2)：PDF 第 1–2 页。
- η 与动量/反转：PDF 第 2 页。
- 校准匹配溢价、Kohlhas–Walther：PDF 第 3 页。
- 预报回归具体系数：前 14 页没有，UNVERIFIED。

## 训练价值

资产定价理论卡。不是准实验审计对象。以后写「时变悲观」先问散度是不是状态依赖。
