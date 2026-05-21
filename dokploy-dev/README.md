# dokploy-dev (Cursor plugin)

Dokploy self-hosted PaaS development plugin (aligned with Dokploy v0.29.x). Deploy applications, provision 6 database types (Postgres, MySQL, MariaDB, MongoDB, Redis, LibSQL), manage domains and Docker Compose stacks, AND debug failed deployments end-to-end with AI-powered log analysis (ai-analyzeLogs), Docker container introspection, Traefik diagnosis, and a guided recovery chain. Uses the official @dokploy/mcp server (500+ tools across 49 categories) plus 5 debugging-focused slash commands.

## Install

Drop this directory into `~/.cursor/plugins/local/`, or publish via [cursor.com/marketplace/publish](https://cursor.com/marketplace/publish).

## MCP servers

Required environment variables (set in your shell or Cursor MCP env):

- `DOKPLOY_API_KEY`
- `DOKPLOY_URL`

## Source

Auto-generated from the canonical Claude Code plugin. Do not edit directly.

Canonical: https://github.com/agents-store/claude-public-plugins