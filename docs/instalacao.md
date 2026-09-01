# Instalação detalhada

Jurisprudência TRF3 é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_trf3`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_trf3` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_trf3` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_trf3` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.trf3` (ou `servers.trf3` no VS Code) do config do cliente e reinicie.
