# 👋 freshtemp-labs

> AI Agent 协作开发的开源项目集合

我们探索一种新的开发模式：**人类定义需求，AI Agent 协作实现**。所有项目均由 [Hermes Agent](https://github.com/nousresearch/hermes-agent)（规划/审查）+ 土鳖/DeepSeek V4（编码/测试）双 Agent 协作完成。

## 🚀 项目

| 项目 | 描述 | 亮点 |
|------|------|------|
| [**hermes-skills-bridge**](https://github.com/freshtemp-labs/hermes-skills-bridge) | 一键导入 skills.sh 生态 50+ AI Agent Skills | 50/50 导入成功，13 个来源仓库 |
| [**okr-alignment-system**](https://github.com/freshtemp-labs/okr-alignment-system) | OKR 对齐管理系统 | Swift/SwiftUI，树状可视化 + 级联计算 + iCloud 同步 |
| [**ai-compute-map**](https://github.com/freshtemp-labs/ai-compute-map) | 全球 AI 算力供应链地图 | React/TypeScript，三层数据可视化，支持中/英/日/韩 |
| [**ba2plus-calculator**](https://github.com/freshtemp-labs/ba2plus-calculator) | BA II Plus 金融计算器 | CFA 24/24 测试通过，Tauri 跨平台 |

## 🤖 开发模式

```
人类（老板）
  │
  ├── 定义需求（PRD）
  ├── 审查代码（Code Review）
  └── 决策方向（Strategy）
        │
        ▼
  Hermes Agent（富米）── 规划 + 配置 + 审查 + 汇报
        │
        ├── Kanban 任务分发
        └── 土鳖（DeepSeek V4）── 编码 + 测试 + Git 操作
              │
              ├── 并行子代理（delegate_task）
              └── 舰队作业（多 repo 并行审查）
```

## 📊 数据

- **总 Commits**: 100+（AI 生成 + 人工审查）
- **测试覆盖**: OKR 17K 行测试 / AI 算力地图 129 个测试文件 / CFA 24/24
- **Bug 修复**: 10+ 个由 AI Agent 自动发现并修复的 bug
- **Skills 导入**: 50 个来自 skills.sh 生态的验证 skill

## 🤝 参与

每个项目都有 [`good first issue`](https://github.com/freshtemp-labs/okr-alignment-system/labels/good%20first%20issue) 标签，适合新手贡献者。

- 想改进 OKR 系统？→ [贡献指南](https://github.com/freshtemp-labs/okr-alignment-system/blob/main/CONTRIBUTING.md)
- 想完善算力地图？→ [贡献指南](https://github.com/freshtemp-labs/ai-compute-map/blob/main/CONTRIBUTING.md)
- 想添加更多 Skills？→ [top50.json](https://github.com/freshtemp-labs/hermes-skills-bridge/blob/main/top50.json)

## 💡 为什么关注我们？

1. **AI 辅助开发的最佳实践** — 真实项目，不是 demo
2. **完整的工程文档** — PRD + 代码架构 + 测试 + 贡献指南
3. **持续迭代** — 每天都有新的 AI Agent 发现和修复
4. **开源免费** — GPL-3.0，无任何隐藏费用
