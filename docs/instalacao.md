# Instalação detalhada

Tribunal TJTO: Certidão Judicial é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_tjto_cert_judicial`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_tjto_cert_judicial` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_tjto_cert_judicial` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_tjto_cert_judicial` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_tjto_cert_judicial` (ou `servers.tribunal_tjto_cert_judicial` no VS Code) do config do cliente e reinicie.
