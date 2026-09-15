---
title: "Price regulation in two-sided markets: Empirical evidence from debit cards"
authors: "Vladimir Mukharlyamov, Natasha Sarin"
year: 2025
venue: Journal of Financial Economics 172
doi: 10.1016/j.jfineco.2025.104094
method: DID / threshold
slug: durbin-debit
source_file: uploads/1-s2.0-S0304405X25001023-main_15db.pdf
status: carded-from-first14pp
---

# Price regulation in two-sided markets: Empirical evidence from debit cards

文章编号 104094，印在 172 卷。开放获取 CC BY。Whited 编辑。只根据 PDF 前约 14 页。对照 `references/methods/did.md`。

## 问题

多德–弗兰克 Durbin 修正案把借记卡交换费压到「合理且与成本成比例」后，银行、商户和消费者怎么调。双边市场里压一边价格，会不会从免费支票账户和信用卡那边补回来，从而达不到「零售价下降」的目标。

## 识别

资产超过 100 亿美元的银行受监管，更小的豁免。比较受监管 vs 豁免银行的交换收入、免费支票、月费和最低余额。作者称受监管银行交换收入大约少 30%（年约 82 亿美元）。信用卡替代：受监管银行网点/存款更多的 ZIP 借记份额掉、信用卡用得更多、低收入更易循环余额——作者写明这三段不建立因果。对照 `did.md`：同一时点、按规模门槛分组，不是错时。最危险：100 亿门槛两边的银行本来产品组合就不同；2010 后还有别的危机后改革。

## 数据

银行交换收入、支票账户价目。借记/信用卡使用的地理变异。

## 主结果

受监管银行把大约 14% 的 Durbin 损失转给客户：免费支票从 2010Q2 的 58% 降到 2011Q4 的 28%（2013Q4 为 20%）；月费从 4.30 美元到 6.65（7.62）美元；免月费最低余额从 1049 美元到 1399（1339）美元。低收入更常交月费，有人销户变成无银行账户。商户借记费降了，能否传到零售价，作者称相对总销售太小，看不清。点估计表号在后文。

## 可攻击点

- 规模门槛 DID 不是随机监管。
- 信用卡替代作者自己说不是因果。
- 「零售价」主目标没有可核对的估计。
- 不要写成「Durbin 一定伤害消费者」。

## 可复用设计

双边市场监管要同时报：被压的那一边、补贴的那一边、以及可替代的未监管产品。门槛豁免当对照。账户捆绑是第一威胁。可跑识别审计。

证据指针：摘要（银行向消费者收费、信用卡或抵消商户节省）；引言（82 亿、14%、免费支票 58%→28%）。

训练价值：支付监管在双边市场怎么被绕开。可跑识别审计。
