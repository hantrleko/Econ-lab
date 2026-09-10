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

## 已有卡片（JF 80(4), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-jf-proxy-advisor-controversy.md` | 代理顾问制造争议 | 理论 |
| `2025-jf-ceo-pay-tax-windfalls.md` | 减税横财与 CEO 薪酬 | 三重差分 |
| `2025-jf-order-by-order-auctions.md` | 零售单逐笔拍卖 | 理论 |
| `2025-jf-vc-startup-agglomeration.md` | VC 与创业扎堆 | DID |
| `2025-jf-us-lucky-survivor.md` | 美股幸存偏差 | 贝叶斯测度 |
| `2025-jf-dynamic-banking-deposits.md` | 存款的动态价值 | 理论 |
| `2025-jf-women-hospital-ceos.md` | 医院女 CEO | 描述+匹配 |
| `2025-jf-regulating-otc.md` | 监管 OTC | 理论 |
| `2025-jf-privatization-worker-costs.md` | 私有化的工人成本 | stacked DID |
| `2025-jf-euro-term-structure.md` | 异质货币联盟曲线 | 校准 |
| `2025-jf-interlocking-directorates-banks.md` | 银行连锁董事 | DID |
| `2025-jf-value-of-bank-lending.md` | 银行放贷的价值 | 测度 |

对你最有用、值得下一步 `identification-audit` 的：沃尔克规则 VC DID、意大利连锁董事 DID、瑞典私有化 stacked DID。减税横财三重差也值得看「不对称奖罚」怎么写。

## 已有卡片（JF 80(5), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-jf-superstar-housing-returns.md` | 超级城市住房收益 | 测度 |
| `2025-jf-arbitrage-capital-mmf.md` | MMF 改革与套利资本 | IV |
| `2025-jf-investor-factors.md` | 投资者因子 | 资产定价 |
| `2025-jf-forest-cross-sections.md` | 用树做股票截面 | 方法 |
| `2025-jf-competitive-executive-pay.md` | 竞争性高管薪酬 | 理论 |
| `2025-jf-executive-finance-education-rct.md` | 高管金融课 | RCT |
| `2025-jf-baby-booms-housing.md` | 婴儿潮与房价 | 人口预测 |
| `2025-jf-classified-boards-evolution.md` | 分类董事会三十年 | 治理史 |
| `2025-jf-persuading-investors-video.md` | 路演视频说服 | 相关+实验 |
| `2025-jf-saving-cause-borrowing.md` | 储蓄会不会逼出借贷 | 田野实验 |
| `2025-jf-otc-nonstandardized-assets.md` | 非标准化 OTC | 理论 |
| `2025-jf-tdf-retirement-portfolios.md` | 默认 TDF 与组合 | DID |
| `2025-jf-actual-retail-price.md` | 真实零售成交价 | 同步下单 |
| `2025-jf-segmented-arbitrage.md` | 分割的套利 | 描述 |

对你最有用、值得下一步 `identification-audit` 的：莫桑比克高管金融课 RCT、墨西哥储蓄短信实验、MMF 改革 Bartik IV、默认 TDF 的同雇主前后比较、同步下单测零售价。

## 已有卡片（JF 80(6), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-jf-cyberattack-payments.md` | 支付系统网络攻击 | DID |
| `2025-jf-schumpeter-political-connections.md` | 政治关联与大企业更替 | 长期描述 |
| `2025-jf-war-discourse-returns.md` | 战争话语因子 | 文本定价 |
| `2025-jf-credit-line-channel.md` | 授信挤出期限贷款 | KM + 模型 |
| `2025-jf-privacy-team-incentives.md` | 私下合同与团队层级 | 理论 |
| `2025-jf-ceo-stress-aging.md` | CEO 压力、衰老与死亡 | DID |
| `2025-jf-esg-news-cash-flows.md` | ESG 新闻与现金流 | 预测修订 |
| `2025-jf-green-window-dressing.md` | 绿色窗饰 | 披露窗 |
| `2025-jf-rrp-tbill-intermediation.md` | RRP 与短券中介 | 供给需求 |
| `2025-jf-anomalies-short-sale-costs.md` | 借券费与异常 | 测度 |
| `2025-jf-bank-ipo-risk.md` | 银行上市与冒险 | DID + IV |
| `2025-jf-plantation-mbs-reputation.md` | 种植园 MBS 与声誉 | 历史 |
| `2025-jf-long-horizon-fx-expectations.md` | 两年期汇率预期 | 调查预测 |
| `2025-jf-value-without-employment.md` | 有市值少雇人 | 宏观模型 |

对你最有用、值得下一步 `identification-audit` 的：撤回 IPO 对照的银行上市 DID、支付系统网络攻击 DID、授信提取的 Khwaja–Mian、CEO 行业困境 DID。反收购寿命那一段按错时标准审。

## 已有卡片（RFS 38(1), 2025）

同样只根据上传 PDF 前约 14 页。这批 DOI 前缀是 `hhae`，期刊是 *Review of Financial Studies*，不是卫生经济学。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-fx-hedging-channel.md` | 汇率套保渠道 | 模型+事实 |
| `2025-rfs-fxd-hedging-exports.md` | 银行 FXD 供给与出口 | DID |
| `2025-rfs-pension-discount-curve.md` | 养老金贴现曲线与需求弹性 | IV |
| `2025-rfs-duration-corporate-bonds.md` | 公司债久期调整 | 测度 |
| `2025-rfs-oligopoly-investment-returns.md` | 寡头合谋与投资收益 | 理论 |
| `2025-rfs-dynamic-market-making.md` | 动态做市与双 U 形 | 理论 |
| `2025-rfs-brand-premium.md` | 品牌溢价 | 测度 |

对你最有用、值得下一步 `identification-audit` 的：韩国 FXD 资本监管 DID、荷兰 UFR 贴现曲线改革当需求 IV。

## 已有卡片（RFS 38(2), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-bond-fund-treasury-liquidity.md` | 债基流动性管理与国债脆弱 | DID |
| `2025-rfs-deconstruct-yield-curve.md` | 收益率曲线自助法 | 计量 |
| `2025-rfs-gold-investment-value.md` | 黄金的投资价值 | 无套利 |
| `2025-rfs-war-disaster-premium.md` | 战争话语与市场溢价 | 文本定价 |
| `2025-rfs-loan-spreads-activity.md` | 贷款利差预报实体 | 预测 |
| `2025-rfs-house-prices-rents.md` | 房价与租金去均值 | 测度 |
| `2025-rfs-household-financial-distress.md` | 家庭财务困境与冲击 | 结构 |

对你最有用、值得下一步 `identification-audit` 的：2017 年 SEC 流动性规则下的债基–国债 DID。战争话语这篇和 JF 80(6) 截面那篇是姊妹篇。

## 已有卡片（RFS 38(3), 2025，大数据专刊）

同样只根据上传 PDF 前约 14 页。`hhad074` 是这一辑里提前发表的一篇。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-big-data-next-chapter.md` | 专刊导论 | 目录 |
| `2025-rfs-odd-lot-quotes.md` | NBBO 内的零股报价 | 测度 |
| `2025-rfs-news-sdf-high-frequency.md` | 高频 SDF 与新闻 | 文本定价 |
| `2025-rfs-missing-data-asset-pricing.md` | 定价面板缺失（GMM） | 方法 |
| `2025-rfs-missing-financial-data.md` | 财务特征系统缺失 | 插补 |
| `2025-rfs-news-social-networks.md` | 社交中心度与盈余反应 | 相关 |
| `2025-rfs-valuing-financial-data.md` | 金融数据估值 | 充分统计量 |
| `2025-rfs-fractional-trading.md` | 碎股交易 | DID |

对你最有用、值得下一步 `identification-audit` 的：碎股开通的高价/低价股 DID。两篇缺失数据并排读。导论不当发现引用。

## 已有卡片（RFS 38(8), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-near-rational-ha-models.md` | 异质主体近理性验证 | 计算 |
| `2025-rfs-sovereign-debt-holders.md` | 谁持有主权债 | 需求系统 |
| `2025-rfs-esg-modigliani-miller.md` | ESG-MM | 理论 |
| `2025-rfs-intermediation-exchange-rates.md` | 中介与汇率 | 理论 |
| `2025-rfs-higher-order-beliefs.md` | 高阶信念投机 | 调查+模型 |
| `2025-rfs-ipo-profitability-europe.md` | 欧洲上市与盈利 | IV |

对你最有用、值得下一步 `identification-audit` 的：欧洲 IPO 完成/撤回 + 询价窗 30 天行情 IV。和 JF 银行上市那张对照。

## 已有卡片（RFS 38(5), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-opioid-firm-investment.md` | 阿片与企业投资 | IV |
| `2025-rfs-build-or-buy-hc.md` | 人力资本远就买 | IV |
| `2025-rfs-infrastructure-expropriation.md` | 侵占阴影下的基建融资 | 理论 |
| `2025-rfs-shadow-cost-collateral.md` | 抵押的影子成本 | bunching |
| `2025-rfs-loan-cross-subsidization.md` | 危机贷款交叉补贴 | 事件 |
| `2025-rfs-margin-credit-china.md` | 融资融券与股价 | RD |
| `2025-rfs-hca-qe-lending.md` | 历史成本会计挡住 QE | DID |

对你最有用、值得下一步 `identification-audit` 的：中国融资标的公式 RD（预期会把事件研究洗成零），以及 SBA 灾贷门槛 bunching。阿片那张的医生开药 IV 也可以审。

## 已有卡片（RFS 38(6), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-investor-memory.md` | 自选投资的记忆美化 | 实验 |
| `2025-rfs-memory-moves-markets.md` | 重叠披露的联想记忆 | 事件 |
| `2025-rfs-predictability-experiment.md` | 信号有用才听信念 | 实验 |
| `2025-rfs-earnings-extrapolation.md` | 季初外推与市场可预测 | 时间序列 |
| `2025-rfs-option-ipca.md` | 期权异象的 IPCA | 因子 |
| `2025-rfs-short-term-debt-governance.md` | 短债锁住大股东 | 理论 |

对你最有用、值得下一步 `identification-audit` 的：Charles 的 Pattern firm 日历重叠。两篇记忆并排读。Guo 的「有新闻月」切开无条件自相关，是讲故事用的，不是准实验。

## 已有卡片（RFS 38(7), 2025）

同样只根据上传 PDF 前约 14 页。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-token-platform-coordination.md` | 代币解开平台协调 | 理论 |
| `2025-rfs-pow-pos-security.md` | PoW 对 PoS 安全 | 理论 |
| `2025-rfs-insurer-information-competition.md` | 知情保险公司装傻 | 理论 |
| `2025-rfs-insurance-hedging-competition.md` | 衍生品优先与寿险竞争 | DID |
| `2025-rfs-imperfect-hedging-costs.md` | 交易成本与套保波动 | 理论 |
| `2025-rfs-steel-futures-competition.md` | 钢材期货进现货竞争 | DID |
| `2025-rfs-uncertainty-incentive-contracts.md` | 不确定与部门股权激励 | 理论 |

对你最有用、值得下一步 `identification-audit` 的：寿险 IRMA 711 错时 DID（作者自己写了从未处理对照和现代估计量），以及钢材期货两个开通日。两张都是套保成本下降接到产品市场价格。

## 已有卡片（RFS 38(9), 2025）

同样只根据上传 PDF 前约 14 页。这是 38(9) 的一部分：页码从 2517 起。**2602–2651 仍缺一篇**（未上传）。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-pe-pollution-liability.md` | PE 与环境责任 | DID |
| `2025-rfs-pe-fund-alpha.md` | 单基金 PE 的 α | 测度 |
| `2025-rfs-competition-innovation-btd.md` | BTD 与项目层倒 U | DID |
| `2025-rfs-political-sentiment-patents.md` | 选举与发明人专利 | DID |
| `2025-rfs-social-connectedness-lending.md` | 社交连接与放贷 | 相关 |
| `2025-rfs-bank-bail-ins.md` | Bail-in 最优负债 | 理论 |

对你最有用、值得下一步 `identification-audit` 的：PE 污染的 BLM / DrillCo，以及专利选举的企业×技术 DID。两篇创新并排读。BTD 主 hazard 系数前 14 页没有。社交连接不要写成因果。

## 已有卡片（RFS 38(10), 2025）

同样只根据上传 PDF 前约 14 页。页码从 2845 连到 3148。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-quant-demand-elasticity.md` | 量化需求弹性 | 测度 |
| `2025-rfs-bond-etf-baskets.md` | 债券 ETF 主动篮子 | IV |
| `2025-rfs-persistent-flows-factors.md` | 持续资金流预报因子 | 预测 |
| `2025-rfs-etf-tax-efficiency.md` | ETF 税递延 | DID |
| `2025-rfs-dex-lp-commons.md` | DEX 的 LP 公地 | 理论 |
| `2025-rfs-dominate-historical-average.md` | 打赢历史均值 | 预报 |
| `2025-rfs-weak-id-long-memory.md` | 长记忆弱识别 | 计量 |

对你最有用、值得下一步 `identification-audit` 的：债券 ETF 的月末再平衡 IV，以及 2012 年资本利得税的高净值 DID。两张 ETF 并排读。篮子流动性和 ETF 税的点估计前 14 页没有。

## 已有卡片（RFS 38(11), 2025）

同样只根据上传 PDF 前约 14 页。页码从 3149 连到 3459。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-fsb-advertising-race.md` | 自由民银行广告 | DID |
| `2025-rfs-gender-investment-gap.md` | 性别投资差距 | 结构 |
| `2025-rfs-advice-repeat-demand.md` | 建议赚钱再来 | 风险 |
| `2025-rfs-mortgage-broker-selection.md` | 按揭经纪选择 | 结构 |
| `2025-rfs-pretrial-detention-insolvency.md` | 审前羁押与破产 | IV |
| `2025-rfs-fsb-depositor-flight.md` | 自由民银行挤兑 | 历史 |
| `2025-rfs-small-banks-small-firms.md` | 小银行与小企业 | IV |

对你最有用、值得下一步 `identification-audit` 的：马里兰专员宽松度 IV，以及小企业 Bartik。两张自由民银行并排读。性别差距的分年龄百分点前 14 页没有。

## 已有卡片（RFS 38(12), 2025）

同样只根据上传 PDF 前约 14 页。页码从 3461 起。**3542–3579、3673–3728 仍缺**（未上传）。这 6 篇收到 3790。

| 文件 | 短题 | 方法 |
|---|---|---|
| `2025-rfs-passive-mega-firms.md` | 被动投资与巨头 | 理论 |
| `2025-rfs-pi-capm.md` | 概率加权 CAPM | 理论 |
| `2025-rfs-sentiment-factor-betas.md` | 情绪与因子 beta | 预测 |
| `2025-rfs-anticipatory-mhf-trading.md` | 抢跑困境巨头基金 | 安慰剂 |
| `2025-rfs-short-leg-lottery-text.md` | 短腿文本与彩票 | 文本 |
| `2025-rfs-man-vs-ml-lookahead.md` | 机器学习前瞻偏差 | 复现 |

对你最有用的是复现那张：BHL 的 1.54% 靠前瞻盈余。短腿文本和 Π-CAPM 并排读。被动巨头的点估计、期权 U 形系数前 14 页没有。复现卡不当发现。

## 不要放

- PDF（放到本机 `notes/pdfs/`，默认不提交）
- 完整读书笔记（长文去 `notes/`，这里只留卡片）
- 虚构文献条目
