# code/

可复现分析代码。Stata 与 Python 分开，一张表对应得到出它的脚本。

## 目录

| 路径 | 用途 |
|---|---|
| `code/stata/` | `.do`：清洗、估计、出表 |
| `code/python/` | `.py`：清洗、图、辅助估计 |

## 约定（详见 `.cursor/rules/20-code-style.mdc`）

- 路径相对仓库根，或在脚本头写清工作目录
- 设 seed；Stata 写 `version` 并开 log
- 只读 `data/raw/`，写入 `data/clean/`、`tables/`、`figures/`
- 不要手改 Excel 充当终表

## 建议脚本顺序

```
00_setup     路径、seed、包
01_clean     raw → clean
02_desc      描述统计
03_main      主估计
04_robust    稳健性
05_figures   图
```

新项目先复制这个顺序，再改内容。空目录用 `.gitkeep` 占位，有脚本后可删。
