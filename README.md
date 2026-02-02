# Tenx MCP Analysis Setup

This repository is used to enable the **Tenx MCP Analysis** server, which passively captures and evaluates human–AI collaboration during coding sessions.

The MCP runs in the background and logs interaction quality (clarity, context, persistence) without interrupting the developer’s workflow.

## What this does
- Connects VS Code to the Tenx MCP Analysis server
- Enables non-invasive logging of AI-assisted coding interactions
- Supports structured feedback and performance evaluation

## Requirements
- Latest version of VS Code
- GitHub Copilot & GitHub Copilot Chat installed
- GitHub authentication

## Setup
MCP configuration is located in:
- `.vscode/mcp.json`
- `.github/copilot-instructions.md`

Once configured, start the MCP server from VS Code and authenticate via GitHub.

That’s it — no manual interaction required after setup.
