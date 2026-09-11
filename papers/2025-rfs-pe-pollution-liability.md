---
title: "Does Private Equity Ownership Make Firms Cleaner? The Role of Environmental Liability Risks"
authors: "Aymeric Bellon"
year: "2025"
venue: "Review of Financial Studies 38(9)"
doi: "10.1093/rfs/hhaf035"
method: "DID"
slug: "2025-rfs-pe-pollution-liability"
source_file: "uploads/hhaf035_4721.pdf"
status: "carded-from-first14pp"
---

# Bellon (2025) — PE 接盘之后，责任重的州少排污，联邦地管不住就多排

Kleinman / Rodney White / Wharton Social Impact 资助；Enverus PE 数据致谢。DOI 在 PDF 第 1 页。和 JF Johnston-Ross–Ma–Puri 接盘破产银行是同一「PE 治理」家族，结果换成污染。

## 问题

- 研究问题（一句）：private-to-private 的 PE 控股，会不会让油气井更脏，还是只在环境责任风险高的时候更干净？
- Estimand：PE 买断之后，高责任州（或 BLM 监管被挡住的联邦地/保留地）上新压裂项目的有毒化学品使用，相对非 PE、相对低责任地点。

## 识别

- 策略：两层。第一层是买断后的项目层比较，企业–年 FE + 超本地趋势，再按 Lawsuit Climate Survey 的州诉讼气候（样本中位数上/下）看异质；备选用 Konisky (2007) 执法风险。第二层是 2016–2018 年 BLM 无法监管联邦土地和印第安保留地压裂：责任突然变轻。对照 `did.md`：买断是错时进入，前 14 页未见 CS / Sun–Abraham / 从未处理对照的写法。
- 治理 vs 出钱：油气特有的 DrillCo（PE 出钱、不控管理）在高责任州看不到减污——作者读成要控股才有治理。
- 最危险威胁：PE 选本来就更干净或更会打官司的标的；BLM 冲击叠 2016 政治周期；错时 TWFE 加权。

## 数据

- 观察单元 / 时间：井/项目；2012–2021 美国 166,279 口压裂井。
- 来源：压裂化学品行政数据 + 井特征；Enverus PE 所有权。
- 处理与结果：PE 买断（private-to-private）；结果是新项目有毒化学品。有毒但合法，抬的是 CERCLA / 侵权 / 未来监管风险，不是当场违法。
- 样本限制：上游油气；作者写明和 Shive–Forster (2020) 的上市/大厂空气污染样本不是同一行业。

## 主结果

- 买断后污染下降，和「PE 风险转移、故意排更脏」相反。
- 高责任州：PE 后新项目污染相对基线少 **68.79%**。企业–年 FE、项目产油/技术、超本地趋势之后仍在。
- DrillCo：同样规格下，高责任州无此减污。
- BLM 2016–2018：PE 项目污染相对升 **97.5%**。作者称联邦地/保留地边界是十九、二十世纪定的，和页岩准随机重叠（压裂二十一世纪才普及）；2015 年前边界两侧大多平衡。
- 768 个规格；作者称产量变化不是渠道。两种 EPA 有毒分类都做过。

## 可攻击点

- 68.79%、97.5% 是相对基线的比例，基线若接近零会显得很大；表号在后文。
- 买断错时，前 14 页只报传统规格和「偏离事前趋势」的稳健，没写现代估计量。
- 州诉讼气候是企业主观感受，可能和 PE 选址、本地政治一起动。
- BLM 窗口正好跨特朗普上台，监管放松不只有联邦地这一条。
- DrillCo 不是随机对照：愿签 DrillCo 的公司和愿卖控股权的公司本来就不同。
- 外部有效只在上游压裂；作者自己说别的行业责任结构不同。

## 可复用设计

- 责任风险当强度，不要只报「PE 之后污染升/降」一条平均。
- 同行业里找「出钱但不控管理」的合同当安慰剂（这里是 DrillCo）。
- 历史边界 × 后来才出现的技术，用来讲准随机重叠。
- 企业–年 FE 吃掉「买哪家、那年改什么技术」；结果必须是项目层。
- 和 JF 接盘银行并排：都是 PE 运营工程，不要合成「PE 一定利社会」。

## 证据指针

- 摘要、高责任减污 / 低责任加污、治理渠道：PDF 第 1 页。
- 166,279 口井、企业–年 FE、超本地趋势：PDF 第 3 页。
- −68.79%、DrillCo 无效应：PDF 第 4 页。
- BLM +97.5%、768 规格：PDF 第 5 页。
- 资助与 Enverus：PDF 第 1 页脚注。

## 训练价值

对照 `did.md`。优先审 BLM 边界和 DrillCo 是不是真对照。下一步可对这张跑 `identification-audit`。
