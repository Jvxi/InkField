# 砚田 (InkField)

面向网络小说作者的 AI 辅助写作工作台。支持大纲、角色、伏笔、章节编排，并在严格模式下约束正文纯度、必写情节点与禁写内容。

## 项目结构

本项目采用前后端分离架构，代码分别托管在独立仓库：

| 仓库 | 链接 | 说明 |
|------|------|------|
| 🖥️ 前端 | [InkField-frontend](https://github.com/Jvxi/InkField-frontend) | React + Vite + TypeScript |
| ⚙️ 后端 | [InkField-backend](https://github.com/Jvxi/InkField-backend) | Spring Boot 3 (Java 21) |
| 📦 汇总 | [InkField](https://github.com/Jvxi/InkField) | 项目说明（本仓库） |

## 功能概览

- **多页面工作流**：书籍信息 → 开书问卷(15问) → 大纲 → 角色 → 伏笔 → 章节写作
- 项目骨架：书名、男频/女频、小说类型、发布平台、基调与规则
- **开书 15 问**：根据分类与书籍信息生成问题，完成后才允许 AI 写作
- 大纲 / 角色 / 伏笔：独立页面维护，写作时由后端注入，正文禁止复述设定
- 章节写作：流式生成、中途取消、严格合规校验
- AI 生成：OpenAI 兼容接口 + 流式输出；未配置 Key 时自动回退规则模板草稿
- 发布平台：番茄小说、起点中文网、QQ阅读
- 合规报告：元标签、旁白解说、大纲锚点、章节锚点、必写节点、禁写项检测

## 技术栈

| 层级 | 技术 |
|------|------|
| 前端 | React 18、Vite、TypeScript |
| 后端 | Spring Boot 3、Java 21、PostgreSQL、Flyway、Maven |

## 快速开始

请前往对应仓库查看详细说明：

- 👉 [前端 - 快速开始](https://github.com/Jvxi/InkField-frontend#readme)
- 👉 [后端 - 快速开始](https://github.com/Jvxi/InkField-backend#readme)

### 环境要求

- Node.js 18+
- JDK 21
- Maven 3.9+
- PostgreSQL 15+

## 许可证

MIT License
