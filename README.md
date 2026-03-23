# MCP Agent Pack

Features:
- Dynamic GitHub template fetching
- Local caching (.vscode/mcp_cache)
- Multi-repo aware
- Self-healing agents
- Compressed persistent state
- Logging for auditing

## Usage

1. Configure .vscode/mcp.json with your GitHub URL.
2. MCP automatically fetches templates to cache on-demand.
3. Run MCP orchestrator in Copilot Chat:

```txt
@mcp.sdlc-agents.orchestrate
Add JWT authentication across all services
