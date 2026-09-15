---
title: "How valuable is corporate adaptation to crisis? Estimates from Covid-19 work-from-home announcements"
authors: "Adlai Fisher, Jiří Knesl, Ryan C.Y. Lee"
year: 2025
venue: Journal of Financial Economics 174
doi: 10.1016/j.jfineco.2025.104168
method: event study + matching
slug: covid-wfh-announcements
source_file: uploads/How-valuable-is-corporate-adaptation-to-crisis--Estima_2025_Journal-of-Finan_13f0.pdf
status: carded-from-first14pp
---

# How valuable is corporate adaptation to crisis?

文章编号 104168。开放获取 CC BY。Papanikolaou 编辑。NUS RMI 违约概率；NSERC。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

危机里企业**宣布**适应（自愿居家办公）值多少钱、改不改风险。相对事前特征相似、但未早宣布的公司。

## 识别

事件研究 + 匹配，不是随机适应。处理：2020-01-20 至 2020-03-19（加州首个州封锁前）公司网站自愿 WFH 公告日。样本：CRSP 美股 2549 家，其中 273 家早宣布。对照：特征匹配的未宣布者。事前预测：劳动适合度（Dingel–Neiman；Papanikolaou–Schmidt）、规模；6142 组预测里最优模型都含 PS。CAR：事件窗虚拟、相对基准差分、Patell / Kolari–Pynnönen。风险：市场 beta、PS 劳动不灵活因子、Duan 等违约概率。Bloomberg 报道（273 里 68 家）加快价格吸收。最危险：能早宣布的公司本身更适合远程、更健康；公告 ≠ 落实；对照也可能已私下实施。作者用信息不对称实物期权解释选择，并把 CAR 写成下界。

## 数据

Google API + 词表爬网站，人工核日戳。事前 10-K 主题（远程、韧性、数字化）。经营表现跟到 2023 财年。

## 主结果

公告后五日 CAR 大约 3%–5% 市值；事前窗不显著。宣布组合相对匹配组合，市场与 PS 因子暴露下降。Bloomberg 覆盖者日超额大约 1–1.5%，吸收更快。疫情期相对匹配：研发与雇员增长为正。点估计在引言与第 3 节。

## 可攻击点

- 选择：PS/规模已预测谁宣布，匹配吃不掉未观测适应能力。
- 公告日测量：网站改版、私下通知员工。
- 同时新闻（流动性、分红）可能叠在同一窗。
- 市场已预期科技股 WFH。
- 不要把 3%–5% 写成「适应的因果回报」。

## 可复用设计

适应价值先写谁选择宣布，再写 CAR。媒体速度当信息扩散，不当处理。事件研究审事前可预测性。可跑识别审计。

证据指针：摘要（3%–5%、风险降、Bloomberg 更快）；引言（2549 / 273、封锁前自愿、PS 预测）。

训练价值：中。宣布适应 ≠ 适应。
