# Hermes Agent 使用指南

Hermes Agent 的中文网页版教程，面向小白用户，涵盖安装、使用、配置和排障全流程。

## 在线预览

> 如果你只是想看效果，直接打开 `index.html` 即可 — 纯静态页面，无需构建。

## 内容概览

| 章节 | 说明 |
|------|------|
| 首页 | 功能介绍、一键安装命令 |
| 快速开始 | Linux / macOS / Windows / WSL 安装步骤 |
| 基础使用 | 交互对话、单次查询、会话管理、常用斜杠命令 |
| 场景命令生成器 | 交互式选择场景，自动生成对应命令（模型/Profile/Skills/消息平台/MCP/定时任务/配置/凭证） |
| Skills 系统 | 技能概念、管理命令、Curator、自定义 Skill |
| 配置管理 | 配置文件位置、常用配置项、支持的提供商 |
| 消息平台 | 13 个平台的接入指南和网关管理 |
| 进阶功能 | Delegation、Voice、Webhook、Cron、插件 |
| 常见问题 | 工具/模型/Gateway 问题、中国网络环境、Windows 专属问题 |

## 特性

- 纯静态 HTML/CSS/JS，零依赖，单文件
- 左侧导航栏 + Hash 路由
- 所有代码块带一键复制
- 命令生成器支持搜索过滤
- 移动端响应式（侧栏可折叠）
- 中文界面

## 本地使用

直接用浏览器打开：

```bash
# 或者起一个本地服务器
python3 -m http.server 8899
# 访问 http://localhost:8899
```

## 相关链接

- [Hermes Agent GitHub](https://github.com/NousResearch/hermes-agent)
- [官方文档](https://hermes-agent.nousresearch.com/docs/)

## License

MIT
