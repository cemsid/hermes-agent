# MCP (Model Context Protocol) Demo

This document demonstrates the integration of MCP tools with Hermes Agent.

## Overview

Hermes Agent supports MCP (Model Context Protocol) servers, enabling seamless tool use across different AI workflows.

## Demo Setup

### Prerequisites
- Hermes Agent installed and running
- MCP server configured

### Configuration Example
```json
{
  "mcpServers": {
    "demo-server": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem"],
      "env": {}
    }
  }
}
```

## Usage

1. Start the Hermes Agent with MCP support enabled
2. Connect your MCP server
3. Use natural language to interact with MCP tools

## Results

The agent successfully communicates with MCP servers, enabling extended tool capabilities beyond built-in skills.
