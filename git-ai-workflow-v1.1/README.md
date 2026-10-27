# Git 多 Agent 协作工作流 v1.1

本目录是 v1.1 的完整资料包，共 14 个文件：7 份说明文档和 7 个项目／集合模板。它帮助使用者让多个 AI Agent 在同一项目目录中轮流工作，并用本地 Git 留存版本、接续背景与安全恢复。

## 推荐阅读顺序

| 顺序 | 文件 | 用途 |
|---|---|---|
| 1 | [00-从这里开始.md](00-从这里开始.md) | 选择试点项目并启动首次接入 |
| 2 | [01-使用指南.md](01-使用指南.md) | 理解工作流、职责和状态定义 |
| 3 | [03-实施与检查清单.md](03-实施与检查清单.md) | 供 AI 执行初始化、检查和故障处理 |
| 4 | [02-场景提示词.md](02-场景提示词.md) | 按开工、改稿、验收、交接、恢复等场景使用 |
| 5 | [04-详细文件与使用说明.md](04-详细文件与使用说明.md) | 查文件放置、维护职责和完整操作案例 |
| 6 | [05-版本变更与依据.md](05-版本变更与依据.md) | 查看 v1.1 的演进、公开依据与适用边界 |
| 7 | [06-交付检查记录.md](06-交付检查记录.md) | 查看本资料包已做与未做的验证 |

## 模板说明

- [`templates/project/AGENTS.md`](templates/project/AGENTS.md)：跨 Agent 共用的简短入口。
- [`templates/project/PROJECT_RULES.md`](templates/project/PROJECT_RULES.md)：项目稳定规则与边界。
- [`templates/project/STATE.md`](templates/project/STATE.md)：进度、交接、工具接入与三种状态。
- [`templates/project/.gitignore`](templates/project/.gitignore)：按项目实际情况审查后合并的忽略规则。
- [`templates/project/knowledge/`](templates/project/knowledge/)：关键决策与主题知识记录模板。
- [`templates/collection/PROJECTS.md`](templates/collection/PROJECTS.md)：可选的多项目登记清单。

模板是起点，不要求每个项目都照搬全部文件。先检查项目现有目录和规则，再经使用者确认后增量合并。

## 适用范围与限制

适合需要反复修改、保留历史或由不同 Agent 轮流接续的 HTML 报告和软件项目。每个真实项目使用自己的目录和 Git 仓库；多个 Agent 轮流打开同一真实目录。此资料包目录本身不是实际项目。

本版本已完成文件结构、内容一致性和保留性检查；Aime、TRAE、Antigravity 的具体版本、自动加载、跨软件接力及数据处理设置尚未实测。Git 留存也不等同于质量验收；仍需按任务预览页面或运行测试。

操作步骤见 [快速开始](00-从这里开始.md)。
