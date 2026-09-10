# Econ-lab

Personal applied-economics research operating system.

Tracks: crowdfunding RD, Asia-Pacific chip consumption and electromechanical exports, LGFV / implicit guarantees.

这是长期研究底座，不是单篇论文草稿机。已完成并已投稿的三条线只说明方法背景，不在本仓库里维护稿件本身。日常用途是：读论文、练识别、写可复现代码、用 SSCI 中上的审稿标准打自己的新想法。

常用工具：Stata、Python、LaTeX。写作中英都可以。

## 这个操作系统怎么用

Agent 先读根目录 `AGENTS.md`，再按任务加载 `.cursor/skills/` 里的一个 skill。短禁令在 `.cursor/rules/`，长步骤不进常驻规则。

默认闭环：

1. 读一篇 → `literature-card` → `papers/` 一张卡
2. 要做题 → `templates/design-memo.md` → `memos/` → `identification-audit`
3. 动数据 → 只读 `data/raw/`，代码写在 `code/`
4. 出表图 → `tables/`、`figures/`，正文数字必须指回来
5. 投稿前训练 → `robustness-checklist` 然后 `referee-sim`

## 目录

| 路径 | 含义 |
|---|---|
| `papers/` | 每篇论文 / 每个新题目一张结构化卡片 |
| `notes/` | 方法笔记、脏想法；PDF 建议只放本机 |
| `data/raw/` | 原始数据，只读，默认不提交 |
| `data/clean/` | 代码生成的分析数据，默认不提交 |
| `code/stata/` | `.do` |
| `code/python/` | `.py` |
| `tables/` | 脚本写出的表 |
| `figures/` | 脚本写出的图 |
| `drafts/` | 进行中的 tex / md |
| `memos/` | 识别与设计备忘（决策以这里为准） |
| `templates/` | 空模板，复制后用 |

每个目录有自己的 `README.md`，打开即知该放什么。

## 第一次打开后做什么

1. 读 `AGENTS.md` 和四条 `.cursor/rules/*.mdc`
2. 扫一遍 `templates/`，知道卡片和 design memo 长什么样
3. **本周只做一件能力训练**：把正在读的一篇论文 PDF 放到本机 `notes/pdfs/`（不要 push），对 Agent 说「用 literature-card 做卡片」
4. 卡片做完后，用 `identification-audit` 把这篇的识别当成「若是我的设计」来打
5. 有新题目时，先写 `memos/`，再写代码

不要一上来生成完整论文，也不要为已投稿的三篇重建文件夹。

## Skills

| Skill | 何时叫 |
|---|---|
| `literature-card` | 读 PDF / 笔记 → `papers/` 卡片 |
| `identification-audit` | 审计设计、memo 或代码的识别 |
| `robustness-checklist` | 按方法列出必须做的稳健性 |
| `referee-sim` | 模拟 SSCI Q1/Q2 审稿人 |

在 Cursor 里用技能名或自然语言触发，例如：「用 identification-audit 看这份 memo」。

## 数据与密钥

- 原始数据、密钥、`.dta`、大 CSV 已被 `.gitignore` 挡住
- 需要外部核引工具时只用可选网页核验，不把付费 API 当依赖
- 复现说明里不要编造数据下载链接

## 上游吸收（未整仓复制）

结构与闸门意识来自 econ-paper-studio、econ-research-os、clo-author、Sant'Anna 的 workflow 笔记，以及 awesome-econ-ai-stuff 的 skill 分层。本仓只保留短规则 + 四个 skill + 模板。
