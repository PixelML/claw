<p align="center">
  <img src="assets/logo.png" alt="Claw Logo" width="120" height="120">
</p>

<h1 align="center">Claw</h1>
<p align="center">
  <strong>Your Digital Chief of Staff</strong>
</p>
<p align="center">
  The Executive OS that empowers you to control your local file system through AI agents.
</p>

<p align="center">
  <a href="https://github.com/PixelML/claw/releases/latest">
    <img src="https://img.shields.io/github/v/release/PixelML/claw?style=flat-square" alt="Latest Release">
  </a>
  <a href="https://github.com/PixelML/claw/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/PixelML/claw?style=flat-square" alt="License">
  </a>
  <a href="https://discord.gg/agenticflow">
    <img src="https://img.shields.io/discord/1234567890?style=flat-square&logo=discord&label=Discord" alt="Discord">
  </a>
</p>

---

## 🚀 Download

### Desktop App

| Platform | Download |
|----------|----------|
| 🍎 **macOS** (Apple Silicon) | [Claw_aarch64.dmg](https://github.com/PixelML/claw/raw/main/releases/Claw_aarch64.dmg) |
| 🍎 **macOS** (Intel) | [Claw_x64.dmg](https://github.com/PixelML/claw/raw/main/releases/Claw_x64.dmg) |
| 🪟 **Windows** | Coming Soon |
| 🐧 **Linux** (AppImage) | Coming Soon |
| 🐧 **Linux** (deb) | Coming Soon |

### CLI Installation

```bash
# Quick install (recommended)
curl -fsSL https://clawdev.com/install | bash

# Using npm
npm i -g @pixelml/claw

# Using Homebrew (macOS)
brew install claw

# Using Scoop (Windows)
scoop install claw
```

---

## ✨ Features

- **🔍 Trust UI** - See exactly what will happen before any file operation executes
- **🔒 Privacy First** - All data stays on your machine, no cloud storage
- **⚡ AI-Powered** - Intelligent automation with natural language commands
- **🖥️ Desktop Native** - Built with Tauri for blazing-fast performance
- **🤖 Multi-Agent** - Run multiple AI agents in parallel
- **🔗 Any AI Provider** - Works with Claude, GPT, Gemini, or local models

---

## 📖 Documentation

- [Getting Started Guide](https://docs.clawdev.com/getting-started)
- [CLI Reference](https://docs.clawdev.com/cli)
- [Desktop App Guide](https://docs.clawdev.com/desktop)
- [API Documentation](https://docs.clawdev.com/api)

---

## 🛠️ Building from Source

### Prerequisites

- [Node.js](https://nodejs.org/) 18+
- [Rust](https://rustup.rs/) (latest stable)
- [Bun](https://bun.sh/) (recommended) or npm

### Desktop App

```bash
# Clone the repository
git clone https://github.com/PixelML/claw-core.git
cd claw-core

# Install dependencies
bun install

# Run in development mode
bun run dev

# Build for production
cd packages/desktop
bun run tauri build
```

### CLI

```bash
# The CLI is built as part of the monorepo
cd packages/claw
bun run build
```

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

---

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

---

## 🔗 Links

- [Website](https://clawdev.com)
- [Documentation](https://docs.clawdev.com)
- [Discord Community](https://discord.gg/agenticflow)
- [Twitter/X](https://twitter.com/_clawdev)
- [AgenticFlow](https://agenticflow.ai)

---

<p align="center">
  Made with ❤️ by <a href="https://pixelml.com">Pixel ML</a>
</p>
