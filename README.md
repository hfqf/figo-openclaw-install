# Figo's OpenClaw Installer Skill

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
npx skills add <your-github-username>/<repo-name>
```

*Replace `<your-github-username>/<repo-name>` with your actual GitHub repository path.*

## Usage

Once installed, simply type:

> **`figo-openclaw-installer`**

Or ask naturally:
- "Help me install OpenClaw"
- "Config OpenClaw for Feishu"
- "OpenClaw 怎么装"

## License

MIT
