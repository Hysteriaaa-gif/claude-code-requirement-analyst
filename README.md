# Claude Code Skill: Requirement Analyst (需求分析专家)

🚀 这是一个专为 Anthropic **Claude Code CLI** 打造的自定义 Skill 插件。它可以将 Claude 转化为一位资深的系统分析师，结合你当前项目的本地代码上下文，自动输出结构化的 PRD 需求文档、Mermaid 流程图和敏捷任务拆解。

## ✨ 核心特性

- **代码上下文感知**：不仅分析你的想法，还会扫描当前工作区代码，确保新需求与旧系统架构不冲突。
- **标准化输出**：自动生成包含功能范围、Edge Cases（边界情况）和异常流的 Markdown 报告。
- **可视化支持**：自动编写 Mermaid.js 语法流程图，可在 GitHub 或支持的编辑器中直接渲染。
- **任务级拆解**：直接将宏观需求拆解为通俗易懂、适合团队开发者快速理解的最小 Todo 任务清单。

## 📦 安装方法

你可以选择将该 Skill 安装在**全局**（所有项目可用）或**单个项目**中。

### 方法 A：全局安装 (推荐)

打开终端，将该 Skill 配置文件放到你的全局 Claude 配置目录中：

```bash
# 创建目录
mkdir -p ~/.claude/skills/requirement-analyst

# 将本仓库的 SKILL.md 下载或移动到该目录下
