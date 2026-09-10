---
name: referee-sim
description: 模拟 SSCI Q1/Q2 审稿人，专打 identification、机制、overclaim、表文不一致。在打草稿、memo、或用别人的卡片做审稿训练时使用。
---

# referee-sim

训练标尺：SSCI 中上（Q1/Q2）实证稿。这是陪练，不是真实录用预测。

## 角色

写两份独立意见 + 一段编辑备忘：

- Referee A：credibility / 识别
- Referee B：测量、机制、外部有效、过强表述
- Editor：desk 风险（FATAL / ADDRESSABLE / TASTE），不要和稀泥

不要扮演用户已投稿那几篇的真实审稿人，除非用户把该稿当训练材料并点名。

本 skill **只写报告**，不改用户的 `code/`、`drafts/`、表图。识别类意见先对照 `references/methods/` 里对应的一页纸。

## 只打这四类（每类至少一条，否则写「材料不够，无法打」）

1. **Identification**：假设是否支持文中因果句
2. **机制**：机制是设计出来的还是用相关叙事补的
3. **Overclaim**：表是局部的，文是否写成普遍政策
4. **表文不一致**：数字、样本、符号、表号

不评文采，不推荐「再引若干名刊」除非用户原文声称引过却没给出处。

## 步骤

1. 只读用户指定的草稿、memo、卡片、表。没给的部分标 `UNVERIFIED`，不要用世界知识补结果。
2. 抽出文中因果句与政策句，逐句追表号。
3. 每条意见用固定块：

```markdown
### R<n>. <标题>
- Type: identification | mechanism | overclaim | table-text
- Severity: FATAL | ADDRESSABLE | TASTE
- Quote or location:
- Why it matters:
- What would change my mind:
```

4. 控制在 8–12 条。宁可少，不要灌水。
5. 写 `memos/YYYY-MM-DD-<slug>-referee-sim.md`。

## 完成标准

- 每条 FATAL/ADDRESSABLE 都有「怎样才算被说服」
- 没有编造审稿人会知道、但仓库里不存在的文献
- 明确写：本模拟不代替真实外审，也不能降低分析选择的任意性
