# Agent Skills Project

A collection of skills designed for AI assistants, providing practical tools and capability extensions.

中文版本: [README.md](README.md)

## Overview

This repository is a collection of skills for AI assistants and agent systems. Each skill is an independent module that provides a focused capability to help an assistant complete specific tasks.

## Skills

### 1. Android Project Analyzer (android-project-analyzer)

**Description**: Analyzes a project's structure and generates a standard set of Markdown documents (architecture, tech stack, core files, etc.).

**Key capabilities**:
- Analyze Android project structure
- Generate technology stack documentation
- Produce architecture documentation
- Provide directory structure breakdown
- Identify core files and key modules

**When to use**:
- When a user requests analysis of an Android project
- When you need to generate/refresh project documentation
- When you need a quick understanding of architecture and tech stack

**Documentation**: [skills/android-project-analyzer/SKILL.md](skills/android-project-analyzer/SKILL.md)

## Repository Structure

```
agent-skills/
├── skills/
│   └── android-project-analyzer/
│       └── SKILL.md
├── README.md
└── README.en.md
```

## How to Use

1. Open each skill's `SKILL.md` to understand its purpose and workflow
2. Pick the right skill module for your task
3. Follow the steps defined in the skill documentation

## Contributing

Contributions are welcome:

1. Create a new skill directory
2. Add a `SKILL.md` describing the skill clearly
3. Keep naming and structure consistent with existing skills
4. Open a Pull Request

## License

See the license file in the repository root (if present).
