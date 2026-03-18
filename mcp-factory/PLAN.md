# Niche MCP Server Factory: System Architecture

## Objective:
Turn API documentation into standardized, production-ready MCP (Model Context Protocol) server code.

## The Stack:
- **Frontend**: A sleek, minimal landing page for document input (OpenAPI, manual docs, or URLs).
- **Backend**: A "Vibe-Coding" agent (Sentry) that:
    1. Parses the docs.
    2. Generates a standard `mcp-server` scaffold (Node.js/TypeScript).
    3. Implements the tools (tools.json/index.js).
    4. Provides the `openclaw.json` config snippet for instant loading.

## Tool Integration:
- Uses `mcporter` for server validation.
- Uses `write`/`edit` for code generation.
- Uses `sessions_spawn` (runtime="acp") for isolated testing of the generated server.

## MVP Features:
- [ ] API Doc Text Area (Markdown/JSON/OpenAPI).
- [ ] "Factory Mode" selector (Simple HTTP, Auth-required, or Local CLI wrapper).
- [ ] Code Preview (The generated index.js).
- [ ] Install Command (The one-liner to add it to OpenClaw).
