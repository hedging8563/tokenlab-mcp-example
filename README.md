# TokenLab MCP Example

[![CI](https://github.com/hedging8563/tokenlab-mcp-example/actions/workflows/ci.yml/badge.svg)](https://github.com/hedging8563/tokenlab-mcp-example/actions/workflows/ci.yml)

Example configuration for using the TokenLab MCP server with Claude Desktop, Cursor, Windsurf, and other MCP clients.

## Quickstart

Install and run the published MCP server:

```bash
npx -y @tokenlabai/mcp-server
```

Copy `mcp-config.json` into your MCP client configuration. Public catalog tools work without a key. Add `TOKENLAB_API_KEY` to the `env` object to enable inference tools.

## Tools

- `list_models`
- `get_model`
- `get_model_pricing`
- `compare_models`
- `get_api_overview`
- `create_chat_completion` with `TOKENLAB_API_KEY`
- `create_response` with `TOKENLAB_API_KEY`
- `create_anthropic_message` with `TOKENLAB_API_KEY`
- `create_gemini_content` with `TOKENLAB_API_KEY`

## Links

- MCP server: https://github.com/hedging8563/tokenlab-mcp-server
- Docs: https://tokenlab.sh/docs/en/integrations/tokenlab-mcp-server
