# dokploy-dev (Cursor plugin)

Dokploy self-hosted PaaS development plugin (aligned with Dokploy v0.30.x). Deploy applications, provision 6 database types (Postgres, MySQL, MariaDB, MongoDB, Redis, LibSQL), manage domains and Docker Compose stacks, AND debug failed deployments end-to-end — reads runtime logs of every container (including each container in a Docker Compose stack) over the API/MCP with tail/since/search, plus AI-powered log analysis (ai-analyzeLogs), Docker container and host introspection (server health, events, disk usage, images, volumes), Traefik diagnosis, and a guided recovery chain. Complete MCP/REST coverage: all 604 operations across 57 categories indexed with params — covers per-service Docker network management, vault (external secrets) providers, DNS providers, forward-auth SSO domain protection, SCIM provisioning, build concurrency, and the auto-generated @dokploy/cli (604 commands incl. read-logs). Uses the official @dokploy/mcp server (secret fields are redacted by default since 0.30.0) plus debugging-focused slash commands including /compose-logs.

## Install

Drop this directory into `~/.cursor/plugins/local/`, or publish via [cursor.com/marketplace/publish](https://cursor.com/marketplace/publish).

## MCP servers

Required environment variables (set in your shell or Cursor MCP env):

- `DOKPLOY_API_KEY`
- `DOKPLOY_URL`

## Source

Auto-generated from the canonical Claude Code plugin. Do not edit directly.

Canonical: https://github.com/agents-store/claude-public-plugins