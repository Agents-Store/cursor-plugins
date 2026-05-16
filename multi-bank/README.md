# multi-bank (Cursor plugin)

Multi-Bank Account Manager with broadcast architecture pattern. Aggregates financial data from Monobank and PrivatBank via MCP tools, broadcasts balance updates and budget alerts to subscribed components, categorizes transactions, and exports financial reports in CSV/PDF.

## Install

Drop this directory into `~/.cursor/plugins/local/`, or publish via [cursor.com/marketplace/publish](https://cursor.com/marketplace/publish).

## MCP servers

Required environment variables (set in your shell or Cursor MCP env):

- `MONOBANK_MCP_URL`
- `PRIVATBANK_MCP_URL`

## Source

Auto-generated from the canonical Claude Code plugin. Do not edit directly.

Canonical: https://github.com/agents-store/claude-public-plugins