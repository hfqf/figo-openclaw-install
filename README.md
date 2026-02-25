# Figo's OpenClaw Installer Skill

[English](#english) | [中文](#chinese)

<a name="english"></a>
An automated, bilingual (Chinese/English) expert skill for installing and configuring OpenClaw, optimized for both local and cloud environments.

## Features

- **Automated Installation**: Generates `docker-compose.yml` and `.env` based on user needs.
- **Smart Proxy Detection**: Automatically detects system proxies (Env/Registry/Ports) for overseas model access.
- **Feishu Integration**:
  - Auto-fixes Windows `spawn EINVAL` errors.
  - Guides through App creation, permission setup, and binding.
- **Performance Optimization**:
  - Configures Fallback Models (Anti-Rate Limit).
  - Sets up Local Memory (QMD/SQLite) to save tokens.
  - Optimizes polling frequency for stability.
- **User Friendly**:
  - Bilingual support (auto-detects language).
  - Creates desktop shortcuts and user manuals.

## Installation

You can install this skill directly using `npx skills`:

```bash
# Install via GitHub
npx skills add https://github.com/hfqf/figo-openclaw-install
```

## Usage

Once installed, simply type:

> **`figo-openclaw-installer`**

Or ask naturally:
- "Help me install OpenClaw"
- "Config OpenClaw for Feishu"
- "OpenClaw 怎么装"

---

<a name="chinese"></a>
# Figo 的 OpenClaw 安装专家 Skill

这是一个全自动、中英双语的专家级 Skill，专为安装和配置 OpenClaw 而设计，针对本地和云端环境进行了优化。

## 功能特性

- **全自动化安装**：根据用户需求自动生成 `docker-compose.yml` 和 `.env` 配置文件。
- **智能代理检测**：自动检测系统代理（环境变量/注册表/常用端口），解决海外模型连接问题。
- **飞书深度集成**：
  - 自动修复 Windows 下的 `spawn EINVAL` 报错。
  - 全程引导应用创建、权限配置及绑定流程。
- **性能与稳定性优化**：
  - 配置备用模型（Fallback Models）以防止 API 限流。
  - 设置本地记忆（QMD/SQLite）以节省 Token 消耗。
  - 优化飞书状态查询频次（1小时），提升稳定性。
- **用户友好**：
  - 双语支持（自动识别用户语言）。
  - 自动创建桌面快捷方式和用户手册。

## 安装方法

使用 `npx skills` 命令直接安装：

```bash
# 通过 GitHub 安装
npx skills add https://github.com/hfqf/figo-openclaw-install
```

## 使用方法

安装完成后，在 Trae 对话框中输入：

> **`figo-openclaw-installer`**

或者直接用自然语言提问：
- “帮我安装 OpenClaw”
- “配置飞书插件”
- “OpenClaw 怎么装”

## 许可证

MIT
