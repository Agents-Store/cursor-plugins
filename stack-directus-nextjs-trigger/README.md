# stack-directus-nextjs-trigger (Cursor plugin)

Directus + Next.js + Trigger.dev architecture plugin. How Directus (content, files, access), a Next.js App Router frontend and self-hosted Trigger.dev (durable and scheduled work) fit together: who holds which token, how the cache is invalidated, how a Directus change reaches a task and the result reaches the page, who owns the session, and a production checklist. Tool knowledge comes from its dependencies.

## Install

Drop this directory into `~/.cursor/plugins/local/`, or publish via [cursor.com/marketplace/publish](https://cursor.com/marketplace/publish).

## MCP servers

Required environment variables (set in your shell or Cursor MCP env):

- `DIRECTUS_ADMIN_TOKEN`
- `NEXT_PUBLIC_DIRECTUS_URL`
- `TRIGGER_ACCESS_TOKEN`
- `TRIGGER_API_URL`
- `TRIGGER_PROJECT_REF`

## Source

Auto-generated from the canonical Claude Code plugin. Do not edit directly.

Canonical: https://github.com/agents-store/claude-public-plugins