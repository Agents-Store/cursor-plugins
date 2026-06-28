# restic-dev (Cursor plugin)

restic backup plugin for Agents Store. Set up encrypted daily backups on any Linux server to S3-compatible storage (Cloudflare R2): server recon + restic install, auto-discovery of all Docker volumes/mounts and databases, R2 repository init, a partial-failure-tolerant backup script with logical DB dumps and retention, timezone-aware systemd/cron scheduling, verification, monitoring/dead-man's-switch, and disaster recovery. File-based knowledge, no MCP, no stored credentials.

## Install

Drop this directory into `~/.cursor/plugins/local/`, or publish via [cursor.com/marketplace/publish](https://cursor.com/marketplace/publish).

## Source

Auto-generated from the canonical Claude Code plugin. Do not edit directly.

Canonical: https://github.com/agents-store/claude-public-plugins