# 上游路由

外面的仓库当词典，不当第二套系统。本表告诉你：**遇到什么事先读本仓哪一页，不够再点哪个链接、只偷哪一刀。**

不要 clone 进本仓库。不要把上游 skill 整包拷进 `.cursor/skills/`。

## 本仓入口（先走这里）

| 你在干什么 | 本仓 |
|---|---|
| 读论文做卡 | `literature-card` |
| 审识别 | `identification-audit` + `methods/rd.md` 或 `did.md` 或 `iv.md` |
| 列稳健性 | `robustness-checklist` + 同上方法纸 |
| 假审稿 | `referee-sim`（审的时候不准改用户的代码和正文） |
| 写 Stata 却卡语法 | 打开下面「Stata 词典」，不要新开一套流程 |
| 不知道该不该问用户 | `AGENTS.md` 里「先问再写」 |

同一功能只留一个入口。出现两套说法，以本仓方法纸 + skill 为准，把冲突记在 memo 里问用户。

## 按需打开（高质量，只偷一刀）

| 需要什么 | 打开 | 只偷 | 不要搬 |
|---|---|---|---|
| 检查分层：能跑通 ≠ 识别成立 | [Sant'Anna workflow](https://github.com/pedrohcgs/claude-code-my-workflow) | 五层 credibility；检查要能抓错 | 60 skill、commit 门、Beamer、付费多模型 |
| 错时 DID / 弱 IV / RD 带宽的现代默认 | [EconAgentSkills](https://github.com/JonasWeinert/EconAgentSkills) | 决策树；ASK/DEFAULT；数据键与 merge 行数 | 十个 skill 整锅、R 示例当主流程 |
| Stata 语法、`reghdfe` / `rdrobust` / `csdid` / `esttab` | [stata-skill](https://github.com/dylantmoore/stata-skill) | 当前任务相关的那一份参考 | 37 份参考当常驻规则；C plugin |
| 假审稿要独立 | [MixtapeTools](https://github.com/scunning1975/MixtapeTools) | 换干净上下文审；审的人不改作者代码 | 幻灯修辞、GTD 全家桶 |
| 论文流水线怎么分段 | [clo-author](https://github.com/hugosantanna/clo-author) | 先 design memo 再回归 | 18 agent、80 分门、仪表盘 |
| 中文 + Stata 闸门对照 | [econ-paper-studio](https://github.com/gaaiyun/econ-paper-studio) | claim 必须指回表（已写入规则） | 它的 CLI |
| 文献卡片字段对照 | [econ-research-os](https://github.com/RyanPiao/econ-research-os) | 卡片六块（已写入模板） | 27 skill、必装 MCP |
| 圈里还有什么 | [awesome-econ-ai-stuff](https://github.com/meleantonio/awesome-econ-ai-stuff) | 当收藏夹 | 示例 skill 全装上 |

## 质量不够或与本仓任务错位（默认不打开）

- 0 星 fork、愿景仓（例如只写「将来要从想法生成论文」）
- SuperJay 一类指南：当文章读，不并进 skill
- 教学幻灯、Quarto 写书、Stata C 插件
- 任何必须付费密钥 / 登录 MCP 才能跑的步骤

## 以后才考虑加进本仓的（现在不加 skill）

| 痛点重复出现 | 再加 | 来源 |
|---|---|---|
| 开始写新 do / 洗数据 | 薄的 `stata-do`、`data-hygiene` | Weinert + Moore |
| 正文数字对不上表 | 薄的 `verify-claims` | Sant'Anna / studio |
| 要验证估计量有没有写错 | `validate-estimator`（种已知效应） | dphdame starter |

没碰到痛点，不加。
