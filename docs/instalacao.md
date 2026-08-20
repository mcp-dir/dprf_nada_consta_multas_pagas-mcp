# Instalação detalhada

DPRF Nada consta: Multas Pagas é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_dprf_nada_consta_multas_pagas`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_dprf_nada_consta_multas_pagas` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_dprf_nada_consta_multas_pagas` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_dprf_nada_consta_multas_pagas` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.dprf_nada_consta_multas_pagas` (ou `servers.dprf_nada_consta_multas_pagas` no VS Code) do config do cliente e reinicie.
