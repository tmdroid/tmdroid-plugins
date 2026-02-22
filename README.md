# tmdroid Claude Code Plugins

A custom marketplace for Claude Code plugins.

## Installation

```bash
# Add the marketplace (one-time)
claude plugin marketplace add tmdroid/tmdroid-plugins

# Install plugins
claude plugin install claude-rpi@tmdroid-plugins
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **[claude-rpi](https://github.com/tmdroid/claude-rpi)** | Research-Plan-Implement workflow — systematic codebase research, iterative planning with annotation cycles, and supervised implementation |

## For AI Agents

```bash
claude plugin marketplace add tmdroid/tmdroid-plugins && \
claude plugin install claude-rpi@tmdroid-plugins --scope user
```
