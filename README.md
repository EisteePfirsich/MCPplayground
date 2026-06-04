# MCPplayground

Home project playground to experiment with:

- running an MCP server locally
- connecting a local AI model to that MCP server
- using MCP-powered repository tools from the model

## Goal

Figure out a practical local setup where an AI model can call MCP repo tools to inspect and work with code safely.

## Planned workflow

1. Start a local MCP server implementation.
2. Configure a local AI model client to connect to the MCP server.
3. Expose repository tools through MCP (search, file read, edits, etc.).
4. Validate end-to-end tool calls from the local model against this repo.
