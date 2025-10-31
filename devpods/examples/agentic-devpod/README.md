🔋 Agentic-Focused Development DevPod

This Devpod is designed for Agentic development environment with Docker-in-Docker, Node.js, Claude Flow, AI Swarm orchestration, and automatic Claude Code launch capabilities.

## 📦 What's Included

- **🖼️ Base Image**: Debian-based development container
- **🐳 Docker-in-Docker**: Build and run containers within your development environment
- **🟢 Node.js**: Full Node.js development environment
- **🐍 Python**: Python development environment
- **🛠️ Development Tools** (auto-installed on container creation):
  - tmux: Terminal multiplexer for managing multiple sessions
  - claude-code: Anthropic's official CLI for Claude
- **🧬 VS Code Extensions**:
  - Roo Cline: AI-powered coding assistant

## ✨ Features

- Runs with privileged access to support Docker operations
- Configured for the `vscode` user
- Persistent container (won't shutdown on disconnect)
- Automatic tool installation with graceful fallback and detailed installation report
- Installation report saved to `.devcontainer/installation-report.md` for troubleshooting
- If automatic installation fails during container startup, run manually: `bash .devcontainer/install-tools.sh`

## 📋 Requirements

- [DevPod CLI](https://devpod.sh/docs/getting-started/install)
- Docker Desktop or Docker Engine
- Active GitHub Copilot subscription (for Copilot features)
