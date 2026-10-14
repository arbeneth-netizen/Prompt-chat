# Prompt-chat
Automatischen Zugang auf die prompt Bibliothek 

## MCP-Server

Die Datei `.mcp.json` registriert den [prompts.chat](https://prompts.chat) MCP-Server
(`npx -y prompts.chat mcp`). Claude Code lädt ihn automatisch in diesem Projekt.

Verfügbare Tools:

- `search_prompts` – Prompts per Stichwort suchen (Filter: `type`, `category`, `tag`, `limit`)
- `get_prompt` – einen Prompt per ID abrufen

Manuell starten:

```sh
npx -y prompts.chat mcp
```
