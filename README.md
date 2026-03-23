# Hono Skill

Agent Skill for developing Hono applications. Provides inline API reference and request testing via [Hono CLI](https://github.com/honojs/cli).

## Installation

### Claude Code

```bash
# Add marketplace
/plugin marketplace add yusukebe/hono-skill

# Install skill
/plugin install hono-skill@hono
```

### skills.sh

```bash
npx skills add yusukebe/hono-skill
```

## Skill

### hono

Build Hono web applications with inline API knowledge.

**Features:**

- Inline Hono API reference (routing, context, middleware, JSX, validation, RPC, streaming, helpers)
- Request testing via `hono request`

## MCP Server (Optional)

For the latest Hono documentation search and retrieval, add the `hono-docs` MCP server:

```bash
claude mcp add --transport http hono-docs https://hono-docs-mcp.yusukebe.workers.dev/mcp
```

Or add to your `.mcp.json`:

```json
{
  "mcpServers": {
    "hono-docs": {
      "type": "http",
      "url": "https://hono-docs-mcp.yusukebe.workers.dev/mcp"
    }
  }
}
```

## Requirements

- [Hono CLI](https://github.com/honojs/cli) - Install as devDependency (`npm install -D @hono/cli`)

## License

MIT
