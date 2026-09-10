# papers/

每读一篇论文，或每开一个新题目，在这里放**一张结构化卡片**，不要放 PDF 全文。

## 这个目录干什么

这是长期能力的核心库存：把「读过」变成可检索的设计知识。卡片回答的是设计问题，不是文献综述作文。

已投稿、已结束的稿件不必迁入。这里服务下一篇，以及以后每一篇。

## 命名

```
YYYY-venue-slug.md
```

示例（仅为格式，不是真实文献）：`2010-wp-rd-donation.md`

没有 venue 时用 `wp`、`mimeo` 或 `notes`。

## 怎么新增

1. 复制 `templates/paper-card.md`
2. 调用 skill `literature-card`
3. 缺 DOI、缺系数、没打开 PDF，一律写 `UNVERIFIED`，不要补造

## 一张卡至少要有

- 问题与 estimand
- 识别策略与最危险威胁
- 数据粒度
- 主结果（有出处才填）
- 可攻击点
- 可复用设计（以后自己能偷什么）

## 已有卡片（JF 80(1), 2025）

只根据上传 PDF 前约 14 页做成。系数能对上引言/摘要才写入，表号对不上的标了 UNVERIFIED。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-jf-personal-communication-loan-repayments.md` | 催收电话 | IV |
| `2025-jf-equilibrium-data-mining.md` | 数据挖矿 | 理论 |
| `2025-jf-pe-failed-bank-resolution.md` | PE 接盘破产银行 | 接近出价准随机 |
| `2025-jf-scope-scale-concentration.md` | 文本范围 | IV / 文本 |
| `2025-jf-floor-trading.md` | 关交易大厅 | DID |
| `2025-jf-carbon-returns.md` | 碳收益滞后 | 组合排序 |
| `2025-jf-sms-overdraft-alerts.md` | 透支短信 | 田野实验 |
| `2025-jf-uniswap-amm.md` | Uniswap | 理论+链上 |
| `2025-jf-intermediary-leverage-shocks.md` | 杠杆供需冲击 | 符号限制 |
| `2025-jf-dynamic-competition-mortgages.md` | 按揭收割定价 | 结构 |
| `2025-jf-global-credit-spread-puzzle.md` | 全球信用利差之谜 | 结构定价 |
| `2025-jf-bank-funding-libor.md` | 授信与 LIBOR | 理论+监管数据 |
| `2025-jf-test-assets-weak-factors.md` | 弱因子与测试资产 | 方法 |

对你最有用、值得下一步 `identification-audit` 的：催收 IV、PE 接近出价、关厅 DID、透支实验。

## 已有卡片（JF 80(2), 2025）

同样只根据上传 PDF 前约 14 页。系数对得上摘要/引言才写入。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-jf-repo-financial-crisis.md` | 危机里的回购 | 描述性 |
| `2025-jf-disappearing-index-effect.md` | 消失的指数效应 | 事件研究 |
| `2025-jf-greenwashing-pollutive-plants.md` | 卖污染工厂 | DID |
| `2025-jf-work-more-pay-mortgage.md` | 月供涨了就加班 | IV |
| `2025-jf-pricing-poseidon.md` | 飓风不确定性 | DID |
| `2025-jf-simplicity-and-risk.md` | 复杂度与风险溢价 | 预注册实验 |
| `2025-jf-crisis-interventions-insolvency.md` | 破产干预 | 理论 |
| `2025-jf-designing-stress-scenarios.md` | 压力测试情景 | 理论 |
| `2025-jf-regulatory-fragmentation.md` | 监管碎片化 | 文本 |
| `2025-jf-worker-runs.md` | 工人挤兑 | 理论 |
| `2025-jf-allocation-sri-capital.md` | ESG 资本配置 | 理论 |
| `2025-jf-wealth-insurance-choices.md` | 财富与寿险 | 行政面板 |
| `2025-jf-feedback-systematic-risk.md` | 价格反馈 | 理论 |
| `2025-jf-minority-representation-mortgage.md` | 少数族裔贷款官 | IV |
| `2025-jf-hidden-effort-problem.md` | 高管隐藏努力 | IV |

对你最有用、值得下一步 `identification-audit` 的：卖厂 DID、月供 IV、贷款官排班 IV、高管天气 IV。

## 已有卡片（JF 80(3), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-jf-sunk-costs-mergers.md` | 并购沉没成本 | IV / 准实验 |
| `2025-jf-credit-cycles-crises.md` | 危机信用周期 | 宏观预测 |
| `2025-jf-collusion-brokered-markets.md` | 中介合谋 | 理论 |
| `2025-jf-banks-low-rates.md` | 低利率与银行信贷 | 理论+事实 |
| `2025-jf-intrahousehold-disagreement.md` | 夫妻宏观分歧 | 预注册实验 |
| `2025-jf-excess-capacity-marginal-q.md` | 闲置产能与 q | 测度 |
| `2025-jf-social-security-wealth-inequality.md` | 社保与财富份额 | 测度 |
| `2025-jf-racial-bias-mortgage-aus.md` | 房贷拒绝与色盲算法 | 分解 |
| `2025-jf-covenants-collateral.md` | 契约与抵押 | 理论 |
| `2025-jf-auctions-vs-negotiations.md` | 拍卖还是谈判 | 理论 |
| `2025-jf-overdraft-payday.md` | 透支排序与发薪贷 | DID |
| `2025-jf-investor-syndicates-communication.md` | 辛迪加沟通 | 理论 |

对你最有用、值得下一步 `identification-audit` 的：沉没成本准实验、透支诉讼 DID、夫妻预期实验。房贷拒绝分解请和 80(2) 贷款官 IV 对照着读。

## 不要放

- PDF（放到本机 `notes/pdfs/`，默认不提交）
- 完整读书笔记（长文去 `notes/`，这里只留卡片）
- 虚构文献条目
