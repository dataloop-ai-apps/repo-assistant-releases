# Repo Assistant - Releases

Pre-built releases of the Repo Assistant MCP server for [Cursor IDE](https://cursor.com/).

## Installation

1. Add to your Cursor MCP config (`~/.cursor/mcp.json`):

```json
{
  "mcpServers": {
    "repo-assistant": {
      "command": "uvx",
      "args": [
        "--from",
        "https://github.com/dataloop-ai-apps/repo-assistant-releases/releases/download/v0.2.3/repo_assistant_mcp-0.2.3-py3-none-any.whl",
        "repo-assistant-mcp"
      ]
    }
  }
}
```

2. Restart Cursor.

> Replace the version in the URL with the [latest release](https://github.com/dataloop-ai-apps/repo-assistant-releases/releases).

## What is this?

An MCP server that provides role-based AI assistance, coding guidelines search, active learning, and repo memory across your projects.

## Requirements

- [Cursor IDE](https://cursor.com/)
- Python 3.10+
- [uv](https://docs.astral.sh/uv/) (for `uvx`)
