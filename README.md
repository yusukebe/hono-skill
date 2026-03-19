# Hono Skill

Agent Skill for developing Hono applications. Provides inline API reference and uses [Hono CLI](https://github.com/honojs/cli) minimally for documentation search and request testing.

## Installation

### Claude Code

```bash
# Add marketplace
/plugin marketplace add yusukebe/hono-skill

# Install skill
/plugin install hono-skill@hono
```

## Skill

### hono

Build Hono web applications with inline API knowledge.

**Features:**

- Inline Hono API reference (routing, context, middleware, JSX, validation, RPC, streaming, helpers)
- Documentation search via `hono search` / `hono docs`
- Request testing via `hono request`

## Requirements

- [Hono CLI](https://github.com/honojs/cli) - Install as devDependency (`npm install -D @hono/cli`)

## License

MIT
