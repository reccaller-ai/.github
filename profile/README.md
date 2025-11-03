<div align="center">
  
# 🚀 RecCaller.AI

**Universal AI Context Management for Modern Developers**

*Stop repeating yourself to AI. RecCall remembers everything so you don't have to.*

[![Website](https://img.shields.io/badge/Website-reccaller.ai-blue?style=flat-square)](https://reccaller.ai)
[![npm](https://img.shields.io/npm/v/reccall?style=flat-square)](https://www.npmjs.com/package/reccall)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://github.com/reccaller-ai/reccall/blob/main/LICENSE)

[Get Started](#-quick-start) • [Documentation](https://github.com/reccaller-ai/reccall#readme) • [Website](https://reccaller.ai) • [Issues](https://github.com/reccaller-ai/reccall/issues)

</div>

---

## 🌟 About RecCaller.AI

RecCaller.AI provides **universal context management** for AI-powered development tools. Never explain your project context, codebase structure, or preferences twice to AI assistants.

### Key Features

- 🎯 **Universal Context System** - Static, dynamic (ML-generated), and hybrid contexts
- 🔄 **Multi-Platform Support** - Works with Cursor, VSCode, Warp, Perplexity, Sora, and more
- 🤖 **ML-Powered Intelligence** - Automatic summarization, code extraction, and semantic search
- 🔐 **Enterprise-Ready** - Dependency injection, telemetry, and scalable storage backends
- ⚡ **High Performance** - Sub-millisecond operations with intelligent caching

### Statistics

- **70% Time Saved** - Eliminate repetitive context explanations
- **2-3 Hours Per Day** - Reclaimed from context switching
- **$50K+ Annual Value** - Per developer productivity gain

*[Learn more about our research and data sources](https://github.com/reccaller-ai/reccall/blob/main/docs/RESEARCH_DATA_SOURCES.md)*

---

## 📦 Repositories

### 🎯 [reccall](https://github.com/reccaller-ai/reccall) - Core Engine
**The universal AI context engine with plugin architecture.**

[![Stars](https://img.shields.io/github/stars/reccaller-ai/reccall?style=flat-square)](https://github.com/reccaller-ai/reccall)
[![npm](https://img.shields.io/npm/v/reccall?style=flat-square)](https://www.npmjs.com/package/reccall)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6+-blue?style=flat-square)](https://www.typescriptlang.org/)

**Core Features:**
- Universal Context Management System (UCS)
- ML-powered context generation
- Multi-platform adapters (CLI, MCP, VSCode, Warp, Browser)
- Enterprise features (DI, telemetry, Redis/PostgreSQL)
- REST API and JavaScript SDK

[📖 Documentation](https://github.com/reccaller-ai/reccall#readme) • [📦 npm Package](https://www.npmjs.com/package/reccall) • [🐛 Issues](https://github.com/reccaller-ai/reccall/issues)

---

### 🌐 [websites](https://github.com/reccaller-ai/websites) - Website Repository
**Official website for RecCaller.AI.**

[![Website](https://img.shields.io/badge/Website-Live-success?style=flat-square)](https://reccaller.ai)
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?style=flat-square)](https://reccaller.ai)

**Content:**
- Product landing pages
- Integration guides
- Getting started documentation
- Use cases and examples

[🌐 Live Site](https://reccaller.ai) • [📝 Source](https://github.com/reccaller-ai/websites)

---

### 📚 [contexts](https://github.com/reccaller-ai/contexts) - Context Store
**RecCall contexts repository - community-driven shortcut library.**

[![Contexts](https://img.shields.io/badge/Contexts-Available-brightgreen?style=flat-square)](https://contexts.reccaller.ai)

**Features:**
- Pre-built shortcuts for common workflows
- Community-contributed contexts
- Starter pack templates
- Integration examples

[📚 Browse Contexts](https://contexts.reccaller.ai) • [📖 Repository](https://github.com/reccaller-ai/contexts)

---

## 🚀 Quick Start

### Installation

```bash
# Quick install
curl -sfL https://reccaller.ai/install.sh | sh -

# Or via npm
npm install -g reccall
```

### Basic Usage

```bash
# Record a shortcut
reccall rec react-component "Create React components with TypeScript, proper props, and hooks"

# Call a shortcut
reccall call react-component

# List all shortcuts
reccall list

# Search shortcuts
reccall search api
```

### Integration

**Cursor IDE:**
```json
{
  "mcpServers": {
    "reccall": {
      "command": "reccall-mcp",
      "args": ["--stdio-only"]
    }
  }
}
```

**Full integration guide:** [Getting Started](https://reccaller.ai/pages/getting-started.html)

---

## 🏗️ Architecture

```
RecCaller.AI Organization
├── reccall/          → Core engine & platform adapters
├── websites/         → Official website (reccaller.ai)
└── contexts/         → Context store & shortcuts repository
```

### Technology Stack

- **Core**: TypeScript 5.6+, Node.js 18+
- **Platforms**: Cursor (MCP), VSCode, Warp, Browser Extensions
- **Storage**: Filesystem, Redis, PostgreSQL
- **ML**: Conversation summarization, code extraction, semantic embeddings
- **APIs**: REST API, JavaScript SDK, MCP Protocol

---

## 📊 Project Status

| Repository | Status | Latest Version | Language |
|------------|--------|---------------|----------|
| [reccall](https://github.com/reccaller-ai/reccall) | ✅ Active | [![npm](https://img.shields.io/npm/v/reccall?style=flat-square)](https://www.npmjs.com/package/reccall) | TypeScript |
| [websites](https://github.com/reccaller-ai/websites) | ✅ Live | - | HTML/CSS |
| [contexts](https://github.com/reccaller-ai/contexts) | ✅ Active | - | JSON |

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Report Issues**: Found a bug? [Open an issue](https://github.com/reccaller-ai/reccall/issues)
2. **Share Contexts**: Contribute shortcuts to the [contexts repository](https://github.com/reccaller-ai/contexts)
3. **Improve Documentation**: Help make our docs better
4. **Code Contributions**: Submit PRs for features and fixes

**See our [Contributing Guide](https://github.com/reccaller-ai/reccall/blob/main/docs/contributing/BRANCH_NAMING.md) for details.**

---

## 📚 Documentation

- **[Getting Started](https://reccaller.ai/pages/getting-started.html)** - Quick start guide
- **[How It Works](https://reccaller.ai/pages/how-it-works.html)** - Architecture overview
- **[API Reference](https://github.com/reccaller-ai/reccall/blob/main/docs/API_REFERENCE.md)** - REST API & SDK docs
- **[JavaScript SDK](https://github.com/reccaller-ai/reccall/blob/main/docs/JAVASCRIPT_SDK.md)** - SDK usage guide
- **[Enterprise Deployment](https://github.com/reccaller-ai/reccall/blob/main/docs/ENTERPRISE_DEPLOYMENT.md)** - Production setup

---

## 🔗 Links

- **Website**: [reccaller.ai](https://reccaller.ai)
- **Contexts Store**: [contexts.reccaller.ai](https://contexts.reccaller.ai)
- **npm Package**: [npmjs.com/package/reccall](https://www.npmjs.com/package/reccall)
- **Documentation**: [GitHub](https://github.com/reccaller-ai/reccall#readme)
- **Issues**: [GitHub Issues](https://github.com/reccaller-ai/reccall/issues)

---

## 📄 License

All repositories are licensed under the [MIT License](https://github.com/reccaller-ai/reccall/blob/main/LICENSE).

---

<div align="center">

**Built with ❤️ by the RecCaller.AI team**

[⭐ Star us on GitHub](https://github.com/reccaller-ai/reccall) • [💬 Discussions](https://github.com/reccaller-ai/reccall/discussions)

</div>

