# TokenLab MCP Example

Example configuration for using the TokenLab MCP server with Claude Desktop, Cursor, Windsurf, and other MCP clients.

## Quickstart

Clone and run the MCP server:

```bash
git clone https://github.com/hedging8563/tokenlab-mcp-server.git
cd tokenlab-mcp-server
npm install
npm start
```

Then copy `mcp-config.json` into your MCP client configuration and update the local path.

## Tools

- `list_models`
- `get_model`
- `get_model_pricing`
- `compare_models`
- `get_api_overview`
- `create_response` with `TOKENLAB_API_KEY`
- `create_anthropic_message` with `TOKENLAB_API_KEY`
- `create_gemini_content` with `TOKENLAB_API_KEY`

## Links

- MCP server: https://github.com/hedging8563/tokenlab-mcp-server
- Docs: https://docs.tokenlab.sh/integrations/tokenlab-mcp-server
