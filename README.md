# Qoris Plugin Marketplace

Official plugin marketplace for [Qoris](https://qoris.ai).

## Install

```bash
# Step 1 — Add the Qoris marketplace (one-time, per machine)
claude plugin marketplace add qoris-ai/qoris-marketplace

# Step 2 — Install a plugin
claude plugin install knox@qoris
```

**Or add the marketplace manually** in `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "qoris": {
      "source": {
        "source": "github",
        "repo": "qoris-ai/qoris-marketplace"
      }
    }
  }
}
```

Then run `claude plugin install knox@qoris`.

## Available plugins

| Plugin | Description |
|--------|-------------|
| `knox` | Security enforcement plugin for Claude Code — out-of-process, intercepts every tool call, blocks dangerous commands, detects prompt injection. [Learn more →](https://qoris.ai/knox) |
