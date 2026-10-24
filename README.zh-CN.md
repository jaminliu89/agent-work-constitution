# Agent Work Constitution｜AI 工作宪章

**少假设、少复杂度、多真实执行、多验证、多经验复利。**

[English](README.md) · [核心指令](rules/CONSTITUTION.zh-CN.md) · [工程执行契约](rules/ENGINEERING.zh-CN.md)

这是一套**跨 ChatGPT、Claude Code、Codex、Cursor 等工具的通用 AI Agent 工作指令**。在 Karpathy 风格的四项编程纪律基础上，加入我们长期实践所需的历史资产召回、任务授权边界、真实验收、主线管理与经验复用。

> 独立社区作品，不代表 Andrej Karpathy、Anthropic、OpenAI 或任何工具提供商的官方立场或认可。本文均为独立撰写，并对概念来源作出署名。

## 为什么做这个项目？

只强调代码质量，不足以防止 AI 误解用户目标、臆测历史项目状态、无限加功能、支线跑偏，或者将 Mock、截图和 CI 通过当成真实可用。我们需要的是**有判断、能执行、可验收、会学习**的 Agent，而不是越来越长的口号。

## 2 分钟开始使用

**个人 AI 助手：** 将 [精简版指令](profiles/COMPACT.zh-CN.md) 放进自定义指令；需要完整原则时查看 [核心指令](rules/CONSTITUTION.zh-CN.md)。

**已有代码项目：** 保留原有 `AGENTS.md` 或 `CLAUDE.md`，通过引用或选择性合并的方式接入，不要覆盖已有规则。复杂开发任务使用 [工程执行契约](rules/ENGINEERING.zh-CN.md)。

**新项目：** 参考 [AGENTS 模板](templates/AGENTS.md)、[MEMORY 模板](templates/MEMORY.md)、[任务契约模板](templates/TASK_CONTRACT.md)。这不是要求所有小任务都生成一套文件。

## 文件索引

| 文件 | 用途 |
| --- | --- |
| [`rules/CONSTITUTION.zh-CN.md`](rules/CONSTITUTION.zh-CN.md) | 完整个人/通用 Agent 指令 |
| [`rules/ENGINEERING.zh-CN.md`](rules/ENGINEERING.zh-CN.md) | 工程状态机、范围控制、真实验收 |
| [`profiles/COMPACT.zh-CN.md`](profiles/COMPACT.zh-CN.md) | 可直接复制的个人精简版 |
| [`templates/AGENTS.md`](templates/AGENTS.md) | 项目执行规则起始模板 |
| [`templates/MEMORY.md`](templates/MEMORY.md) | 长期项目经验起始模板 |
| [`templates/TASK_CONTRACT.md`](templates/TASK_CONTRACT.md) | 本次任务的范围与验收契约 |
| [`AGENTS.md`](AGENTS.md) | 本仓库贡献时使用的规则 |
| [`CLAUDE.md`](CLAUDE.md) | 本仓库 Claude Code 入口 |

## 核心升级

1. **编码前先思考**：暴露关键假设和取舍。
2. **简单优先**：拒绝不必要的功能和抽象。
3. **精准修改**：不顺手重构无关代码。
4. **结果可验证**：先定成功标准，再循环验证。
5. **约束与记忆先行**：查真实项目状态，回收相关历史决策。
6. **决策授权**：提议不等于批准，研究不等于集成。
7. **证据分级**：已实现、已测试、已验证、已验收不混用。
8. **主线恢复**：支线结束要返回约定的目标。
9. **学习复利**：抽象可迁移的教训，不盲目安装和整合。

## 关键边界

- `AGENTS.md`、`MEMORY.md` 的初始化闸门只适用于**实际可访问的项目工作空间**，普通聊天无需强制创建文件。
- 模板不存在时不得伪称已复制；能安全推断的尽量自行处理，确实阻碍任务的重要信息才集中询问。
- 重复三次的任务应**评估**自动化价值，不意味着必须立刻开发自动化系统。
- 真实仓库状态与明确决定优先于 AI 的印象；证据缺失就明确声明。
- 不可逆操作、外部发布、资金与权限变更，应遵守必要的授权边界。

## 如何知道它真的有用？

通过真实任务观察：是否偏离已确认需求、核心场景能否端到端完成、是否引入回归问题、是否无关修改、有没有虚假完成声明、临时支线后能不能返回主线。可使用 [任务契约模板](templates/TASK_CONTRACT.md) 留下证据。

## 来源与关系说明

四项编程原则受到社区项目 [Karpathy-Inspired Claude Code Guidelines](https://github.com/multica-ai/andrej-karpathy-skills) 启发。该项目以社区视角归纳 Karpathy 对 AI 编码的观察，并不是 Karpathy 本人的官方指令。这里是独立扩展，不是原文复制或官方分支。

欢迎通过 [贡献指南](CONTRIBUTING.md) 交流。采用 [MIT 许可证](LICENSE)。
