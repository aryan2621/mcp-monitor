# Cloud live tests

MCP servers that use the **published** cloud SDKs (`mcp-monitor-sdk` on npm and PyPI), not the repo `file:` copies.

| Path | Server | Language |
|---|---|---|
| [js](js) | inventory-mcp | TypeScript |
| [python](python) | shop-mcp | Python |

Create a server + API key per MCP at [https://mcp-monitor.vercel.app/](https://mcp-monitor.vercel.app/), then run with `MCP_API_KEY` set.
