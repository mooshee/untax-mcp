# Untax MCP & Agent Plugin (`v0.4.4`)

[![Untax MCP server quality and maintenance on Glama](https://glama.ai/mcp/servers/mooshee/untax-mcp/badges/score.svg)](https://glama.ai/mcp/servers/mooshee/untax-mcp)

Research county property assessments, compare available records, and prepare a free private veteran review PDF from a saved review you select. Missing facts stay visible. A draft does not establish eligibility or authorize filing.

## Quick start

1. Follow the [Untax setup guide](https://untax.io/integrations/0.4.1) to connect a supported assistant to `https://untax.io/mcp`.
2. Ask about a property's available assessment records, a public VA office, or an official VA form. These public lookups require no account or API key. Check the response for sources and missing information.
3. If you request a private review or test checkout, follow the browser sign-in link and review the requested permissions.

Version 0.4.4 updates package descriptions and instructions. Existing connections and account permissions are unchanged. Read the [release notes](https://github.com/mooshee/untax-mcp/releases/tag/v0.4.4) or [release history](https://github.com/mooshee/untax-mcp/releases).

## Connect your assistant

### Claude Code / Claude Desktop
```bash
/plugin marketplace add mooshee/untax-mcp
claude plugin install untax@untax-marketplace
claude mcp add --transport http untax https://untax.io/mcp
```

### VS Code / GitHub Copilot
- [1-Click Install in VS Code](https://insiders.vscode.dev/redirect/mcp/install?name=untax&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Funtax.io%2Fmcp%22%7D)

### OpenAI Codex CLI / Desktop
```bash
codex mcp add untax --url https://untax.io/mcp
```

The downloadable package also includes the Codex plugin manifest, connection file, and both Untax skills.

### Cursor
Uses `.cursor-plugin/plugin.json` and `.cursor/mcp.json` (`https://untax.io/mcp`).

### Gemini CLI
```bash
gemini extensions install https://github.com/mooshee/untax-mcp
```

### Devin CLI / Desktop
```bash
devin plugins install mooshee/untax-mcp
```

### AWS Kiro Powers
Import this repository into Kiro Powers (`POWER.md` at repository root).

### Vercel Skills (`skills.sh`) & ClawHub
```bash
npx -y skills add mooshee/untax-mcp
clawhub install untax-research
```

## Package and review status

The release archives install the existing skills and remote connection. The included OpenAI review draft still needs a verified recording and provider checks before submission. Installing this package does not submit it to a directory or change the hosted service.

## Links
- **Website:** https://untax.io
- **MCP Endpoint:** `https://untax.io/mcp`
- **Privacy Policy:** https://untax.io/privacy
- **Terms of Service:** https://untax.io/terms
- **Support:** https://untax.io/support


---

Built and maintained by **[Moosh Works](https://mooshworks.com)**.
