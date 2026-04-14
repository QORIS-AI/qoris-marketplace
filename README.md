# Qoris Plugin Marketplace

Official plugin marketplace for [Qoris](https://qoris.ai).

## Add this marketplace to Claude Code

In `~/.claude/settings.json`:

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

## Install plugins

```bash
claude plugin install knox@qoris
```

## Available plugins

| Plugin | Description |
|--------|-------------|
| `knox` | Security enforcement layer for Claude Code — blocks dangerous commands, audits every tool call, detects prompt injection |
