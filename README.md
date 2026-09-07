# octo-server 需求池

本仓库是 [octo-server](https://github.com/Mininglamp-OSS/octo-server) 开源项目的需求池，用于收集 Bug 反馈、功能需求和改进建议。

## 如何提交

1. **Bug 反馈**：使用 Bug Report 模板提交 Issue
2. **功能需求**：使用 Feature Request 模板提交 Issue
3. 提交后请耐心等待管家 Agent 扫描分类，Label 会在 10 分钟内自动打上

## Label 体系

### 类型（type）
| Label | 说明 |
|-------|------|
| `type:bug` | 缺陷反馈 |
| `type:feature` | 功能需求 |

### 优先级（priority）
| Label | 说明 |
|-------|------|
| `priority:P1` | 紧急 — 影响核心功能，需立即处理 |
| `priority:P2` | 重要 — 影响用户体验，本版本修复 |
| `priority:P3` | 一般 — 改进建议，排期处理 |

### 状态（status）
| Label | 说明 |
|-------|------|
| `status:new` | 新建，待分类 |
| `status:in-progress` | 处理中 |
| `status:fixed` | 已修复 |
| `status:wontfix` | 不予修复 |

## 处理流程

用户提交 Issue → 管家 Agent 扫描(10min) → 自动打 Label → 群聊汇报 → PM Agent 评估 → 撰写/更新 PRD → 评审 → 实施跟踪
