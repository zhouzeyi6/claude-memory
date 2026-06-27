# CLAUDE.md (跨设备记忆)

## 环境
- Windows 11，使用 Git Bash（非 PowerShell / cmd）
- 全局代理已配置，网络无限制

## 工作习惯
- 回复用中文
- 实现任何功能前，优先用 GitHub MCP 搜索现成方案，不重复造轮子
- 网页结果需验证时用 Playwright MCP 截图确认
- 只有在没有合适现有方案时才自行实现

## MCP 工具策略
- GitHub MCP → 搜轮子、查代码、看 Issue，优先于 WebSearch
- Playwright MCP → 网页截图验证，优先于 WebFetch 文本描述

## 记忆机制
- 记忆仓库: https://github.com/zhouzeyi6/claude-memory
- 每个项目用 Issue 记录上下文
- Labels: project / decision / preference / context
