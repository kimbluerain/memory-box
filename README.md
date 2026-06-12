# supermemory — 本地化 AI 记忆管理

> AI Memory as a Skill — not as a service.

**supermemory** 是一个纯 `.md` 文件即插即用的 AI 记忆系统。  
零依赖、零安装、零后台进程。**Obsidian 打开就是可视化记忆图谱。**

## 快速开始

1. 把 `sample-vault/` 复制到你想要的位置（比如 `~/ai-memory/`）
2. 告诉你的 AI Agent 读取 `supermemory.md` 这个 skill 文件
3. AI 会自动维护你的画像、技术偏好、项目决策
4. 用 Obsidian 打开同一个文件夹 → 图谱视图一览无余

## 文件说明

| 文件 | 作用 |
|------|------|
| `supermemory.md` | Skill 定义文件 — AI Agent 读这个就知道怎么维护记忆 |
| `sample-vault/` | 示例记忆库 — 复制即用，Obsidian 可直接打开 |

## 多 Agent 共享

所有指向同一个文件夹的 AI Agent 共用同一份记忆。  
Reasonix、Claude Code、Cline、Cursor... 只要支持文件读写就能接入。

## 与同类项目的区别

其他方案（bastra-recall、trail、frozo-vault-mem）都是**软件包**——需要 `npm install`、跑 MCP server、配 daemon。  
supermemory 是**一个 `.md` 文件**——复制粘贴就能用。它是规则，不是软件。
