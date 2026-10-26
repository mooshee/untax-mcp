# Untax MCP & Agent Plugin (`v0.4.2`)

[![Untax MCP server quality and maintenance on Glama](https://glama.ai/mcp/servers/mooshee/untax-mcp/badges/score.svg)](https://glama.ai/mcp/servers/mooshee/untax-mcp)

Source-backed property assessment research and draft assessment comparisons for supported pilot jurisdictions. Free private veteran review PDFs use explicitly selected saved reviews and show unanswered questions. Retained county facts, owner reports and optional permitted VA observations remain distinct.

## Quick start

1. Open [Untax](https://untax.io) in your browser or connect your MCP client to `https://untax.io/mcp` (or `https://untax.io/api/v1/mcp`).
2. Public property-assessment and VA office/form lookups are free and require no account or API key.

## Install Across Agent Harnesses

### Claude Code / Claude Desktop
```bash
claude mcp add --transport http untax https://untax.io/mcp
```

### OpenAI Codex CLI / Desktop
Add `.codex-plugin/plugin.json` or `.mcp.json` pointing to `https://untax.io/mcp`.

### Cursor
Uses `.cursor-plugin/plugin.json` and `.cursor/mcp.json` (`https://untax.io/mcp`).

### Gemini CLI
```bash
gemini extensions install https://github.com/mooshee/untax-mcp
```

### AWS Kiro Powers
Import this repository into Kiro Powers (`POWER.md` at repository root).

### Vercel Skills (`skills.sh`) & ClawHub
```bash
npx -y skills add mooshee/untax-mcp
clawhub install untax-research
```

## Links
- **Website:** https://untax.io
- **MCP Endpoint:** `https://untax.io/mcp`
- **Privacy Policy:** https://untax.io/privacy
- **Terms of Service:** https://untax.io/terms
- **Support:** https://untax.io/support
