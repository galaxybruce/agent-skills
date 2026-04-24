# Agent Skills 项目

一个为 AI 助手设计的技能集合项目，提供各种实用的工具和功能扩展。

English version: [README.en.md](README.en.md)

## 项目概述

本项目是一个技能（Skills）集合，专为 AI 助手和智能代理系统设计。每个技能都是一个独立的模块，提供特定的功能和能力，帮助 AI 助手更好地完成各种任务。

## 技能列表

### 1. Android 项目分析器 (android-project-analyzer)

**描述**：分析项目结构并生成标准的 Markdown 文档集（架构、技术栈、核心文件等）。

**功能特点**：
- 自动分析 Android 项目结构
- 生成详细的技术栈文档
- 创建项目架构说明
- 提供目录结构分析
- 识别核心文件和功能模块

**使用场景**：
- 当用户要求分析 Android 项目时
- 需要生成项目文档时
- 了解项目架构和技术栈时

**文档位置**：[skills/android-project-analyzer/SKILL.md](skills/android-project-analyzer/SKILL.md)

## 项目结构

```
agent-skills/
├── skills/
│   └── android-project-analyzer/
│       └── SKILL.md
├── README.md
└── README.en.md
```

## 如何使用

1. 查看各个技能目录下的 `SKILL.md` 文件，了解具体的使用方法和功能说明
2. 根据需求选择合适的技能模块
3. 按照技能文档中的指引进行集成和使用

## 贡献指南

欢迎提交新的技能模块或改进现有技能。请遵循以下步骤：

1. 创建新的技能目录
2. 在目录中添加 `SKILL.md` 文件，详细描述技能功能
3. 遵循项目的文档格式和命名规范
4. 提交 Pull Request

## 许可证

本项目采用开源许可证，具体信息请查看项目根目录的许可证文件。
