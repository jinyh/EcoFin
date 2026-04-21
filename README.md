# EcoFin：金融经济百科（中美视角）

> A China-US comparative finance and economics knowledge base for Obsidian.

EcoFin 是一个面向投资者、政策研究者与金融从业者的金融经济知识库。它把经济学、金融学、政治学、法学、会计学与经济史放在同一套框架里，用中美对比视角组织理论、制度和实践。

## Why EcoFin

- **六学科闭环**：经济、金融、政治、法律、会计、历史相互补足，不再按单一学科割裂理解问题。
- **中美对比视角**：同一知识点同时讨论中国与美国的制度环境、市场结构和实践差异。
- **五段式结构**：理论定义 → 数学表述 → 中美对比 → 直觉理解 → 实践指南。
- **Obsidian 兼容**：正文保持 Obsidian 双链友好，可作为持续维护的知识库使用。

## Who It's For

- **投资者**：想把宏观、金融产品、会计分析和制度风险放在一张图里理解。
- **政策研究者**：想从制度、监管、法律和历史脉络看中美差异。
- **金融从业者**：需要一个兼顾理论、实务和跨学科连接的工作型知识底座。

## Quick Start

### On GitHub

1. 从 [知识地图](./book/00-index.md) 开始，先看全书结构。
2. 再按主题进入各篇章，例如 [经济学](./book/01-economics.md) 或 [投资实践附录](./book/APP-investment.md)。
3. GitHub 适合顺序阅读和文件浏览；Obsidian 双向链接与 Graph View 需要在本地打开 `book/` 才能完整使用。

### In Obsidian

1. 将 `book/` 目录作为 Vault 打开。
2. 从 `00-index.md` 开始浏览。
3. 使用 `[[文件名|显示文本]]` 导航，并用 Graph View 查看知识图谱。

## Reading Map

| 编号 | 学科 | 核心问题 | 状态 |
|------|------|----------|------|
| [00](./book/00-index.md) | 知识地图 | 全书导航入口 | stable |
| [01](./book/01-economics.md) | 经济学 | 资源配置、市场机制、宏观调控 | stable |
| [02](./book/02-finance.md) | 金融学 | 价值配置、风险管理、金融工具 | draft |
| [03](./book/03-politics.md) | 政治学 | 制度框架、政策制定、权力博弈 | draft |
| [04](./book/04-law.md) | 法学 | 规则保障、合约执行、产权界定 | draft |
| [05](./book/05-accounting.md) | 会计学 | 信息质量、准则对比、造假识别 | draft |
| [06](./book/06-history.md) | 经济史 | 历史经验、制度演变、思潮变迁 | draft |
| [07](./book/07-cross-themes.md) | 交叉主题 | 金融与法律、经济与政治的跨学科议题 | draft |

说明：这里的 `status` 是篇章发布状态，不等同于模块扩充进度。

## Reading Paths

- **投资者路径**：金融学 → 会计学 → 经济学 → 法学 → [投资实践附录](./book/APP-investment.md)
- **政策研究者路径**：经济学 → 政治学 → 法学 → 经济史 → 交叉主题
- **金融从业者路径**：金融学 → 会计学 → 法学 → 经济学 → 交叉主题

## Current Status

目前仓库已经建立完整篇章骨架，并按 `70` 个模块跟踪扩充任务，当前完成 `22/70`，即约 `31%`。详细进度见 [模块扩充跟踪](./docs/tracking/模块清单.md)。

已发布为 `stable` 的入口文档：

- [知识地图](./book/00-index.md)
- [经济学](./book/01-economics.md)
- [投资实践附录](./book/APP-investment.md)

## Repository Layout

```text
book/      对外正文与 Obsidian Vault
docs/      规划、跟踪、报告与架构文档
archive/   项目版本归档
sources/   外部来源快照与素材
```

## Obsidian Notes

- 推荐从 `book/` 打开而不是仓库根目录打开。
- 双向链接和 Graph View 只在 Obsidian 内完整可用。
- 如需做进度管理或项目维护，文档入口在 `docs/`，不在正文目录里。

## Reference

- 结构风格参考 [Path2AGI](https://github.com/datawhalechina/Path2AGI)
- 部分金融内容基于 Vincent Logic《金融知识体系终极指南》

---

**版本**：v3.1 | **更新日期**：2026-04-22
