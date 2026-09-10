---
title: "Competition and Innovation Revisited: A Project-Level View"
authors: "Jon A. Garfinkel; Mosab Hammoudeh"
year: "2025"
venue: "Review of Financial Studies 38(9)"
doi: "10.1093/rfs/hhae078"
method: "DID"
slug: "2025-rfs-competition-innovation-btd"
source_file: "uploads/hhae078_6656.pdf"
status: "carded-from-first14pp"
---

# Garfinkel and Hammoudeh (2025) — 治疗领域被 BTD 打乱后，项目层创新是倒 U，企业层专利几乎不动

开放获取（非商用）。旧题 *Competition Threats and Rival Innovation Responses*。Cortellis；Hermosilla 政策暴露；Hoberg scope。DOI 在 PDF 第 1 页。和同辑专利情绪那张并排：一个是发明人党派，一个是项目层竞争。

## 问题

- 研究问题（一句）：竞争和创新到底是倒 U 还是符号乱飘——是理论错了，还是企业层加总把项目反应洗掉了？
- Estimand：2012-07-09 起 FDA Breakthrough Therapy Designation 打乱某个治疗领域后，该领域对手 II 期项目进入 III 期的风险，按事前竞争强弱、以及项目是否共用 BTD 药物技术（离新前沿远近）切开。

## 识别

- 策略：作者把 BTD 写成「工具化」随机打乱水平，实际是治疗领域事件 / 风险模型，不是经典 2SLS。对照 `did.md`：BTD 日错时进入不同适应症；前 14 页强调事前平行，未见现代错时估计量。对照项目是未受该次 BTD 冲击的 II 期。
- 侧写加总：制造业里用 Autor–Dorn–Hanson 中国进口 IV + Hoberg–Phillips scope。低 scope 企业倒 U 清楚，高 scope 糊掉（表 2）。药企也一样：BTD 公司正 CAR、对手负 CAR，企业层专利/研发几乎无反应。
- 距离前沿：对手项目若共用 BTD 药物的至少一种技术，作者当成更近 Hashmi (2013) 前沿，续做 hazard 全面更高。
- 最危险威胁：BTD 授予不是对治疗领域的随机分配，FDA 看着早期疗效；适应症定义（ICD-10）可被作者选择。预期（专利或试验完成已公告）会让「打乱」不意外。

## 数据

- 观察单元 / 时间：药物项目；主结果是 II 期→III 期 hazard。2012-07-09 通路开通之后的 BTD。
- 来源：Cortellis；Hermosilla 政策暴露；Hoberg scope；部分样本有销售额做 HHI。
- 处理与结果：同一治疗领域出现 BTD。竞争用该领域项目数（主）、企业数、大企业加权、子样本 HHI。
- 样本限制：去掉癌症、去掉可能「买来杀掉」的项目（Cunningham et al. 2021）做过；尚未上市药的领域当颈颈竞争。

## 主结果

- 企业层：BTD 公告正 CAR、对手负 CAR；企业层专利和研发相对其他药企几乎无差别——作者读成加总/重分。
- 项目层：事前竞争弱则 II→III hazard 升，强则降，倒 U（Aghion et al. 2005）。低暴露（该领域只占组合一小块）更弱。共用 BTD 技术的项目续做全面更高，且在高暴露、低竞争市场上更明显。
- 事前平行；低 BTD 政策暴露市场结果更强或相当。癌症样本、生物 vs 大药、三种竞争度量、HHI（与项目数负相关）作者称方向不变。
- 表 2（制造业 IV，不是主设计）：全样本进口一次项为正、平方为负；低 scope 更清楚，高 scope 不显著。点估计单位含糊，R² 印成接近零。
- 主 hazard 的具体系数：前 14 页只有定性，表号在后文，**UNVERIFIED**。

## 可攻击点

- 「instrument stochastic unleveling」容易被引成 2SLS；前 14 页没有第一阶段。
- 错时 BTD，对照是其他项目，不是从未处理领域；hazard 的处理时点定义要审。
- 倒 U 靠竞争度量切段，切法一变形状会变；HHI 只在有销售的子样本。
- 企业层「无创新反应」可能是窗太短或专利不是药企的对的结果。
- 表 2 制造业回归 R² 接近 0，只能当「加总会脏」的示意，不当发现。

## 可复用设计

- 先报企业层 CAR 有、专利/研发无，再下到项目层，用来讲加总，不要反过来。
- 创新决策对准 II→III，不要用公司当年专利总数。
- 用「是否共用被冲击产品的技术」当距离前沿，比用价格推 TFP 干净（药没有那个价格问题）。
- 预期：事前平行 + 低政策暴露子样本，两刀都要。
- 不要把中国进口 IV 写成这篇的主识别。

## 证据指针

- 摘要、BTD 打乱、倒 U、技术距离改形状：PDF 第 1 页。
- 2012-07-09 BTD、Aghion 机制：PDF 第 3 页。
- 企业层 CAR vs 无专利/研发、II→III hazard：PDF 第 4–5 页。
- 表 2 中国进口 × scope：PDF 第 10 页。
- 主 hazard 点估计：前 14 页无，UNVERIFIED。

## 训练价值

对照 `did.md`。练的是「加总把倒 U 洗掉」怎么用项目层写出来。主系数要翻后文表。下一步可对这张跑 `identification-audit`，重点审 BTD 是不是外生打乱。
