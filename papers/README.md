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

## 不要放

- PDF（放到本机 `notes/pdfs/`，默认不提交）
- 完整读书笔记（长文去 `notes/`，这里只留卡片）
- 虚构文献条目
