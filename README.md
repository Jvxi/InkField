<div align="center">

# 🖋️ 砚田 (InkField)

**AI 驱动的网络小说创作工作台**

[![Frontend](https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://github.com/Jvxi/InkField-frontend)
[![Backend](https://img.shields.io/badge/Backend-Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://github.com/Jvxi/InkField-backend)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

[![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white)]()
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-4169E1?style=flat-square&logo=postgresql&logoColor=white)]()
[![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=flat-square&logo=vite&logoColor=white)]()

<br/>

![GitHub Stars](https://img.shields.io/github/stars/Jvxi/InkField?style=social)
![GitHub Forks](https://img.shields.io/github/forks/Jvxi/InkField?style=social)

</div>

---

## ✨ 项目简介

> 面向网络小说作者的 **AI 辅助写作工作台**，支持从构思到成稿的全流程创作。
> 严格模式下约束正文纯度、必写情节点与禁写内容，让 AI 成为你的创作助手。

<br/>

## 🏗️ 项目架构

本项目采用**前后端分离**架构，代码分别托管在独立仓库：

<div align="center">

| 仓库 | 技术栈 | 链接 |
|:---:|:---:|:---:|
| 🖥️ **前端** | React + Vite + TypeScript | [![Repo](https://img.shields.io/badge/Repo-InkField--frontend-blue?style=for-the-badge&logo=github)](https://github.com/Jvxi/InkField-frontend) |
| ⚙️ **后端** | Spring Boot + Java 21 | [![Repo](https://img.shields.io/badge/Repo-InkField--backend-green?style=for-the-badge&logo=github)](https://github.com/Jvxi/InkField-backend) |
| 📦 **汇总** | 项目文档（本仓库） | [![Repo](https://img.shields.io/badge/Repo-InkField-purple?style=for-the-badge&logo=github)](https://github.com/Jvxi/InkField) |

</div>

<br/>

## 🚀 核心功能

<table>
<tr>
<td width="50%">

### 📝 创作流程
- 多页面工作流引导
- 开书 15 问问卷系统
- 大纲 / 角色 / 伏笔管理
- 章节流式生成与编辑

</td>
<td width="50%">

### 🤖 AI 能力
- OpenAI 兼容接口
- 流式输出实时预览
- 智能合规校验
- 未配置 Key 自动回退

</td>
</tr>
<tr>
<td width="50%">

### 📊 质量管控
- 严格正文模式
- 元标签检测
- 旁白解说过滤
- 必写节点校验

</td>
<td width="50%">

### 📚 平台支持
- 番茄小说
- 起点中文网
- QQ阅读
- 平台规则自动注入

</td>
</tr>
</table>

<br/>

## 🛠️ 技术栈

<div align="center">

| 层级 | 技术 |
|:---:|:---|
| **前端** | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=flat-square) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square) ![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white&style=flat-square) |
| **后端** | ![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?logo=springboot&logoColor=white&style=flat-square) ![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white&style=flat-square) ![Maven](https://img.shields.io/badge/-Maven-C71A36?logo=apachemaven&logoColor=white&style=flat-square) |
| **数据库** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat-square) ![Flyway](https://img.shields.io/badge/-Flyway-CC0200?logo=flyway&logoColor=white&style=flat-square) |

</div>

<br/>

## ⚡ 快速开始

> 请前往对应仓库查看详细的安装和运行说明

<div align="center">

[![Frontend README](https://img.shields.io/badge/📖_前端快速开始-Click_Here-61DAFB?style=for-the-badge&logo=github)](https://github.com/Jvxi/InkField-frontend#readme)
[![Backend README](https://img.shields.io/badge/📖_后端快速开始-Click_Here-6DB33F?style=for-the-badge&logo=github)](https://github.com/Jvxi/InkField-backend#readme)

</div>

### 环境要求

| 依赖 | 版本 |
|:---:|:---:|
| Node.js | 18+ |
| JDK | 21 |
| Maven | 3.9+ |
| PostgreSQL | 15+ |

<br/>

## 📁 目录结构

```
InkField/
├── 🖥️ frontend/          # 前端项目 (独立仓库)
│   ├── src/
│   │   ├── components/   # React 组件
│   │   ├── pages/        # 页面组件
│   │   ├── context/      # 状态管理
│   │   └── styles/       # 样式文件
│   └── ...
│
├── ⚙️ backend/            # 后端项目 (独立仓库)
│   ├── src/main/java/
│   │   ├── controller/   # API 控制器
│   │   ├── service/      # 业务逻辑
│   │   ├── model/        # 数据模型
│   │   └── persistence/  # 数据访问
│   └── ...
│
└── 📄 README.md           # 项目说明 (本文件)
```

<br/>

## 🌟 功能预览

<details>
<summary><b>📝 多页面工作流</b></summary>

```
书籍信息 → 开书问卷(15问) → 大纲 → 角色 → 伏笔 → 章节写作
```

每个环节独立页面，支持随时回溯修改。

</details>

<details>
<summary><b>🤖 AI 辅助写作</b></summary>

- 支持 OpenAI 兼容接口
- 流式输出，实时预览生成内容
- 未配置 API Key 时自动回退规则模板

</details>

<details>
<summary><b>✅ 严格合规校验</b></summary>

开启「严格正文模式」后，生成结果需同时满足：
- 无元标签
- 无旁白解说话术
- 大纲必保留项需在正文中体现
- 不命中禁写项

</details>

<br/>

---

<div align="center">

**⭐ 如果这个项目对你有帮助，请给一个 Star 支持一下！⭐**

![Visitor Count](https://komarev.com/ghpvc/?username=Jvxi&label=Visitors&color=blueviolet&style=flat-square)

<br/>

![GitHub Last Commit](https://img.shields.io/github/last-commit/Jvxi/InkField?style=flat-square)
![GitHub Commit Activity](https://img.shields.io/github/commit-activity/m/Jvxi/InkField?style=flat-square)

<br/>

**Made with ❤️ by [Jvxi](https://github.com/Jvxi)**

</div>
