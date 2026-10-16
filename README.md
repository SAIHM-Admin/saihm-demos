# SAIHM demos

The landing page and runnable demos for **[SAIHM](https://saihm.net)** — non-custodial, post-quantum memory for AI agents. One client-side-encrypted memory that every model can read, with erasure you can prove.

**Live page:** https://saihm-admin.github.io/saihm-demos/

## Demos

One repo per model — each runs fully offline against an included blind sandbox (no account needed to try it), or live against the hosted endpoint with one environment variable:

- **[demo-claude](https://github.com/SAIHM-Admin/demo-claude)** · **[demo-openai](https://github.com/SAIHM-Admin/demo-openai)** · **[demo-deepseek](https://github.com/SAIHM-Admin/demo-deepseek)** · **[demo-qwen](https://github.com/SAIHM-Admin/demo-qwen)** · **[demo-kimi](https://github.com/SAIHM-Admin/demo-kimi)** · **[demo-glm](https://github.com/SAIHM-Admin/demo-glm)**

And three that show the whole point — one memory, many surfaces:

- **[demo-cross-model-memory](https://github.com/SAIHM-Admin/demo-cross-model-memory)** — one encrypted memory shared across **Claude, DeepSeek, Qwen, Kimi, GLM, GPT**, plus provable crypto-shred erasure.
- **[demo-claude-code](https://github.com/SAIHM-Admin/demo-claude-code)** — SAIHM as an MCP server for Claude Code, Cursor, and any MCP host.
- **[saihm-langchain](https://github.com/SAIHM-Admin/saihm-langchain)** — SAIHM as a LangChain `BaseChatMessageHistory` and a LlamaIndex `BaseMemory` for Python; the same store opens from both.

## Built on

- [@saihm/mcp-server-pro](https://github.com/SAIHM-Admin/saihm-mcp-server-pro) — the production sealing client ([npm](https://www.npmjs.com/package/@saihm/mcp-server-pro)).
- [@saihm/client-pro](https://github.com/SAIHM-Admin/saihm-client-pro) — post-quantum client crypto ([npm](https://www.npmjs.com/package/@saihm/client-pro)).
- [@saihm/mcp-server](https://github.com/SAIHM-Admin/saihm-mcp) — the open MCP thin-client ([npm](https://www.npmjs.com/package/@saihm/mcp-server)).

## Learn more

- [Token benchmark](https://github.com/SAIHM-Admin/saihm-token-benchmark) — recalling a bounded memory instead of resending the transcript cuts context tokens **62.8%–85.9%** across a multi-session task (offline, reproducible).
- [AI memory needs a standard](https://saihm.net/blog/2026-05-18-ai-memory-needs-a-standard)
- [What makes SAIHM different](https://saihm.net/blog/2026-05-31-what-makes-saihm-different)

**Join the protocol:** https://saihm.net/join

Apache-2.0 © SAIHM
