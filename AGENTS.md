# Agent Instructions: econ-lab

这是个人的应用经济学研究操作系统。目标是提高**长期研究能力**，不是赶某一篇已投稿件。

已完成并已投稿的方向（众筹 RD、亚太芯片与机电出口 / GVC、城投债与隐担保）只说明研究者的方法口味，**不要主动去改那些稿、补那些表、重写那些引言**，除非用户点名。

## 研究者是谁

- 实证经济 / 金融
- 常用 Stata + Python + LaTeX
- 写作中英都要能用
- 目标期刊：SSCI 中上（Q1/Q2 审稿标准当训练标尺）
- 关心的识别工具：RD、DID、IV、事件研究；也会遇到调节 / GVC 类交互设计

## 这个仓库干什么

长期底座，用来固定四种能力：

1. 把论文读成可偷的设计（`papers/` 卡片）
2. 在跑回归前写清识别（`memos/`）
3. 代码可复现、不碰 raw（`code/` + `data/`）
4. 用审稿标准打自己的过强表述（`referee-sim`）

Agent 是陪练和质检，不是代写整篇论文，也不是文献生成器。

## 先读

1. 本文件
2. `.cursor/rules/` 四条短规则
3. 本次任务对应的 skill（见下表）
4. 相关目录自己的 `README.md`（打开就能看懂该放什么）

不要把上游仓库全文贴进规则，也不要安装需要付费密钥才能用的服务。

## 默认工作流

按阶段走，允许从中途切入，不允许跳过「证据回指」。

```
读 / 选题  →  literature-card
设计       →  design memo + identification-audit
动手       →  数据审计（人工）+ 可复现代码
出表       →  表图命名，claim 指回本地文件
防守       →  robustness-checklist
投稿训练   →  referee-sim（打 identification / 机制 / overclaim / 表文）
```

Sant'Anna 五层不可串台。能跑通 ≠ 估对了 ≠ 测的是那个构念 ≠ 识别成立。Agent 说「检查过了」时，必须写明检查的是哪一层。

## 何时用哪个 skill

| 用户在做什么 | 用这个 skill | 产物 |
|---|---|---|
| 丢来 PDF、笔记、或说「读这篇」 | `literature-card` | `papers/<slug>.md` |
| 审一个设计、memo、或 do/py | `identification-audit` | 威胁等级 + 必须先做的诊断 |
| 方法已定，要列稳健性 | `robustness-checklist` | 按方法分组的必做 / 已做 / 未做 |
| 打一篇草稿、memo、或别人的卡 | `referee-sim` | SSCI Q1/Q2 风格意见，带「怎样才算被说服」 |

一次任务只用相关 skill，不要四个全开。长流程在 skill 里，不在 always-on rules 里。

## 完成定义

一项任务只有同时满足才算完成：

- 没有新造文献、DOI、系数、数据包链接
- 每条事实性 claim 能指回本地表、代码、日志或卡片；否则标 `UNVERIFIED`
- 改了识别或样本，对应 memo / 卡片已更新
- 没有把稳健性写成新贡献
- 没有生成完整论文正文（除非用户明确只要骨架或改已有段落）
- 结束时用简短中文说明：做了什么、哪些仍是 `UNVERIFIED`、用户下一步做什么

## 明确禁止

- 整仓复制上游（econ-paper-studio、econ-research-os、clo-author 等）
- 用「看起来像引用」的文字冒充已读文献
- 覆盖 `data/raw/`
- 为了交差编造主结果
- 把聊天里的口头识别当成终稿而不写 `memos/`

## 可选工具（需要时再装，不是本仓依赖）

- 本机 Stata、Python 3、LaTeX（XeLaTeX / latexmk）
- 引用核验可用 Crossref / OpenAlex 网页；无密钥则人工核 DOI，不要假装核过
- 不要把付费 API、必须登录的 MCP 写成默认步骤
