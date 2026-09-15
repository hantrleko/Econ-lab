---
title: "JAQ of all trades: Job mismatch, firm productivity and managerial quality"
authors: "Luca Coraggio; Marco Pagano; Annalisa Scognamiglio; Joacim Tåg"
year: "2025"
venue: "Journal of Financial Economics 164"
doi: "10.1016/j.jfineco.2024.103992"
method: "other"
slug: "2025-jfe-jaq-job-mismatch"
source_file: "uploads/1-s2.0-S0304405X24002150-main_37e5.pdf"
status: "carded-from-first14pp"
---

# Coraggio, Pagano, Scognamiglio, and Tåg (2025) — 用最能产的厂当模板，机器学习打出岗位匹配分，和工资、生产率一起走

文章编号 103992。Papanikolaou 编辑。开放获取 CC BY-NC-ND。Pagano：意大利 MUR PRIN 2017（2017RJJNM5）、EIEF。Scognamiglio：UniCredit Foundation Modigliani。Tåg：Marianne and Marcus Wallenberg、Torsten Söderberg、Jan Wallander / Tom Hedelius。作者挂 Naples / CSEF、EIEF、Hanken、IFN。复制包 JAQ-Replication。

## 问题

- 研究问题（一句）：人有没有被放在最合适的岗位上？这种匹配和工资、企业生产率、管理层质量是不是一起动？
- Estimand：不是因果主设计。先构造员工层 eJAQ 和企业层 JAQ，再看它们与收入、离职、增加值/人均销售、竞争、是否家族企业、人力资本的相关；以及管理层匹配改善之后，普通员工匹配是否跟着改善。

## 识别

- 策略：测度。四步。用机器学习，在**最能产的企业**里估「工人特征 → 岗位」的分配规则（对标 Bloom–Van Reenen 用咨询公司最佳实践）。再预测每个工人对每个岗位的适合度；实际岗位是否等于最适合岗位（eJAQ）；企业内平均得 JAQ。
- 循环担心：规则在高产企业上训练，再拿 JAQ 去跟生产率相关。作者称相关回归丢掉训练集。安慰剂：用噪声假生产率训练，关系应消失。随机企业子集重训。再用 AKM 工资残差（匹配剩余）另建训练集。
- 管理层：分别算普通员工 JAQ 和管理者 JAQ。看管理者招聘/解雇是否持久改变管理质量，以及随后普通员工匹配。 subsample：在任管理者死亡。作者称死亡样本估计很不精确。
- 最危险威胁：JAQ 本质上是「像高产企业那样分岗」；和生产率相关可能仍是定义。死亡样本太小，不能当因果。

## 数据

- 行政雇主–雇员数据，含职业。具体国家/年范围前 14 页没有写死，UNVERIFIED（作者称任何带职业的雇主–雇员数据都能做）。
- 特征：教育、年龄、性别、经验。经验和教育最重要，但不同职业权重不同。

## 主结果

- eJAQ 的变异多半来自留在本企业的人，不是跳槽；企业 JAQ 上升通常是老人经验积累、岗位没换。
- 职业生涯里 eJAQ 上升，头几年最大。匹配最好的人，比同样特征或同样岗位的错配者赚得显著更多，也更少换雇主。
- 企业 JAQ 与市场竞争、非家族、人力资本、对数增加值和人均销售正相关；控制行业、资本劳动、所有权、以及用来预测 JAQ 的工人特征之后仍在。把 JAQ 改成「只在现有员工和现有岗位里重排」的版本，相关还在。
- 普通员工 JAQ 与管理者 JAQ、管理团队平均经验正相关，即使用企业内变异。管理质量因招人/开人而升时，普通员工匹配改善，且常发生在普通员工匹配刚变差之后；管理变更差则普通员工匹配被持久打乱。更好的管理者主要靠留住老人、让他们积累经验；更差的管理者靠乱调岗把老人匹配打坏。

## 可攻击点

- 点估计、样本国和年，前 14 页没有，**UNVERIFIED**。
- 「最能产企业的分岗 = 好匹配」是基准选择，不是理论最优。
- 相关不是「更好匹配导致更高产」。死亡冲击作者自己说不精确。
- 机器学习分配规则不可解释时，JAQ 难当可操作的管理建议。

## 可复用设计

- 匹配质量不要靠再做一轮 Bloom 问卷，用带职业的行政数据就能做。
- 先在「标杆企业」上学分配规则，验证时丢掉训练集，再用噪声/随机/AKM 残差重训。
- 企业层 JAQ 拆成老人积累 vs 招人开人，机制才分得开。
- 管理者死亡当冲击可以试，但 n 不够就别写成因果。

## 证据指针

- 摘要、JAQ、管理、可复用到任何带职业的数据：PDF 第 1 页。
- 四步、循环担心与安慰剂、死亡样本不精确：PDF 第 2 页。
- 资助：PDF 第 1 页脚注。
- 系数：前 14 页没有，UNVERIFIED。

## 训练价值

测度卡。练的是「指标会不会循环定义」，不是准实验。死亡冲击太弱，不优先审计。
