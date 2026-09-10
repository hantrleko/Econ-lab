---
name: identification-audit
description: 审计一篇设计、design memo 或代码的识别策略：estimand、假设、最危险威胁、必须先做的诊断。在用户要审识别、审 do/py、或把别人的设计当陪练时使用。
---

# identification-audit

陪练目标：用户以后能自己指出「这篇 / 我的设计会死在哪一点」。

## 输入（缺了就问，不要脑补）

- 设计说明：`memos/`、`papers/` 卡片、或用户粘贴的段落
- 若有代码：`code/stata/` 或 `code/python/` 里被点名的脚本
- 方法家族：RD / DID / IV / 事件研究 / 调节，以用户或卡片为准

方法确定后先读一页纸，再审计：`references/methods/rd.md`、`did.md` 或 `iv.md`。事件研究走 `did.md`。不要同时打开多份上游 README。

## 步骤

1. 用一句话重述 estimand（谁、相对谁、什么处理、什么结果）。重述不了就判「设计未写清」，不要替用户选定 estimand。观察单元、处理定义、聚类未定时，按 `AGENTS.md`「先问再写」停下来问。
2. 列出识别假设（每条一句）。标哪些是源里写了的，哪些是你补的推断（推断必须标 `UNVERIFIED`）。
3. 点名最危险的 1–3 个威胁。每个威胁写：为何在这个样本里危险、它会把估计偏去哪。
4. 对照 `.cursor/rules/10-identification.mdc` 和对应方法纸的「必须先做」。缺的诊断列为 **必须先做**，不要用「也可以做」稀释。
5. 若有代码：检查处理变量构造、样本限制、固定效应、聚类是否与 memo 一致。只报告你看见的不一致，不编造没打开的脚本内容。
6. 五层 credibility：最后用四行写明本次审计覆盖了哪一层、没覆盖哪一层（通常到不了「识别成立」）。

## 输出格式

```markdown
# Identification audit: <slug>

## Estimand
## Assumptions (stated vs inferred)
## Most dangerous threats
1. ...
## Must-run diagnostics
- [ ] ...
## Code vs memo mismatches (if any)
## Credibility layers covered
## UNVERIFIED
```

写到 `memos/YYYY-MM-DD-<slug>-id-audit.md`，除非用户只要对话里看。

## 禁止

- 把审计写成「建议再做机器学习 / 再引三篇经典」
- 为了显得全面列出 20 条同等重要的稳健性（那是下一个 skill）
- 宣布识别「没问题」
